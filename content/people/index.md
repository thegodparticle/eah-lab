---
title: Meet the Team
date: "2026-01-01"
type: landing
sections:
  # -----------------------------------------------------------------------------
  # CUSTOM STYLES
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500&family=Source+Sans+3:wght@300;400;500;600&display=swap');
        
        :root {
          --eahl-navy: #0a1628;
          --eahl-navy-light: #162544;
          --eahl-cream: #faf8f5;
          --eahl-accent: #4a90a4;
          --eahl-coral: #e07a5f;
          --eahl-sage: #6b8f71;
          --eahl-text: #374151;
          --eahl-text-light: #6b7280;
        }
        
        .team-page h1, .team-page h2, .team-page h3 {
          font-family: 'Playfair Display', Georgia, serif !important;
        }
        
        .team-page p, .team-page span, .team-page a, .team-page li {
          font-family: 'Source Sans 3', -apple-system, sans-serif !important;
        }
        
        /* ===== HERO ===== */
        .team-hero {
          background: var(--eahl-navy) !important;
          position: relative;
          overflow: hidden;
        }
        
        .team-hero::before {
          content: '';
          position: absolute;
          inset: 0;
          background: 
            radial-gradient(ellipse at 30% 20%, rgba(74, 144, 164, 0.15) 0%, transparent 50%),
            radial-gradient(ellipse at 70% 80%, rgba(224, 122, 95, 0.1) 0%, transparent 40%);
          pointer-events: none;
        }
        
        .team-hero-content {
          max-width: 800px;
          margin: 0 auto;
          text-align: center;
          padding: 0 24px;
          position: relative;
          z-index: 2;
        }
        
        .team-hero-label {
          display: inline-flex;
          align-items: center;
          gap: 12px;
          font-size: 0.75rem;
          font-weight: 600;
          letter-spacing: 0.2em;
          text-transform: uppercase;
          color: rgba(255, 255, 255, 0.5);
          margin-bottom: 24px;
        }
        
        .team-hero-label::before,
        .team-hero-label::after {
          content: '';
          width: 32px;
          height: 1px;
          background: rgba(255, 255, 255, 0.3);
        }
        
        .team-hero-title {
          font-size: clamp(2.5rem, 5.5vw, 4rem) !important;
          font-weight: 500 !important;
          color: #ffffff !important;
          line-height: 1.1 !important;
          margin-bottom: 28px !important;
          letter-spacing: -0.02em;
        }
        
        .team-hero-title em {
          font-style: italic;
          color: var(--eahl-accent);
        }
        
        .team-hero-divider {
          width: 64px;
          height: 3px;
          background: linear-gradient(90deg, var(--eahl-accent), var(--eahl-coral));
          margin: 0 auto 32px auto;
          border-radius: 2px;
        }
        
        .team-hero-desc {
          font-size: 1.2rem;
          color: rgba(255, 255, 255, 0.75);
          line-height: 1.75;
          max-width: 620px;
          margin: 0 auto;
        }
        
        /* ===== SECTION STYLING ===== */
        .team-section {
          background: #ffffff !important;
        }
        
        .team-section-alt {
          background: var(--eahl-cream) !important;
        }
        
        .section-intro {
          max-width: 900px;
          margin: 0 auto 60px auto;
          text-align: center;
          padding: 0 24px;
        }
        
        .section-number {
          font-family: 'Playfair Display', serif !important;
          font-size: 0.85rem;
          color: var(--eahl-text-light);
          margin-bottom: 12px;
          display: block;
        }
        
        .section-title {
          font-size: clamp(2rem, 4vw, 2.75rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 16px !important;
          letter-spacing: -0.02em;
        }
        
        .section-divider {
          width: 60px;
          height: 3px;
          background: var(--eahl-coral);
          margin: 0 auto;
          border-radius: 2px;
        }
        
        .section-desc {
          font-size: 1.1rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          max-width: 600px;
          margin: 20px auto 0 auto;
        }
        
        /* ===== OVERRIDE HUGO PEOPLE BLOCK STYLES ===== */
        .team-page .hb-people .card {
          background: #ffffff !important;
          border: 1px solid #e5e7eb !important;
          border-radius: 16px !important;
          overflow: hidden !important;
          transition: all 0.3s ease !important;
          box-shadow: none !important;
        }
        
        .team-page .hb-people .card:hover {
          transform: translateY(-6px) !important;
          box-shadow: 0 20px 40px rgba(10, 22, 40, 0.08) !important;
          border-color: transparent !important;
        }
        
        .team-page .hb-people .card-body {
          padding: 24px !important;
        }
        
        .team-page .hb-people .card-title {
          font-family: 'Playfair Display', Georgia, serif !important;
          font-size: 1.25rem !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 4px !important;
        }
        
        .team-page .hb-people .card-subtitle,
        .team-page .hb-people .text-muted {
          font-family: 'Source Sans 3', sans-serif !important;
          font-size: 0.95rem !important;
          color: var(--eahl-text-light) !important;
        }
        
        .team-page .hb-people .avatar {
          border-radius: 12px !important;
        }
        
        .team-page .hb-people a {
          color: var(--eahl-accent) !important;
          transition: color 0.2s ease !important;
        }
        
        .team-page .hb-people a:hover {
          color: var(--eahl-coral) !important;
        }
        
        .team-page .hb-people .social-icons a {
          color: var(--eahl-text-light) !important;
        }
        
        .team-page .hb-people .social-icons a:hover {
          color: var(--eahl-accent) !important;
        }
        
        /* Section titles in people blocks */
        .team-page section h2 {
          font-family: 'Playfair Display', Georgia, serif !important;
          font-size: clamp(1.8rem, 3.5vw, 2.25rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          letter-spacing: -0.02em !important;
          text-align: center !important;
          margin-bottom: 48px !important;
        }
        
        /* ===== JOIN CTA - EXPANDED ===== */
        .team-join-section {
          background: var(--eahl-cream) !important;
        }
        
        .team-join-container {
          max-width: 1100px;
          margin: 0 auto;
          padding: 0 24px;
        }
        
        .team-join-header {
          text-align: center;
          margin-bottom: 64px;
        }
        
        .team-join-badge {
          display: inline-block;
          font-size: 0.75rem;
          font-weight: 600;
          letter-spacing: 0.15em;
          text-transform: uppercase;
          color: #ffffff;
          background: var(--eahl-coral);
          padding: 8px 20px;
          border-radius: 100px;
          margin-bottom: 24px;
        }
        
        .team-join-title {
          font-size: clamp(2rem, 4vw, 2.75rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 16px !important;
          letter-spacing: -0.02em;
        }
        
        .team-join-subtitle {
          font-size: 1.15rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          max-width: 650px;
          margin: 0 auto;
        }
        
        .team-join-grid {
          display: grid;
          grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
          gap: 32px;
          margin-bottom: 64px;
        }
        
        .team-join-card {
          background: #ffffff;
          border: 1px solid #e5e7eb;
          border-radius: 20px;
          padding: 40px 32px;
          position: relative;
          transition: all 0.3s ease;
        }
        
        .team-join-card::before {
          content: '';
          position: absolute;
          top: 0;
          left: 0;
          right: 0;
          height: 4px;
          background: var(--card-accent);
          border-radius: 20px 20px 0 0;
        }
        
        .team-join-card:hover {
          transform: translateY(-6px);
          box-shadow: 0 24px 48px rgba(10, 22, 40, 0.1);
          border-color: transparent;
        }
        
        .team-join-card-icon {
          width: 56px;
          height: 56px;
          border-radius: 14px;
          display: flex;
          align-items: center;
          justify-content: center;
          font-size: 1.5rem;
          margin-bottom: 24px;
          background: var(--icon-bg);
          color: var(--icon-color);
        }
        
        .team-join-card-title {
          font-size: 1.35rem !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 12px !important;
        }
        
        .team-join-card-desc {
          font-size: 1rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          margin-bottom: 20px;
        }
        
        .team-join-card-list {
          list-style: none;
          padding: 0;
          margin: 0 0 24px 0;
        }
        
        .team-join-card-list li {
          position: relative;
          padding-left: 20px;
          margin-bottom: 10px;
          font-size: 0.95rem;
          color: var(--eahl-text);
          line-height: 1.5;
        }
        
        .team-join-card-list li::before {
          content: '';
          position: absolute;
          left: 0;
          top: 8px;
          width: 6px;
          height: 6px;
          border-radius: 50%;
          background: var(--card-accent);
        }
        
        .team-join-card-status {
          display: inline-block;
          font-size: 0.8rem;
          font-weight: 600;
          text-transform: uppercase;
          letter-spacing: 0.1em;
          padding: 6px 14px;
          border-radius: 6px;
        }
        
        .status-recruiting {
          background: rgba(107, 143, 113, 0.15);
          color: var(--eahl-sage);
        }
        
        .status-limited {
          background: rgba(224, 122, 95, 0.15);
          color: var(--eahl-coral);
        }
        
        /* Join bottom CTA */
        .team-join-bottom {
          background: var(--eahl-navy);
          border-radius: 24px;
          padding: 56px 48px;
          text-align: center;
          position: relative;
          overflow: hidden;
        }
        
        .team-join-bottom::before {
          content: '';
          position: absolute;
          inset: 0;
          background: radial-gradient(ellipse at 50% 0%, rgba(74, 144, 164, 0.2) 0%, transparent 60%);
          pointer-events: none;
        }
        
        .team-join-bottom-content {
          position: relative;
          z-index: 2;
        }
        
        .team-join-bottom-title {
          font-size: clamp(1.5rem, 3vw, 2rem) !important;
          font-weight: 500 !important;
          color: #ffffff !important;
          margin-bottom: 16px !important;
        }
        
        .team-join-bottom-title em {
          font-style: italic;
          color: var(--eahl-accent);
        }
        
        .team-join-bottom-desc {
          font-size: 1.05rem;
          color: rgba(255, 255, 255, 0.75);
          line-height: 1.7;
          max-width: 500px;
          margin: 0 auto 32px auto;
        }
        
        .team-join-btn {
          display: inline-flex;
          align-items: center;
          gap: 10px;
          font-size: 1.05rem;
          font-weight: 600;
          color: var(--eahl-navy) !important;
          background: #ffffff;
          padding: 18px 40px;
          border-radius: 100px;
          text-decoration: none !important;
          transition: all 0.3s ease;
        }
        
        .team-join-btn:hover {
          background: var(--eahl-accent);
          color: #ffffff !important;
          transform: translateY(-3px);
          box-shadow: 0 16px 32px rgba(74, 144, 164, 0.3);
        }
        
        /* ===== RESPONSIVE ===== */
        @media (max-width: 768px) {
          .team-hero-content { padding: 0 20px; }
          .section-intro { margin-bottom: 40px; }
          .team-join-card { padding: 32px 24px; }
          .team-join-bottom { padding: 40px 24px; border-radius: 16px; }
          .team-join-grid { grid-template-columns: 1fr; }
        }
        </style>
    design:
      columns: "1"
      spacing:
        padding: ["0", "0", "0", "0"]

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