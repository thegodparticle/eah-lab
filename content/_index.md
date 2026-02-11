---
title: Home
type: landing
date: "2026-01-01"

design:
  css_class: "eahl-landing"

sections:
  # -----------------------------------------------------------------------------
  # CUSTOM STYLES (as a blank block at top)
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <style>
        /* ===== GLOBAL TYPOGRAPHY ===== */
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
        
        .eahl-landing h1, .eahl-landing h2, .eahl-landing h3 {
          font-family: 'Playfair Display', Georgia, serif !important;
        }
        
        .eahl-landing p, .eahl-landing span, .eahl-landing a {
          font-family: 'Source Sans 3', -apple-system, sans-serif !important;
        }
        
        /* ===== HERO SECTION ===== */
        .eahl-hero-section {
          background: linear-gradient(135deg, var(--eahl-navy) 0%, var(--eahl-navy-light) 100%) !important;
          position: relative;
          overflow: hidden;
        }
        
        .eahl-hero-section::before {
          content: '';
          position: absolute;
          top: 0;
          right: 0;
          width: 50%;
          height: 100%;
          background: radial-gradient(ellipse at 70% 50%, rgba(74, 144, 164, 0.15) 0%, transparent 60%);
          pointer-events: none;
        }
        
        .eahl-hero-content {
          position: relative;
          z-index: 2;
          max-width: 900px;
          margin: 0 auto;
          text-align: center;
          padding: 40px 20px;
        }
        
        .eahl-hero-label {
          display: inline-flex;
          align-items: center;
          gap: 12px;
          font-size: 0.75rem;
          font-weight: 600;
          letter-spacing: 0.2em;
          text-transform: uppercase;
          color: var(--eahl-accent);
          margin-bottom: 32px;
        }
        
        .eahl-hero-label::before,
        .eahl-hero-label::after {
          content: '';
          width: 40px;
          height: 1px;
          background: var(--eahl-accent);
          opacity: 0.5;
        }
        
        .eahl-hero-title {
          font-size: clamp(2.5rem, 6vw, 4rem) !important;
          font-weight: 500 !important;
          color: #ffffff !important;
          line-height: 1.15 !important;
          margin-bottom: 12px !important;
          letter-spacing: -0.02em;
        }
        
        .eahl-hero-title-accent {
          display: block;
          font-style: italic;
          color: var(--eahl-accent) !important;
        }
        
        .eahl-hero-subtitle {
          font-size: 1.25rem;
          color: rgba(255, 255, 255, 0.85);
          line-height: 1.7;
          max-width: 600px;
          margin: 0 auto 24px auto;
          font-weight: 400;
        }
        
        .eahl-hero-affiliation {
          font-size: 0.95rem;
          color: rgba(255, 255, 255, 0.6);
          display: flex;
          align-items: center;
          justify-content: center;
          gap: 8px;
        }
        
        .eahl-hero-affiliation::before {
          content: '◆';
          font-size: 0.4rem;
          color: var(--eahl-coral);
        }
        
        /* ===== WAVEFORM ANIMATION ===== */
        .eahl-waveform {
          display: flex;
          align-items: center;
          justify-content: center;
          gap: 4px;
          margin: 48px auto 0 auto;
          height: 60px;
        }
        
        .eahl-wave-bar {
          width: 3px;
          height: 10px;
          background: linear-gradient(180deg, var(--eahl-accent), rgba(74, 144, 164, 0.4));
          border-radius: 3px;
          animation: eahl-wave 1.2s ease-in-out infinite;
        }
        
        .eahl-wave-bar:nth-child(1) { animation-delay: 0s; }
        .eahl-wave-bar:nth-child(2) { animation-delay: 0.1s; }
        .eahl-wave-bar:nth-child(3) { animation-delay: 0.2s; }
        .eahl-wave-bar:nth-child(4) { animation-delay: 0.3s; }
        .eahl-wave-bar:nth-child(5) { animation-delay: 0.4s; }
        .eahl-wave-bar:nth-child(6) { animation-delay: 0.5s; }
        .eahl-wave-bar:nth-child(7) { animation-delay: 0.6s; }
        .eahl-wave-bar:nth-child(8) { animation-delay: 0.5s; }
        .eahl-wave-bar:nth-child(9) { animation-delay: 0.4s; }
        .eahl-wave-bar:nth-child(10) { animation-delay: 0.3s; }
        .eahl-wave-bar:nth-child(11) { animation-delay: 0.2s; }
        .eahl-wave-bar:nth-child(12) { animation-delay: 0.1s; }
        .eahl-wave-bar:nth-child(13) { animation-delay: 0s; }
        
        @keyframes eahl-wave {
          0%, 100% { height: 10px; }
          50% { height: 40px; }
        }
        
        /* ===== RESEARCH SECTION ===== */
        .eahl-research-section {
          background: var(--eahl-cream) !important;
        }
        
        .eahl-section-header {
          text-align: center;
          margin-bottom: 64px;
        }
        
        .eahl-section-number {
          font-family: 'Playfair Display', serif;
          font-size: 0.85rem;
          color: var(--eahl-text-light);
          margin-bottom: 12px;
          display: block;
        }
        
        .eahl-section-title {
          font-size: clamp(2rem, 4vw, 2.75rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 16px !important;
          letter-spacing: -0.02em;
        }
        
        .eahl-section-divider {
          width: 60px;
          height: 3px;
          background: var(--eahl-coral);
          margin: 0 auto;
          border-radius: 2px;
        }
        
        .eahl-pillars-grid {
          display: grid;
          grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
          gap: 32px;
          max-width: 1100px;
          margin: 0 auto;
        }
        
        .eahl-pillar-card {
          background: #ffffff;
          border: 1px solid #e5e7eb;
          border-radius: 16px;
          padding: 40px 32px;
          transition: all 0.3s ease;
          position: relative;
          overflow: hidden;
        }
        
        .eahl-pillar-card::before {
          content: '';
          position: absolute;
          top: 0;
          left: 0;
          right: 0;
          height: 3px;
          background: var(--card-color);
          transform: scaleX(0);
          transform-origin: left;
          transition: transform 0.3s ease;
        }
        
        .eahl-pillar-card:hover {
          transform: translateY(-6px);
          box-shadow: 0 20px 40px rgba(10, 22, 40, 0.08);
          border-color: transparent;
        }
        
        .eahl-pillar-card:hover::before {
          transform: scaleX(1);
        }
        
        .eahl-pillar-icon {
          width: 52px;
          height: 52px;
          border-radius: 12px;
          display: flex;
          align-items: center;
          justify-content: center;
          margin-bottom: 24px;
          font-size: 1.4rem;
          background: var(--icon-bg);
          color: var(--icon-color);
        }
        
        .eahl-pillar-title {
          font-size: 1.35rem !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 12px !important;
        }
        
        .eahl-pillar-desc {
          font-size: 1rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          margin: 0;
        }
        
        /* ===== MISSION SECTION ===== */
        .eahl-mission-section {
          background: var(--eahl-navy) !important;
          position: relative;
        }
        
        .eahl-mission-content {
          max-width: 850px;
          margin: 0 auto;
          text-align: center;
        }
        
        .eahl-mission-quote {
          font-size: clamp(1.5rem, 3.5vw, 2.25rem) !important;
          font-weight: 400 !important;
          color: #ffffff !important;
          line-height: 1.4 !important;
          margin-bottom: 32px !important;
        }
        
        .eahl-mission-quote em {
          font-style: italic;
          color: var(--eahl-accent);
        }
        
        .eahl-mission-body {
          font-size: 1.1rem;
          color: rgba(255, 255, 255, 0.8);
          line-height: 1.8;
          margin-bottom: 40px;
        }
        
        .eahl-mission-body strong {
          color: #ffffff;
          font-weight: 500;
        }
        
        .eahl-values-row {
          display: flex;
          gap: 12px;
          justify-content: center;
          flex-wrap: wrap;
        }
        
        .eahl-value-tag {
          font-size: 0.9rem;
          font-weight: 500;
          color: rgba(255, 255, 255, 0.9);
          padding: 10px 20px;
          background: rgba(255, 255, 255, 0.1);
          border: 1px solid rgba(255, 255, 255, 0.15);
          border-radius: 100px;
          transition: all 0.2s ease;
        }
        
        .eahl-value-tag:hover {
          background: rgba(255, 255, 255, 0.15);
          transform: translateY(-2px);
        }
        
        /* ===== CTA SECTION ===== */
        .eahl-cta-section {
          background: var(--eahl-cream) !important;
        }
        
        .eahl-cta-card {
          background: #ffffff;
          border: 1px solid #e5e7eb;
          border-radius: 20px;
          padding: 60px 48px;
          max-width: 700px;
          margin: 0 auto;
          text-align: center;
          position: relative;
          overflow: hidden;
        }
        
        .eahl-cta-card::before {
          content: '';
          position: absolute;
          top: 0;
          left: 40px;
          right: 40px;
          height: 4px;
          background: linear-gradient(90deg, var(--eahl-accent), var(--eahl-coral), var(--eahl-sage));
          border-radius: 0 0 4px 4px;
        }
        
        .eahl-cta-title {
          font-size: 1.75rem !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 16px !important;
        }
        
        .eahl-cta-desc {
          font-size: 1.05rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          margin-bottom: 28px;
        }
        
        .eahl-cta-roles {
          display: flex;
          gap: 8px;
          justify-content: center;
          flex-wrap: wrap;
          margin-bottom: 32px;
        }
        
        .eahl-role {
          font-size: 0.9rem;
          font-weight: 500;
          padding: 8px 16px;
          border-radius: 8px;
        }
        
        .eahl-role-phd { background: rgba(74, 144, 164, 0.12); color: var(--eahl-accent); }
        .eahl-role-postdoc { background: rgba(224, 122, 95, 0.12); color: var(--eahl-coral); }
        .eahl-role-participant { background: rgba(107, 143, 113, 0.12); color: var(--eahl-sage); }
        
        .eahl-cta-button {
          display: inline-flex;
          align-items: center;
          gap: 8px;
          font-size: 1rem;
          font-weight: 600;
          color: #ffffff !important;
          background: var(--eahl-navy);
          padding: 16px 36px;
          border-radius: 100px;
          text-decoration: none !important;
          transition: all 0.3s ease;
        }
        
        .eahl-cta-button:hover {
          background: var(--eahl-accent);
          transform: translateY(-2px);
          box-shadow: 0 12px 24px rgba(74, 144, 164, 0.25);
        }
        
        /* ===== RESPONSIVE ===== */
        @media (max-width: 768px) {
          .eahl-hero-content { padding: 20px 16px; }
          .eahl-pillar-card { padding: 32px 24px; }
          .eahl-cta-card { padding: 40px 24px; }
          .eahl-cta-card::before { left: 20px; right: 20px; }
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
        <div class="eahl-hero-content">
          <div class="eahl-hero-label">
            Research Laboratory
          </div>
          <h1 class="eahl-hero-title">
            Electric & Acoustic
            <span class="eahl-hero-title-accent">Hearing Lab</span>
          </h1>
          <p class="eahl-hero-subtitle">
            Decoding the neural basis of auditory perception to transform hearing restoration for cochlear implant users.
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
          <h2 class="eahl-section-title">Research Focus</h2>
          <div class="eahl-section-divider"></div>
        </div>
        <div class="eahl-pillars-grid">
          <div class="eahl-pillar-card" style="--card-color: #4a90a4; --icon-bg: rgba(74, 144, 164, 0.12); --icon-color: #4a90a4;">
            <div class="eahl-pillar-icon">
              <i class="fas fa-ear-listen"></i>
            </div>
            <h3 class="eahl-pillar-title">Cochlear Implants</h3>
            <p class="eahl-pillar-desc">
              Pioneering electrical stimulation strategies to restore natural pitch perception and improve music appreciation for CI users.
            </p>
          </div>
          <div class="eahl-pillar-card" style="--card-color: #e07a5f; --icon-bg: rgba(224, 122, 95, 0.12); --icon-color: #e07a5f;">
            <div class="eahl-pillar-icon">
              <i class="fas fa-wave-square"></i>
            </div>
            <h3 class="eahl-pillar-title">Psychoacoustics</h3>
            <p class="eahl-pillar-desc">
              Quantifying auditory perception through rigorous behavioral experiments, adaptive psychophysical methods, and computational modeling.
            </p>
          </div>
          <div class="eahl-pillar-card" style="--card-color: #6b8f71; --icon-bg: rgba(107, 143, 113, 0.12); --icon-color: #6b8f71;">
            <div class="eahl-pillar-icon">
              <i class="fas fa-brain"></i>
            </div>
            <h3 class="eahl-pillar-title">Auditory Neuroscience</h3>
            <p class="eahl-pillar-desc">
              Mapping neural health, cortical plasticity, and reorganization using high-density EEG and advanced signal processing.
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
            Hearing is more than detecting sound—it's the <em>foundation of human connection.</em>
          </h2>
          <p class="eahl-mission-body">
            By integrating <strong>computational modeling</strong>, <strong>psychophysical testing</strong>, and <strong>neuroimaging</strong>, we're decoding how the brain processes sound to create better hearing solutions.
          </p>
          <div class="eahl-values-row">
            <span class="eahl-value-tag">Open Science</span>
            <span class="eahl-value-tag">Reproducible Research</span>
            <span class="eahl-value-tag">Student-Centered</span>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["120px", "20px", "120px", "20px"]
      css_class: "eahl-mission-section"

  # -----------------------------------------------------------------------------
  # 4. CTA
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="eahl-cta-card">
          <h2 class="eahl-cta-title">Join Our Research Team</h2>
          <p class="eahl-cta-desc">
            We're actively recruiting researchers and participants to advance auditory neuroscience.
          </p>
          <div class="eahl-cta-roles">
            <span class="eahl-role eahl-role-phd">PhD Students</span>
            <span class="eahl-role eahl-role-postdoc">Postdoctoral Fellows</span>
            <span class="eahl-role eahl-role-participant">Study Participants</span>
          </div>
          <a href="./contact/" class="eahl-cta-button">
            Get Involved →
          </a>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["80px", "20px", "120px", "20px"]
      css_class: "eahl-cta-section"
---