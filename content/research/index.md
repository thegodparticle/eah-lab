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
        
        .research-page p, .research-page span, .research-page a, .research-page li {
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
          font-size: clamp(2.25rem, 5vw, 3.25rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          line-height: 1.2 !important;
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
          max-width: 700px;
          margin: 0 auto;
        }
        
        .research-hero-desc strong {
          color: var(--eahl-navy);
          font-weight: 600;
        }
        
        /* ===== QUESTION CARDS ===== */
        .research-questions {
          background: var(--eahl-cream) !important;
        }
        
        .question-card {
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
        
        .question-card:last-child {
          margin-bottom: 0;
        }
        
        .question-card:hover {
          box-shadow: 0 32px 64px rgba(10, 22, 40, 0.1);
          transform: translateY(-4px);
        }
        
        .question-card.reversed {
          direction: rtl;
        }
        
        .question-card.reversed > * {
          direction: ltr;
        }
        
        .question-image {
          position: relative;
          min-height: 420px;
          background-size: cover;
          background-position: center;
        }
        
        .question-image::after {
          content: '';
          position: absolute;
          inset: 0;
          background: linear-gradient(135deg, rgba(10, 22, 40, 0.15) 0%, rgba(10, 22, 40, 0.05) 100%);
        }
        
        .question-content {
          padding: 56px 48px;
          display: flex;
          flex-direction: column;
          justify-content: center;
        }
        
        .question-number {
          font-family: 'Playfair Display', serif !important;
          font-size: 4rem;
          font-weight: 400;
          line-height: 1;
          margin-bottom: 20px;
          opacity: 0.08;
          color: var(--eahl-navy);
        }
        
        .question-label {
          font-size: 0.75rem;
          font-weight: 600;
          letter-spacing: 0.15em;
          text-transform: uppercase;
          margin-bottom: 12px;
        }
        
        .question-label.accent { color: var(--eahl-accent); }
        .question-label.coral { color: var(--eahl-coral); }
        .question-label.sage { color: var(--eahl-sage); }
        
        .question-heading {
          font-size: clamp(1.4rem, 2.5vw, 1.75rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          line-height: 1.35 !important;
          margin-bottom: 20px !important;
          letter-spacing: -0.01em;
          font-style: italic;
        }
        
        .question-text {
          font-size: 1.05rem;
          color: var(--eahl-text-light);
          line-height: 1.75;
          margin-bottom: 28px;
        }
        
        .question-text strong {
          color: var(--eahl-navy);
          font-weight: 600;
        }
        
        .question-approaches {
          margin: 0;
          padding: 0;
          list-style: none;
        }
        
        .question-approaches li {
          position: relative;
          padding-left: 20px;
          margin-bottom: 8px;
          font-size: 0.95rem;
          color: var(--eahl-text);
        }
        
        .question-approaches li::before {
          content: '';
          position: absolute;
          left: 0;
          top: 10px;
          width: 8px;
          height: 2px;
          border-radius: 1px;
        }
        
        .question-approaches.accent li::before { background: var(--eahl-accent); }
        .question-approaches.coral li::before { background: var(--eahl-coral); }
        .question-approaches.sage li::before { background: var(--eahl-sage); }
        
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
          .question-card,
          .question-card.reversed {
            grid-template-columns: 1fr;
            direction: ltr;
          }
          .question-card.reversed > * {
            direction: ltr;
          }
          .question-image {
            min-height: 280px;
            order: -1;
          }
          .question-content {
            padding: 40px 32px;
          }
          .question-number {
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