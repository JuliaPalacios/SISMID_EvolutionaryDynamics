---
layout: page
title: "Workshop: Evolutionary Dynamics of Viruses"
---

Instructor(s): Julia A. Palacios and Nicola F. Müller

## General

This module covers the use of phylogenetic and bioinformatic tools to analyze pathogen genetic variation and to gain insight into the processes that shape their diversity. The module focuses on phylogenies and how these relate to population genetic processes in infectious diseases.

In particular, the module will cover Bayesian Evolutionary Analysis by Sampling Trees 2 (BEAST2). Class exercises will focus on estimating epidemic time scales, reconstructing changes in viral population sizes through time, and inferring spatial diffusion of viruses. Evolutionary processes including recombination and selection will also be considered.

## Before the course

Please install the newest version (2.7.7) of [BEAST2](https://www.beast2.org/) on the computer you plan to use. BEAST2 requires Java. If you encounter installation issues, post in the SISMID Slack channel `module-evolution-and-molecular-epi-of-viruses`.

Also install:
- [Tracer 1.7.2](https://github.com/beast-dev/tracer/releases/tag/v1.7.2) to visualize MCMC traces.
- [Figtree 1.4.4](https://github.com/rambaut/figtree/releases/tag/v1.4.4) to view phylogenies. If you get a Java error, try [Figtree 1.4.5_pre](https://github.com/rambaut/figtree/releases/tag/v1.4.5pre).

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
        <td markdown="1">{{ time }}–{% for s in site.data.schedule[0].sessions %}{% if s.start == time %}{{ s.end }}{% endif %}{% endfor %}</td>
        {% for day in site.data.schedule %}
          {% assign match = day.sessions | where: "start", time | first %}
          {% if match %}
            <td markdown="1">
              **{{ match.title }}**  
              *{{ match.lecturer | default: match.lecturers }}*  
              {% if match.slides %}[Slides]({{ match.slides }}){% endif %}
              {% if match.tutorial %} • [Tutorial]({{ match.tutorial }}){% endif %}
            </td>
          {% else %}
            <td></td>
          {% endif %}
        {% endfor %}
      </tr>
    {% endfor %}
  </tbody>
</table>

---

## Some Reading Material (optional)

- Overview of BEAST2 packages: [doi:10.1371/journal.pcbi.1006650](https://doi.org/10.1371/journal.pcbi.1006650)
- Decoding Genomes: [decodinggenomes.org](https://decodinggenomes.org/)
- Review of phylodynamics (coalescent focus): [PLoS Comput Biol 100.2947](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002947)
- Review of phylodynamics in livestock: [ScienceDirect S0169534721001300](https://www.sciencedirect.com/science/article/pii/S0169534721001300)

## Acknowledgements

These tutorials were ,in part, from [taming-the-beast.org](https://taming-the-beast.org/) and past SISMID workshops, based on work by Louis du Plessis, Veronika Boskova, David Rasmussen, Carsten Magnus, Sebastian Duchene, Timothy G. Vaughan, Denise Kühnert, Julia Pecerska, Marc Suchard, and Philippe Lemey.
