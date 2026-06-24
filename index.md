---
layout: default
title: Home
---

<section class="hero">
  <div class="hero__content">
    <p class="eyebrow">Atmospheric scientist · Air quality specialist · Data-driven regulatory analysis</p>
    <h1>Jithin Kanayankottupoyil</h1>
    <p class="hero__subtitle">
      I work at the intersection of emissions inventories, vehicle emission modeling, dispersion and receptor modeling,
      ambient monitoring, and machine learning for air quality analysis.
    </p>
    <div class="hero__actions">
      <a class="button button--primary" href="{{ '/research/' | relative_url }}">Research areas</a>
      <a class="button button--secondary" href="{{ '/files/cv.pdf' | relative_url }}">Download CV</a>
    </div>
  </div>
</section>

<section class="section section--compact">
  <h2>Profile</h2>
  <p>
    I am an air quality specialist with experience in regulatory emissions analysis, mobile-source emissions modeling,
    air pollution monitoring, dispersion modeling, source apportionment, and applied machine learning. My work has supported
    emissions inventories, exposure assessment, regulatory planning, and scientific publications across academic,
    transportation, and public agency settings.
  </p>
</section>

<section class="section">
  <h2>Research and technical focus</h2>
  <div class="card-grid three">
    <article class="card">
      <h3>Emissions inventories</h3>
      <p>Development and QA/QC of mobile-source, point-source, area-source, and chemically speciated emissions datasets.</p>
    </article>
    <article class="card">
      <h3>Modeling and exposure</h3>
      <p>AERMOD, CALPUFF, MOVES, EMFAC, receptor modeling, GIS interpolation, and regulatory-grade impact analysis.</p>
    </article>
    <article class="card">
      <h3>Machine learning</h3>
      <p>Forecasting and source-apportionment applications using meteorology, precursor concentrations, and activity datasets.</p>
    </article>
  </div>
</section>

<section class="section split">
  <div>
    <h2>Selected current work</h2>
    <ul class="clean-list">
      <li><strong>CARB:</strong> EMFAC model development and light-duty fleet/emission factor analysis.</li>
      <li><strong>Vehicle Surveillance Program:</strong> Exhaust and evaporative emission factor development using chassis dynamometer and real-world data.</li>
      <li><strong>Research:</strong> PM<sub>2.5</sub>, VOCs, ozone formation potential, source apportionment, and deep-learning forecasting.</li>
    </ul>
  </div>
  <div class="note-box">
    <h3>Core tools</h3>
    <p>AERMOD · CALPUFF · MOVES · EMFAC · ArcGIS Pro · BenMAP-CE · PMF 5.0 · CMB 8.2 · Python · R · MySQL · Power BI</p>
  </div>
</section>

<section class="section">
  <h2>Selected projects</h2>
  <div class="card-grid two">
    <article class="card card--project">
      <p class="card__meta">2023-present · Dallas-Fort Worth, TX</p>
      <h3>Air quality monitoring</h3>
      <p>Operation, calibration, QA/QC, and analysis of NOx, ozone, and micro-sensor ambient monitoring datasets.</p>
      <a href="{{ '/projects/#air-quality-monitoring' | relative_url }}">View project →</a>
    </article>
    <article class="card card--project">
      <p class="card__meta">2022-present · Machine learning</p>
      <h3>Deep learning for air quality forecasting</h3>
      <p>Ozone and VOC forecasting using precursor, meteorological, and natural gas production datasets.</p>
      <a href="{{ '/projects/#deep-learning-air-quality' | relative_url }}">View project →</a>
    </article>
  </div>
</section>

<section class="section section--compact">
  <h2>Recent news</h2>
  <div class="post-list">
    {% for post in site.posts limit:3 %}
      <article class="post-preview">
        <p class="post-date">{{ post.date | date: "%B %-d, %Y" }}</p>
        <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
        <p>{{ post.excerpt | strip_html | truncate: 180 }}</p>
      </article>
    {% endfor %}
  </div>
</section>
