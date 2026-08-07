---
permalink: /
title: "Víthor Rosa Franco"
author_profile: true
hide_title: true
redirect_from:
  - /about/
  - /about.html
---

<div class="home-intro">
  <p class="eyebrow">VÍTHOR ROSA FRANCO</p>
  <p class="home-kicker">PSYCHOMETRICS · MATHEMATICAL PSYCHOLOGY · BAYESIAN METHODS</p>
  <h1 class="home-tagline">I develop quantitative methods for psychological measurement and formal models of behavior.</h1>
  <p class="home-lead">I am an Assistant Professor of Psychological Assessment in the Postgraduate Program in Psychology at Universidade São Francisco (USF), Brazil. My work sits at the intersection of psychometrics, measurement theory, mathematical psychology, Bayesian inference, and computational modeling.</p>
  <div class="button-row">
    <a class="btn btn--primary" href="/research/">Research</a>
    <a class="btn btn--light-outline" href="/publications/">Publications</a>
    <a class="btn btn--light-outline" href="/software/">Software</a>
  </div>
</div>

## Research

My research asks a simple question with difficult consequences: **what assumptions are we making when we turn psychological observations into measurements?** I work on methods that make those assumptions more explicit, testable, and useful. Current interests include psychometric theory, item response models, Bayesian hierarchical modeling, nonparametric methods, causal and network models, and computational approaches to psychological assessment.

<div class="card-grid">
  <div class="info-card">
    <h3>Measurement & psychometrics</h3>
    <p>Fundamental measurement, item response theory, nonparametric psychometrics, psychometric assumptions, and alternative models of psychological measurement.</p>
  </div>
  <div class="info-card">
    <h3>Bayesian & computational methods</h3>
    <p>Bayesian hierarchical models, Monte Carlo methods, graphical models, computational statistics, and flexible estimation strategies for behavioral data.</p>
  </div>
  <div class="info-card">
    <h3>Mathematical psychology</h3>
    <p>Formal theories of psychological processes, representational measurement, decision models, and the use of mathematical structure to sharpen psychological explanation.</p>
  </div>
  <div class="info-card">
    <h3>AI & psychological assessment</h3>
    <p>Large language models, natural-language data, algorithmic methods, and the opportunities and risks of using AI in psychological measurement and assessment.</p>
  </div>
</div>

<p class="section-link"><a href="/research/">More about my research →</a></p>

## Selected publications

{% assign featured_pubs = site.data.publications | where: "featured", true %}
<div class="publication-list compact">
{% for pub in featured_pubs limit: 6 %}
  <div class="publication-item">
    <div class="publication-year">{{ pub.year }}</div>
    <div class="publication-body">
      <strong>{% if pub.url and pub.url != '' %}<a href="{{ pub.url }}">{{ pub.title }}</a>{% else %}{{ pub.title }}{% endif %}</strong><br>
      <span>{{ pub.authors }}</span><br>
      <em>{{ pub.venue }}</em>
    </div>
  </div>
{% endfor %}
</div>

<p class="section-link"><a href="/publications/">View the complete publication list →</a></p>

## Open-source software

I develop R and C++ tools for Bayesian computation, item response modeling, graphical models, and numerical optimization. The projects are research-oriented and are designed to make methodological ideas directly usable in empirical work.

<div class="software-strip">
  <a href="https://github.com/vthorrf/YABS"><strong>YABS</strong><span>Bayesian computation</span></a>
  <a href="https://github.com/vthorrf/birm"><strong>birm</strong><span>Bayesian item response models</span></a>
  <a href="https://github.com/vthorrf/gbggm"><strong>gbggm</strong><span>Bayesian graphical models</span></a>
</div>

<p class="section-link"><a href="/software/">Explore software and code →</a></p>
