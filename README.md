```markdown
---
layout: page
title: "Workshop Schedule"
permalink: /schedule/
---

<table>
  <thead>
    <tr>
      <th>Time</th>
      {% for day in site.data.schedule %}
      <th>{{ day.day }}</th>
      {% endfor %}
    </tr>
  </thead>
  <tbody>
    {% assign all_times = site.data.schedule | map: "sessions" | flatten | map: "start" | uniq %}
    {% for time in all_times %}
      <tr>
        <td>{{ time }}–{% for s in site.data.schedule[0].sessions %}{% if s.start == time %}{{ s.end }}{% endif %}{% endfor %}</td>
        {% for day in site.data.schedule %}
          <td>
            {% assign match = day.sessions | where: "start", time | first %}
            {% if match %}
              **{{ match.title }}**<br>
              *{{ match.lecturer }}*<br>
              {% if match.slides %}[Slides]({{ match.slides }}){% endif %}
              {% if match.tutorial %} • [Tutorial]({{ match.tutorial }}){% endif %}
            {% else %}
              {% if day.full_day == false %}&nbsp;{% endif %}
            {% endif %}
          </td>
        {% endfor %}
      </tr>
    {% endfor %}
  </tbody>
</table>
```