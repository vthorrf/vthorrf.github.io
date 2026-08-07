---
permalink: /software/
title: "Software"
author_profile: true
---

<p class="page-lede">I build research software mainly in R and C++ to make Bayesian, psychometric, and optimization methods easier to test and reuse. Most projects are experimental research software; repository documentation describes the current implementation status.</p>

<div class="software-grid">
  <div class="software-card featured-software">
    <div class="software-card-top"><span class="software-label">Bayesian computation</span><span>R / C++</span></div>
    <h2>YABS</h2>
    <p><strong>Yet Another Bayesian Sampler</strong> is a flexible Bayesian modeling toolkit with C++ implementations of multiple MCMC algorithms, Laplace approximation, importance-sampling support, and general-purpose variational Bayes algorithms.</p>
    <p><a class="btn btn--primary" href="https://github.com/vthorrf/YABS">GitHub repository</a></p>
  </div>

  <div class="software-card">
    <div class="software-card-top"><span class="software-label">Psychometrics</span><span>R</span></div>
    <h2>birm</h2>
    <p>A plug-and-play framework for <strong>Bayesian Item Response Models</strong>, including Rasch-family models, logistic IRT models, unfolding models, Bayesian optimal scoring, and several estimation strategies.</p>
    <p><a href="https://github.com/vthorrf/birm">View on GitHub →</a></p>
  </div>

  <div class="software-card">
    <div class="software-card-top"><span class="software-label">Latent variables</span><span>R</span></div>
    <h2>bsem</h2>
    <p>An earlier Bayesian psychometric modeling package with item-response models, including logistic and partial-credit families, and several Bayesian estimation approaches.</p>
    <p><a href="https://github.com/vthorrf/bsem">View on GitHub →</a></p>
  </div>

  <div class="software-card">
    <div class="software-card-top"><span class="software-label">Networks</span><span>R / C++</span></div>
    <h2>gbggm</h2>
    <p>Implementations of <strong>Generalized Bayesian Gaussian Graphical Models</strong>, including multiple prior families for regularization and heavy-tailed behavior.</p>
    <p><a href="https://github.com/vthorrf/gbggm">View on GitHub →</a></p>
  </div>

  <div class="software-card">
    <div class="software-card-top"><span class="software-label">Optimization</span><span>R</span></div>
    <h2>optimg</h2>
    <p>A general-purpose gradient-based optimization package with implementations including steepest two-group gradient descent and Adam.</p>
    <p><a href="https://github.com/vthorrf/optimg">View on GitHub →</a></p>
  </div>

  <div class="software-card">
    <div class="software-card-top"><span class="software-label">Dependence</span><span>R</span></div>
    <h2>wijayatunga</h2>
    <p>An R implementation of the Wijayatunga dependence coefficient for nonlinear associations.</p>
    <p><a href="https://github.com/vthorrf/wijayatunga">View on GitHub →</a></p>
  </div>
</div>

## Installation and reproducibility

For development versions of my R packages, the repository README is the authoritative source for installation instructions. In general, GitHub-hosted R packages can be installed with `remotes::install_github("vthorrf/package")`.

<p class="section-link"><a href="https://github.com/vthorrf?tab=repositories">See all repositories on GitHub →</a></p>
