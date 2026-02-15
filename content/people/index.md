---
title: Meet the Team
date: "2026-01-01"
lastmod: "2026-02-15"
type: landing

sitemap:
  priority: 0.8
  changefreq: monthly

sections:
  # -----------------------------------------------------------------------------
  # 1. HERO
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="team-hero-content">
          <div class="team-hero-label">Our People</div>
          <h1 class="team-hero-title">
            The Minds Behind<br><em>The Science</em>
          </h1>
          <div class="team-hero-divider"></div>
          <p class="team-hero-desc">
            A growing team of researchers dedicated to understanding variability in cochlear implant outcomes.
          </p>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["140px", "20px", "120px", "20px"]
      css_class: "team-page team-hero"

  # -----------------------------------------------------------------------------
  # 2. FACULTY INTRO
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="section-intro">
          <span class="section-number">01</span>
          <h2 class="section-title">Principal Investigator</h2>
          <div class="section-divider"></div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "0", "20px"]
      css_class: "team-page team-section"

  # -----------------------------------------------------------------------------
  # 3. FACULTY PEOPLE BLOCK
  # -----------------------------------------------------------------------------
  - block: people
    content:
      title: ""
      user_groups:
        - Faculty
      sort_ascending: true
      sort_by: Params.last_name
    design:
      show_interests: true
      show_role: true
      show_social: true
      columns: "2"
      spacing:
        padding: ["20px", "0", "80px", "0"]
      background:
        color: "#ffffff"
      css_class: "team-page"

  # -----------------------------------------------------------------------------
  # 4. TEAM INTRO
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="section-intro">
          <span class="section-number">02</span>
          <h2 class="section-title">Lab Members</h2>
          <div class="section-divider"></div>
          <p class="section-desc">
            Graduate students and research assistants advancing our mission.
          </p>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "0", "20px"]
      css_class: "team-page team-section-alt"

  # -----------------------------------------------------------------------------
  # 5. TEAM PEOPLE BLOCK
  # -----------------------------------------------------------------------------
  - block: people
    content:
      title: ""
      user_groups:
        - Researchers
        - Grad Students
        - Administration
        - Visitors
      sort_ascending: true
      sort_by: Params.last_name
    design:
      show_interests: false
      show_role: true
      show_social: true
      columns: "2"
      spacing:
        padding: ["20px", "0", "80px", "0"]
      background:
        color: "#faf8f5"
      css_class: "team-page"

  # -----------------------------------------------------------------------------
  # 6. ALUMNI INTRO
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="section-intro">
          <span class="section-number">03</span>
          <h2 class="section-title">Alumni</h2>
          <div class="section-divider"></div>
          <p class="section-desc">
            Former team members continuing to make an impact in hearing science.
          </p>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "0", "20px"]
      css_class: "team-page team-section"

  # -----------------------------------------------------------------------------
  # 7. ALUMNI PEOPLE BLOCK
  # -----------------------------------------------------------------------------
  - block: people
    content:
      title: ""
      user_groups:
        - Alumni
      sort_ascending: false
      sort_by: Params.last_name
    design:
      show_interests: false
      show_role: true
      show_social: false
      columns: "2"
      spacing:
        padding: ["20px", "0", "80px", "0"]
      background:
        color: "#ffffff"
      css_class: "team-page"

  # -----------------------------------------------------------------------------
  # 8. JOIN CTA - SIMPLE LINK TO JOIN PAGE
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="team-cta-content">
          <h2 class="team-cta-title">
            Interested in <em>joining us?</em>
          </h2>
          <p class="team-cta-desc">
            We're always looking for motivated students and research participants to advance hearing science.
          </p>
          <a href="../contact/" class="team-cta-btn">
            View Opportunities →
          </a>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "100px", "20px"]
      css_class: "team-page team-cta"
---