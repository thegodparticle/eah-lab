---
title: Home
type: landing
date: "2026-01-01"
lastmod: "2026-02-15"

sitemap:
  priority: 1.0
  changefreq: weekly

design:
  css_class: "eahl-landing"

sections:
  # -----------------------------------------------------------------------------
  # 1. HERO
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="eahl-hero-content">
          <div class="eahl-hero-label">
            Research Laboratory
          </div>
          <h1 class="eahl-hero-title">
            Electric & Acoustic
            <span class="eahl-hero-title-accent">Hearing Lab</span>
          </h1>
          <p class="eahl-hero-subtitle">
            Understanding why cochlear implant outcomes vary so dramatically and developing personalized approaches to close the gap.
          </p>
          <p class="eahl-hero-affiliation">University of South Alabama</p>
          <div class="eahl-waveform">
            <div class="eahl-wave-bar"></div>
            <div class="eahl-wave-bar"></div>
            <div class="eahl-wave-bar"></div>
            <div class="eahl-wave-bar"></div>
            <div class="eahl-wave-bar"></div>
            <div class="eahl-wave-bar"></div>
            <div class="eahl-wave-bar"></div>
            <div class="eahl-wave-bar"></div>
            <div class="eahl-wave-bar"></div>
            <div class="eahl-wave-bar"></div>
            <div class="eahl-wave-bar"></div>
            <div class="eahl-wave-bar"></div>
            <div class="eahl-wave-bar"></div>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "0", "100px", "0"]
      css_class: "eahl-hero-section"

  # -----------------------------------------------------------------------------
  # 2. RESEARCH PILLARS
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="eahl-section-header">
          <h2 class="eahl-section-title">What We Study</h2>
          <div class="eahl-section-divider"></div>
        </div>
        <div class="eahl-pillars-grid">
          <div class="eahl-pillar-card" style="--card-color: #4a90a4; --icon-bg: rgba(74, 144, 164, 0.12); --icon-color: #4a90a4;">
            <div class="eahl-pillar-icon">
              <i class="fas fa-heartbeat"></i>
            </div>
            <h3 class="eahl-pillar-title">Neural Health</h3>
            <p class="eahl-pillar-desc">
              Measuring auditory nerve survival patterns and understanding how neural degeneration limits what cochlear implant users can perceive.
            </p>
          </div>
          <div class="eahl-pillar-card" style="--card-color: #e07a5f; --icon-bg: rgba(224, 122, 95, 0.12); --icon-color: #e07a5f;">
            <div class="eahl-pillar-icon">
              <i class="fas fa-sliders-h"></i>
            </div>
            <h3 class="eahl-pillar-title">Stimulation Optimization</h3>
            <p class="eahl-pillar-desc">
              Developing personalized electrical stimulation strategies tailored to each patient's unique auditory system.
            </p>
          </div>
          <div class="eahl-pillar-card" style="--card-color: #6b8f71; --icon-bg: rgba(107, 143, 113, 0.12); --icon-color: #6b8f71;">
            <div class="eahl-pillar-icon">
              <i class="fas fa-music"></i>
            </div>
            <h3 class="eahl-pillar-title">Pitch & Spectral Perception</h3>
            <p class="eahl-pillar-desc">
              Mapping the limits of pitch sensitivity and spectral resolution to understand why music and speech in noise remain challenging.
            </p>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "100px", "20px"]
      css_class: "eahl-research-section"

  # -----------------------------------------------------------------------------
  # 3. MISSION
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="eahl-mission-content">
          <h2 class="eahl-mission-quote">
            Same device. Same surgery.<br><em>Vastly different outcomes.</em>
          </h2>
          <p class="eahl-mission-body">
            We're working to understand the biological and technical factors that drive variability in cochlear implant performance and translating that knowledge into <strong>better clinical outcomes</strong>.
          </p>
          <div class="eahl-values-row">
            <span class="eahl-value-tag">Psychophysics</span>
            <span class="eahl-value-tag">Electrophysiology</span>
            <span class="eahl-value-tag">Translational Research</span>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["120px", "20px", "120px", "20px"]
      css_class: "eahl-mission-section"

  # -----------------------------------------------------------------------------
  # 4. CTA - COMMENTED OUT (available on Team page instead)
  # -----------------------------------------------------------------------------
  # - block: markdown
  #   content:
  #     text: |
  #       <div class="eahl-cta-card">
  #         <h2 class="eahl-cta-title">Join Our Research Team</h2>
  #         <p class="eahl-cta-desc">
  #           We're recruiting motivated researchers and cochlear implant users to advance hearing science.
  #         </p>
  #         <div class="eahl-cta-roles">
  #           <span class="eahl-role eahl-role-phd">Graduate Students</span>
  #           <span class="eahl-role eahl-role-postdoc">Research Assistants</span>
  #           <span class="eahl-role eahl-role-participant">CI Participants</span>
  #         </div>
  #         <a href="./contact/" class="eahl-cta-button">
  #           Get Involved →
  #         </a>
  #       </div>
  #   design:
  #     columns: "1"
  #     spacing:
  #       padding: ["80px", "20px", "120px", "20px"]
  #     css_class: "eahl-cta-section"
---