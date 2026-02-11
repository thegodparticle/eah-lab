---
title: Research Overview
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
        
        .research-page h1, .research-page h2, .research-page h3 {
          font-family: 'Playfair Display', Georgia, serif !important;
        }
        
        .research-page p, .research-page span, .research-page a {
          font-family: 'Source Sans 3', -apple-system, sans-serif !important;
        }
        
        /* ===== HERO ===== */
        .research-hero {
          background: linear-gradient(180deg, #ffffff 0%, var(--eahl-cream) 100%) !important;
        }
        
        .research-hero-content {
          max-width: 800px;
          margin: 0 auto;
          text-align: center;
          padding: 0 24px;
        }
        
        .research-hero-label {
          display: inline-flex;
          align-items: center;
          gap: 12px;
          font-size: 0.75rem;
          font-weight: 600;
          letter-spacing: 0.2em;
          text-transform: uppercase;
          color: var(--eahl-accent);
          margin-bottom: 24px;
        }
        
        .research-hero-label::before,
        .research-hero-label::after {
          content: '';
          width: 32px;
          height: 1px;
          background: var(--eahl-accent);
          opacity: 0.5;
        }
        
        .research-hero-title {
          font-size: clamp(2.5rem, 5.5vw, 4rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          line-height: 1.1 !important;
          margin-bottom: 24px !important;
          letter-spacing: -0.02em;
        }
        
        .research-hero-title em {
          font-style: italic;
          color: var(--eahl-accent);
        }
        
        .research-hero-divider {
          width: 64px;
          height: 3px;
          background: var(--eahl-coral);
          margin: 0 auto 32px auto;
          border-radius: 2px;
        }
        
        .research-hero-desc {
          font-size: 1.2rem;
          color: var(--eahl-text-light);
          line-height: 1.75;
          max-width: 680px;
          margin: 0 auto;
        }
        
        .research-hero-desc strong {
          color: var(--eahl-navy);
          font-weight: 600;
        }
        
        /* ===== PILLAR CARDS ===== */
        .research-pillars {
          background: var(--eahl-cream) !important;
        }
        
        .pillar-card {
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 0;
          max-width: 1100px;
          margin: 0 auto 48px auto;
          background: #ffffff;
          border-radius: 24px;
          overflow: hidden;
          border: 1px solid #e5e7eb;
          transition: all 0.4s ease;
        }
        
        .pillar-card:last-child {
          margin-bottom: 0;
        }
        
        .pillar-card:hover {
          box-shadow: 0 32px 64px rgba(10, 22, 40, 0.1);
          transform: translateY(-4px);
        }
        
        .pillar-card.reversed {
          direction: rtl;
        }
        
        .pillar-card.reversed > * {
          direction: ltr;
        }
        
        .pillar-image {
          position: relative;
          min-height: 420px;
          background-size: cover;
          background-position: center;
        }
        
        .pillar-image::after {
          content: '';
          position: absolute;
          inset: 0;
          background: linear-gradient(135deg, rgba(10, 22, 40, 0.15) 0%, rgba(10, 22, 40, 0.05) 100%);
        }
        
        .pillar-content {
          padding: 56px 48px;
          display: flex;
          flex-direction: column;
          justify-content: center;
        }
        
        .pillar-number {
          font-family: 'Playfair Display', serif !important;
          font-size: 4rem;
          font-weight: 400;
          line-height: 1;
          margin-bottom: 20px;
          opacity: 0.08;
          color: var(--eahl-navy);
        }
        
        .pillar-label {
          font-size: 0.75rem;
          font-weight: 600;
          letter-spacing: 0.15em;
          text-transform: uppercase;
          margin-bottom: 12px;
        }
        
        .pillar-label.accent { color: var(--eahl-accent); }
        .pillar-label.coral { color: var(--eahl-coral); }
        .pillar-label.sage { color: var(--eahl-sage); }
        
        .pillar-heading {
          font-size: clamp(1.75rem, 3vw, 2.25rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          line-height: 1.2 !important;
          margin-bottom: 20px !important;
          letter-spacing: -0.02em;
        }
        
        .pillar-text {
          font-size: 1.05rem;
          color: var(--eahl-text-light);
          line-height: 1.75;
          margin-bottom: 28px;
        }
        
        .pillar-text strong {
          color: var(--eahl-navy);
          font-weight: 600;
        }
        
        .pillar-tags {
          display: flex;
          flex-wrap: wrap;
          gap: 10px;
        }
        
        .pillar-tag {
          display: inline-block;
          padding: 8px 16px;
          border-radius: 100px;
          font-size: 0.85rem;
          font-weight: 500;
          transition: all 0.2s ease;
        }
        
        .pillar-tag.accent {
          color: var(--eahl-accent);
          background: rgba(74, 144, 164, 0.1);
          border: 1px solid rgba(74, 144, 164, 0.2);
        }
        
        .pillar-tag.coral {
          color: var(--eahl-coral);
          background: rgba(224, 122, 95, 0.1);
          border: 1px solid rgba(224, 122, 95, 0.2);
        }
        
        .pillar-tag.sage {
          color: var(--eahl-sage);
          background: rgba(107, 143, 113, 0.1);
          border: 1px solid rgba(107, 143, 113, 0.2);
        }
        
        .pillar-tag:hover {
          transform: translateY(-2px);
        }
        
        /* ===== CTA SECTION ===== */
        .research-cta {
          background: #ffffff !important;
        }
        
        .research-cta-content {
          max-width: 650px;
          margin: 0 auto;
          text-align: center;
          padding: 0 24px;
        }
        
        .research-cta-label {
          font-size: 0.75rem;
          font-weight: 600;
          letter-spacing: 0.2em;
          text-transform: uppercase;
          color: var(--eahl-accent);
          margin-bottom: 16px;
          display: block;
        }
        
        .research-cta-title {
          font-size: clamp(1.8rem, 3.5vw, 2.5rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 16px !important;
          letter-spacing: -0.02em;
        }
        
        .research-cta-desc {
          font-size: 1.1rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          margin-bottom: 40px;
        }
        
        .research-cta-btn {
          display: inline-flex;
          align-items: center;
          gap: 10px;
          font-size: 1.05rem;
          font-weight: 600;
          color: #ffffff !important;
          background: var(--eahl-navy);
          padding: 18px 40px;
          border-radius: 100px;
          text-decoration: none !important;
          transition: all 0.3s ease;
        }
        
        .research-cta-btn:hover {
          background: var(--eahl-accent);
          transform: translateY(-3px);
          box-shadow: 0 16px 32px rgba(74, 144, 164, 0.25);
        }
        
        /* ===== RESPONSIVE ===== */
        @media (max-width: 900px) {
          .pillar-card,
          .pillar-card.reversed {
            grid-template-columns: 1fr;
            direction: ltr;
          }
          .pillar-card.reversed > * {
            direction: ltr;
          }
          .pillar-image {
            min-height: 280px;
            order: -1;
          }
          .pillar-content {
            padding: 40px 32px;
          }
          .pillar-number {
            font-size: 3rem;
          }
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
        <div class="research-hero-content">
          <div class="research-hero-label">Our Methodology</div>
          <h1 class="research-hero-title">
            From Electrode<br>to <em>Cortex</em>
          </h1>
          <div class="research-hero-divider"></div>
          <p class="research-hero-desc">
            We don't just study the ear — we study the <strong>entire auditory pathway</strong>. By combining electrical engineering, psychophysics, and neuroscience, we bridge the gap between artificial stimulation and natural perception.
          </p>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["120px", "20px", "100px", "20px"]
      css_class: "research-page research-hero"

  # -----------------------------------------------------------------------------
  # 2. PILLAR 1 - COCHLEAR IMPLANTS
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="pillar-card">
          <div class="pillar-image" style="background-image: url('https://images.unsplash.com/photo-1518770660439-4636190af475?q=80&w=2670&auto=format&fit=crop');"></div>
          <div class="pillar-content">
            <div class="pillar-number">01</div>
            <p class="pillar-label accent">Cochlear Implants</p>
            <h2 class="pillar-heading">Focused Neural Stimulation</h2>
            <p class="pillar-text">
              Current implants spread electrical fields too broadly, creating muddy, distorted sound. We're engineering <strong>focused multipolar stimulation strategies</strong> that precisely shape electrical fields to target specific neural populations — restoring the spectral resolution needed for music and speech in noise.
            </p>
            <div class="pillar-tags">
              <span class="pillar-tag accent">Tripolar Stimulation</span>
              <span class="pillar-tag accent">Current Steering</span>
              <span class="pillar-tag accent">Phantom Electrodes</span>
            </div>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["80px", "20px", "24px", "20px"]
      css_class: "research-page research-pillars"

  # -----------------------------------------------------------------------------
  # 3. PILLAR 2 - PSYCHOACOUSTICS
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="pillar-card reversed">
          <div class="pillar-image" style="background-image: url('https://images.unsplash.com/photo-1484704849700-f032a568e944?q=80&w=2670&auto=format&fit=crop');"></div>
          <div class="pillar-content">
            <div class="pillar-number">02</div>
            <p class="pillar-label coral">Psychoacoustics</p>
            <h2 class="pillar-heading">Quantifying the Human Experience</h2>
            <p class="pillar-text">
              We don't just measure detection thresholds — we map the complete limits of perceptual resolution. Using rigorous <strong>psychophysical paradigms</strong> like spectral ripple discrimination and temporal modulation detection, we quantify exactly how much auditory detail a CI user can extract from their device.
            </p>
            <div class="pillar-tags">
              <span class="pillar-tag coral">Spectral Ripple</span>
              <span class="pillar-tag coral">Modulation Detection</span>
              <span class="pillar-tag coral">Pitch Scaling</span>
            </div>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["0", "20px", "24px", "20px"]
      css_class: "research-page research-pillars"

  # -----------------------------------------------------------------------------
  # 4. PILLAR 3 - AUDITORY NEUROSCIENCE
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="pillar-card">
          <div class="pillar-image" style="background-image: url('https://images.unsplash.com/photo-1559757175-5b8d42d634d3?q=80&w=2670&auto=format&fit=crop');"></div>
          <div class="pillar-content">
            <div class="pillar-number">03</div>
            <p class="pillar-label sage">Auditory Neuroscience</p>
            <h2 class="pillar-heading">The Plastic Brain</h2>
            <p class="pillar-text">
              The cochlea is just the entry point — the real transformation happens in the cortex. Using <strong>high-density EEG</strong>, we track how the auditory cortex reorganizes after hearing loss and implantation. Our goal: harness neuroplasticity to train the brain to extract meaning from artificial signals.
            </p>
            <div class="pillar-tags">
              <span class="pillar-tag sage">Cortical Potentials</span>
              <span class="pillar-tag sage">Source Localization</span>
              <span class="pillar-tag sage">Neural Adaptation</span>
            </div>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["0", "20px", "100px", "20px"]
      css_class: "research-page research-pillars"

  # -----------------------------------------------------------------------------
  # 5. CTA
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="research-cta-content">
          <span class="research-cta-label">Explore Further</span>
          <h2 class="research-cta-title">Dive Deeper</h2>
          <p class="research-cta-desc">
            See how we apply these methodologies in our peer-reviewed publications.
          </p>
          <a href="../publication/" class="research-cta-btn">
            View Publications <span>→</span>
          </a>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "120px", "20px"]
      css_class: "research-page research-cta"
---