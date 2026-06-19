---
layout: default
title: Home
description: Freelancer | Developer | Digital Solutions — Android apps, web tools, utilities, and software projects.
---

<header class="hero">
  <div class="container">
    <div class="row align-items-center">

      <!-- LEFT SIDE -->
      <div class="col-lg-7 text-center text-lg-start">
        <h1 class="hero-title mb-3">Fahad Qayyum Awan</h1>
        <p class="hero-subtitle mb-4">
          Freelancer | Developer | Digital Solutions
        </p>
        <p class="mb-4" style="max-width: 500px;">
          Individual developer building Android apps, web tools, utilities, and software projects.
        </p>

        <div class="d-flex flex-wrap gap-3 justify-content-center justify-content-lg-start">
          <a class="btn btn-brand btn-lg" href="#contact">Contact Me</a>
          <a class="btn btn-outline-brand btn-lg" href="#pages">View Pages</a>
        </div>
      </div>

      <!-- RIGHT SIDE -->
      <div class="col-lg-5 hero-mark">
        <!-- Clean arch SVG -->
        <svg viewBox="0 0 300 400">
          <path 
            d="M150 20 Q260 120 260 240 L260 360 L40 360 L40 240 Q40 120 150 20 Z"
            fill="none"
            stroke="rgba(255,255,255,0.7)"
            stroke-width="6"
          />
        </svg>
      </div>

    </div>
  </div>
</header>

<main>
  <section id="pages" class="section">
    <div class="container">
      <div class="d-flex align-items-end justify-content-between flex-wrap gap-2 mb-3">
        <div>
          <h2 class="section-title mb-1">Pages</h2>
          <p class="muted mb-0">Policies and support information.</p>
        </div>
      </div>

      <div class="row g-3">
        <div class="col-md-4">
          <div class="soft-card p-4 h-100">
            <h3 class="h5 fw-bold mb-2">Privacy Policy</h3>
            <p class="muted mb-3">Read how information is handled across apps and services.</p>
            <a class="btn btn-brand" href="{{ '/privacy-policy' | relative_url }}">Open</a>
          </div>
        </div>

        <div class="col-md-4">
          <div class="soft-card p-4 h-100">
            <h3 class="h5 fw-bold mb-2">Terms of Service</h3>
            <p class="muted mb-3">Rules and conditions for using my apps and online features.</p>
            <a class="btn btn-brand" href="{{ '/terms-of-service' | relative_url }}">Open</a>
          </div>
        </div>

        <div class="col-md-4">
          <div class="soft-card p-4 h-100">
            <h3 class="h5 fw-bold mb-2">Support</h3>
            <p class="muted mb-3">Get help, report issues, or request features.</p>
            <a class="btn btn-brand" href="{{ '/support' | relative_url }}">Open</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="section pt-0">
    <div class="container">
      <div class="soft-card p-4 p-md-5">
        <div class="row align-items-center g-4">
          <div class="col-lg-8">
            <h2 class="section-title mb-2">Contact</h2>
            <p class="muted mb-0">
              Email:
              <a class="fw-semibold text-decoration-none" href="mailto:malik.fahad1990@gmail.com">
                malik.fahad1990@gmail.com
              </a>
            </p>
          </div>
          <div class="col-lg-4 text-lg-end">
            <a class="btn btn-brand btn-lg w-100 w-lg-auto" href="mailto:malik.fahad1990@gmail.com">
              Send Email
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</main>
