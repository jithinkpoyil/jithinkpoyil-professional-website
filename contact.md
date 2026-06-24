---
layout: default
title: Contact
permalink: /contact/
---

# Contact

For research collaboration, professional inquiries, or technical discussion, use the contact links below.

<div class="contact-card">
  <p><strong>Email:</strong> <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a></p>
  <p><strong>Location:</strong> {{ site.author.location }}</p>
  <p><strong>Current role:</strong> {{ site.author.role }}, {{ site.author.affiliation }}</p>
</div>

## Profiles

<ul class="link-list">
  <li><a href="{{ site.author.github }}">GitHub</a></li>
  <li><a href="{{ site.author.linkedin }}">LinkedIn</a></li>
  <li><a href="{{ site.author.scholar }}">Google Scholar</a></li>
  {% if site.author.orcid and site.author.orcid != "" %}
  <li><a href="{{ site.author.orcid }}">ORCID</a></li>
  {% endif %}
</ul>

## Collaboration areas

I am interested in collaborations related to:

- Emissions inventory development and evaluation.
- Mobile-source emissions modeling and regulatory analysis.
- Air quality monitoring QA/QC and data interpretation.
- Dispersion, receptor, and exposure modeling.
- Machine learning for air quality forecasting and source attribution.

<!-- Optional: Replace this page with a form service such as Formspree only if you are comfortable using a third-party service. -->
