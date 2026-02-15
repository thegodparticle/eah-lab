---
title: Research Overview
date: "2026-01-01"
lastmod: "2026-02-15"
type: landing

sitemap:
  priority: 0.9
  changefreq: monthly
  
sections:
  # -----------------------------------------------------------------------------
  # 1. HERO
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="research-hero-content">
          <div class="research-hero-label">Research Focus</div>
          <h1 class="research-hero-title">
            Why Do Cochlear Implants Work <em>Brilliantly</em> for Some and <em>Poorly</em> for Others?
          </h1>
          <div class="research-hero-divider"></div>
          <p class="research-hero-desc">
            Two patients. Same device. Same surgery. Vastly different outcomes. One understands speech effortlessly; the other struggles even in quiet rooms. We're working to understand <strong>why</strong> and how to close this gap.
          </p>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["120px", "20px", "100px", "20px"]
      css_class: "research-page research-hero"

  # -----------------------------------------------------------------------------
  # 2. QUESTION 1 - NEURAL HEALTH
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="question-card">
          <div class="question-image" style="background-image: url('https://images.unsplash.com/photo-1559757175-5700dde675bc?q=80&w=2574&auto=format&fit=crop');"></div>
          <div class="question-content">
            <div class="question-number">01</div>
            <p class="question-label accent">Neural Health</p>
            <h2 class="question-heading">How much does the condition of the auditory nerve limit what a cochlear implant user can hear?</h2>
            <p class="question-text">
              Before sound reaches the brain, it must pass through the auditory nerve and in many CI users, these nerve fibers have <strong>degenerated</strong>. We're developing methods to reliably measure neural health at individual electrode sites and determine how this degeneration constrains what patients can perceive.
            </p>
            <ul class="question-approaches accent">
              <li>Objective measures of neural survival patterns</li>
              <li>Relating neural health to pitch perception limits</li>
              <li>Predicting outcomes from physiological markers</li>
            </ul>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["80px", "20px", "24px", "20px"]
      css_class: "research-page research-questions"

  # -----------------------------------------------------------------------------
  # 3. QUESTION 2 - PERSONALIZED STIMULATION
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="question-card reversed">
          <div class="question-image" style="background-image: url('https://images.unsplash.com/photo-1598800489147-44a63d7b5016?q=80&w=2670&auto=format&fit=crop');"></div>
          <div class="question-content">
            <div class="question-number">02</div>
            <p class="question-label coral">Personalized Stimulation</p>
            <h2 class="question-heading">Can we tailor electrical stimulation to each patient's unique auditory system?</h2>
            <p class="question-text">
              Current cochlear implants use essentially the same stimulation approach for everyone but every patient's auditory nerve is different. We're investigating how to <strong>personalize</strong> stimulation strategies based on individual patterns of neural health, potentially improving outcomes without changing the hardware.
            </p>
            <ul class="question-approaches coral">
              <li>Site-specific stimulation parameters</li>
              <li>Matching stimulation to local neural condition</li>
              <li>Translating research findings to clinical fitting</li>
            </ul>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["0", "20px", "24px", "20px"]
      css_class: "research-page research-questions"

  # -----------------------------------------------------------------------------
  # 4. QUESTION 3 - PERCEPTUAL LIMITS
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="question-card">
          <div class="question-image" style="background-image: url('https://images.unsplash.com/photo-1493225457124-a3eb161ffa5f?q=80&w=2670&auto=format&fit=crop');"></div>
          <div class="question-content">
            <div class="question-number">03</div>
            <p class="question-label sage">Perceptual Boundaries</p>
            <h2 class="question-heading">What are the fundamental limits of hearing with electrical stimulation?</h2>
            <p class="question-text">
              Music sounds flat. Voices blur together in noise. These struggles trace back to <strong>spectral resolution</strong>. We use rigorous psychophysical methods to map the precise boundaries of perception in CI users, identifying where the bottlenecks lie and what might be done about them.
            </p>
            <ul class="question-approaches sage">
              <li>Psychophysical measurement of pitch sensitivity</li>
              <li>Spectral and temporal resolution assessment</li>
              <li>Connecting perceptual limits to device and neural factors</li>
            </ul>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["0", "20px", "100px", "20px"]
      css_class: "research-page research-questions"

  # -----------------------------------------------------------------------------
  # 5. CTA
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="research-cta-content">
          <span class="research-cta-label">Our Work</span>
          <h2 class="research-cta-title">Explore Our Publications</h2>

          <a href="../publication/" class="research-cta-btn">
            View Publications →
          </a>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "120px", "20px"]
      css_class: "research-page research-cta"
---