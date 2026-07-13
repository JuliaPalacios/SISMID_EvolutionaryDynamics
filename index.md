---
layout: page
title: ""
---

Instructor(s): Julia A. Palacios and Nicola F. Müller

## General

This module covers the use of phylogenetic and bioinformatic tools to analyze pathogen genetic variation and to gain insight into the processes that shape their diversity. The module focuses on phylogenies and how these relate to population genetic processes in infectious diseases.

In particular, the module will cover Bayesian Evolutionary Analysis by Sampling Trees 2 (BEAST2). Class exercises will focus on estimating epidemic time scales, reconstructing changes in viral population sizes through time, and inferring spatial diffusion of viruses. Evolutionary processes including recombination and selection will also be considered.

## Before the course

Please install the newest version (2.7.8) of [BEAST2](https://www.beast2.org/) on the computer you plan to use. BEAST2 requires Java. If you encounter installation issues, post in the SISMID Slack channel `jul15-viral-evolution`.

Also install:
- [Tracer 1.7.2](https://github.com/beast-dev/tracer/releases/tag/v1.7.2) to visualize MCMC traces.
- [Figtree 1.4.4](https://github.com/rambaut/figtree/releases/tag/v1.4.4) to view phylogenies. If you get a Java error, try [Figtree 1.4.5_pre](https://github.com/rambaut/figtree/releases/tag/v1.4.5pre).

---

## Schedule

<table class="schedule-table">
  <thead>
    <tr>
      <th>Time</th>
      {% for day in site.data.schedule %}
        <th>{{ day.day }}</th>
      {% endfor %}
    </tr>
  </thead>
  <tbody>
    {% comment %}
    First, collect all unique times and sort them properly (chronologically with AM before PM)
    {% endcomment %}
    {% assign all_times = "" | split: "" %}
    {% for day in site.data.schedule %}
      {% for session in day.sessions %}
        {% unless all_times contains session.start %}
          {% assign all_times = all_times | push: session.start %}
        {% endunless %}
      {% endfor %}
    {% endfor %}
    
    {% comment %}
    Convert times to 24-hour format for proper sorting, handling AM/PM
    {% endcomment %}
    {% assign time_pairs = "" | split: "" %}
    {% for time in all_times %}
      {% assign time_lower = time | downcase %}
      {% assign is_pm = false %}
      {% if time_lower contains "pm" %}
        {% assign is_pm = true %}
        {% assign clean_time = time_lower | replace: "pm", "" | strip %}
      {% elsif time_lower contains "am" %}
        {% assign clean_time = time_lower | replace: "am", "" | strip %}
      {% else %}
        {% assign clean_time = time %}
      {% endif %}
      
      {% assign time_parts = clean_time | split: ":" %}
      {% assign hour = time_parts[0] | plus: 0 %}
      {% assign minute = time_parts[1] | plus: 0 %}
      
      {% comment %}Convert to 24-hour format{% endcomment %}
      {% if is_pm and hour != 12 %}
        {% assign hour = hour | plus: 12 %}
      {% elsif is_pm == false and hour == 12 %}
        {% assign hour = 0 %}
      {% endif %}
      
      {% if hour < 10 %}
        {% assign hour_padded = hour | prepend: "0" %}
      {% else %}
        {% assign hour_padded = hour | append: "" %}
      {% endif %}
      {% if minute < 10 %}
        {% assign minute_padded = minute | prepend: "0" %}
      {% else %}
        {% assign minute_padded = minute | append: "" %}
      {% endif %}
      {% assign sort_key = hour_padded | append: ":" | append: minute_padded %}
      {% assign pair = sort_key | append: "|" | append: time %}
      {% assign time_pairs = time_pairs | push: pair %}
    {% endfor %}
    
    {% assign sorted_pairs = time_pairs | sort %}
    {% assign sorted_times = "" | split: "" %}
    {% for pair in sorted_pairs %}
      {% assign parts = pair | split: "|" %}
      {% assign sorted_times = sorted_times | push: parts[1] %}
    {% endfor %}
    
    {% comment %}
    Now create rows for each time slot
    {% endcomment %}
    {% for time in sorted_times %}
      <tr>
        <td class="time-slot">{{ time }}</td>
        {% for day in site.data.schedule %}
          {% assign current_session = day.sessions | where: "start", time | first %}
          <td class="session-cell">
            {% if current_session %}
              <div class="session-content">
                <strong>{{ current_session.title }}</strong>
                {% if current_session.lecturer %}
                  <br><em>{{ current_session.lecturer }}</em>
                {% endif %}
                {% if current_session.slides or current_session.tutorial %}
                  <div class="session-links">
                    {% if current_session.slides %}
                      <a href="{{ current_session.slides }}" target="_blank" class="session-link">Slides</a>
                    {% endif %}
                    {% if current_session.tutorial %}
                      {% if current_session.slides %} • {% endif %}
                      <a href="{{ current_session.tutorial }}" target="_blank" class="session-link">Tutorial</a>
                    {% endif %}
                  </div>
                {% endif %}
              </div>
            {% else %}
              {% comment %}
              Check if this cell should be part of a multi-time session from previous rows
              {% endcomment %}
              {% assign spanning_session = nil %}
              {% for prev_time in sorted_times %}
                {% if prev_time >= time %}
                  {% break %}
                {% endif %}
                {% assign prev_session = day.sessions | where: "start", prev_time | first %}
                {% if prev_session.end and prev_session.end > time %}
                  {% assign spanning_session = prev_session %}
                {% endif %}
              {% endfor %}
              
              {% if spanning_session %}
                <div class="session-continuation">
                  <!-- This cell is part of {{ spanning_session.title }} -->
                </div>
              {% endif %}
            {% endif %}
          </td>
        {% endfor %}
      </tr>
    {% endfor %}
  </tbody>
</table>

---

<style>
.schedule-table {
  width: 100%;
  border-collapse: collapse;
  margin: 20px 0;
  font-size: 14px;
}

.schedule-table th,
.schedule-table td {
  border: 1px solid #ddd;
  padding: 12px;
  text-align: left;
  vertical-align: top;
}

.schedule-table th {
  background-color: #052049;
  color: white;
  font-weight: bold;
  text-align: center;
}

.time-slot {
  background-color: #f8f9fa;
  font-weight: bold;
  text-align: center;
  width: 100px;
}

.session-cell {
  min-height: 60px;
  position: relative;
}

.session-content {
  line-height: 1.4;
}

.session-links {
  margin-top: 8px;
  font-size: 12px;
}

.session-link {
  color: #052049;
  text-decoration: none;
  font-weight: bold;
}

.session-link:hover {
  text-decoration: underline;
}

.session-continuation {
  height: 100%;
  background-color: #f0f0f0;
  opacity: 0.3;
}

/* Make table responsive */
@media (max-width: 768px) {
  .schedule-table {
    font-size: 12px;
  }
  
  .schedule-table th,
  .schedule-table td {
    padding: 8px;
  }
}
</style>

## Some Reading Material (optional)

- Overview of BEAST2 packages: [doi:10.1371/journal.pcbi.1006650](https://doi.org/10.1371/journal.pcbi.1006650)
- Decoding Genomes: [decodinggenomes.org](https://decodinggenomes.org/)
- Review of phylodynamics (coalescent focus): [PLoS Comput Biol 100.2947](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002947), [Statistical Challenges in Tracking the Evolution of SARS-CoV-2](https://projecteuclid.org/journals/statistical-science/volume-37/issue-2/Statistical-Challenges-in-Tracking-the-Evolution-of-SARS-CoV-2/10.1214/22-STS853.full)
- Review of phylodynamics in livestock: [ScienceDirect S0169534721001300](https://www.sciencedirect.com/science/article/pii/S0169534721001300)

## Acknowledgements

These tutorials are, in part, from [taming-the-beast.org](https://taming-the-beast.org/) and past SISMID workshops, based on work by Louis du Plessis, Veronika Boskova, David Rasmussen, Carsten Magnus, Sebastian Duchene, Timothy G. Vaughan, Denise Kühnert, Julia Pecerska, Marc Suchard, and Philippe Lemey.
