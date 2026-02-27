---
layout: default
title: Home
description: Freelancer | Developer | Digital Solutions — Android apps, web tools, utilities, and software projects.
---

<header class="hero">
  <div class="container">
    <div class="row align-items-center g-4">
      <div class="col-lg-8">
        <h1 class="hero-title mb-3">Fahad Qayyum Awan</h1>
        <p class="hero-subtitle mb-4">Freelancer | Developer | Digital Solutions</p>
        <p class="mb-4" style="max-width: 48rem; opacity:.9;">
          Individual developer building Android apps, web tools, utilities, and software projects.
        </p>

        <div class="d-flex flex-wrap gap-2">
          <a class="btn btn-brand btn-lg" href="#contact">Contact Me</a>
          <a class="btn btn-outline-brand btn-lg" href="#pages">View Pages</a>
        </div>
      </div>

      <div class="col-lg-4 hero-mark">
        <!-- Inline SVG “mosque” mark (no extra files needed) -->
        <svg viewBox="0 0 512 512" role="img" aria-label="Mosque logo">
          <defs>
            <linearGradient id="g" x1="0" y1="0" x2="1" y2="1">
              <stop offset="0" stop-color="rgba(255,255,255,0.95)"/>
              <stop offset="1" stop-color="rgba(255,255,255,0.70)"/>
            </linearGradient>
          </defs>

          <!-- crescent -->
          <path fill="url(#g)" d="M316 72c-36 6-62 38-56 74 5 31 31 54 63 56-18 18-44 27-71 22-40-8-67-47-59-87 8-41 46-68 85-65 14 1 27 5 38 12z"/>

          <!-- dome -->
          <path fill="url(#g)" d="M128 232c18-86 88-144 170-144s152 58 170 144H128z"/>

          <!-- main body -->
          <path fill="url(#g)" d="M112 232h288v176c0 16-13 28-28 28H140c-15 0-28-12-28-28V232z"/>

          <!-- door arch -->
          <path fill="rgba(15,23,42,0.12)" d="M256 264c-44 0-80 36-80 80v92h160v-92c0-44-36-80-80-80z"/>
          <path fill="url(#g)" d="M256 280c-35 0-64 29-64 64v92h128v-92c0-35-29-64-64-64z"/>

          <!-- side minarets -->
          <path fill="url(#g)" d="M76 236h44v200H76V236zm316 0h44v200h-44V236z"/>
          <path fill="rgba(15,23,42,0.12)" d="M76 236c10-42 22-72 44-88v88H76zm316 0c10-42 22-72 44-88v88h-44z"/>

          <!-- base -->
          <path fill="rgba(255,255,255,0.72)" d="M72 436h368v24H72v-24z"/>
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
        <div class="col-md-6">
          <div class="soft-card p-4 h-100">
            <h3 class="h5 fw-bold mb-2">Privacy Policy</h3>
            <p class="muted mb-3">Read how information is handled across apps and services.</p>
            <a class="btn btn-brand" href="{{ '/privacy-policy' | relative_url }}">Open</a>
          </div>
        </div>

        <div class="col-md-6">
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
