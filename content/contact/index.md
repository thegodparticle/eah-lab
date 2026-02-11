---
title: Join Us
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
        
        .join-page h1, .join-page h2, .join-page h3 {
          font-family: 'Playfair Display', Georgia, serif !important;
        }
        
        .join-page p, .join-page span, .join-page a, .join-page li {
          font-family: 'Source Sans 3', -apple-system, sans-serif !important;
        }
        
        /* ===== HERO ===== */
        .join-hero {
          background: linear-gradient(180deg, #ffffff 0%, var(--eahl-cream) 100%) !important;
        }
        
        .join-hero-content {
          max-width: 750px;
          margin: 0 auto;
          text-align: center;
          padding: 0 20px;
        }
        
        .join-hero-label {
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
        
        .join-hero-label::before,
        .join-hero-label::after {
          content: '';
          width: 32px;
          height: 1px;
          background: var(--eahl-accent);
          opacity: 0.5;
        }
        
        .join-hero-title {
          font-size: clamp(2.2rem, 5vw, 3.2rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          line-height: 1.2 !important;
          margin-bottom: 20px !important;
          letter-spacing: -0.02em;
        }
        
        .join-hero-title em {
          font-style: italic;
          color: var(--eahl-accent);
        }
        
        .join-hero-subtitle {
          font-size: 1.2rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          max-width: 600px;
          margin: 0 auto;
        }
        
        /* ===== OPPORTUNITIES GRID ===== */
        .join-opportunities {
          background: var(--eahl-cream) !important;
        }
        
        .opportunities-grid {
          display: grid;
          grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
          gap: 32px;
          max-width: 1000px;
          margin: 0 auto;
        }
        
        .opportunity-card {
          background: #ffffff;
          border: 1px solid #e5e7eb;
          border-radius: 20px;
          padding: 44px 36px;
          position: relative;
          overflow: hidden;
          transition: all 0.3s ease;
        }
        
        .opportunity-card::before {
          content: '';
          position: absolute;
          top: 0;
          left: 0;
          right: 0;
          height: 4px;
          background: var(--card-accent);
        }
        
        .opportunity-card:hover {
          transform: translateY(-6px);
          box-shadow: 0 24px 48px rgba(10, 22, 40, 0.1);
          border-color: transparent;
        }
        
        .opportunity-icon {
          width: 56px;
          height: 56px;
          border-radius: 14px;
          display: flex;
          align-items: center;
          justify-content: center;
          margin-bottom: 28px;
          font-size: 1.5rem;
          background: var(--icon-bg);
          color: var(--icon-color);
        }
        
        .opportunity-title {
          font-size: 1.6rem !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 14px !important;
          letter-spacing: -0.01em;
        }
        
        .opportunity-desc {
          font-size: 1.05rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          margin-bottom: 28px;
        }
        
        .opportunity-benefits {
          list-style: none;
          padding: 0;
          margin: 0 0 32px 0;
        }
        
        .opportunity-benefits li {
          display: flex;
          align-items: center;
          gap: 12px;
          font-size: 1rem;
          color: var(--eahl-text);
          padding: 10px 0;
          border-bottom: 1px solid #f3f4f6;
        }
        
        .opportunity-benefits li:last-child {
          border-bottom: none;
        }
        
        .benefit-icon {
          width: 20px;
          height: 20px;
          border-radius: 50%;
          display: flex;
          align-items: center;
          justify-content: center;
          font-size: 0.65rem;
          flex-shrink: 0;
          background: var(--check-bg);
          color: var(--check-color);
        }
        
        .opportunity-btn {
          display: inline-flex;
          align-items: center;
          gap: 8px;
          font-size: 1rem;
          font-weight: 600;
          padding: 14px 28px;
          border-radius: 100px;
          text-decoration: none !important;
          transition: all 0.3s ease;
          background: var(--btn-bg);
          color: #ffffff !important;
        }
        
        .opportunity-btn:hover {
          transform: translateY(-2px);
          box-shadow: 0 12px 24px var(--btn-shadow);
        }
        
        /* ===== VISIT SECTION ===== */
        .join-visit {
          background: #ffffff !important;
        }
        
        .visit-container {
          max-width: 1000px;
          margin: 0 auto;
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 64px;
          align-items: start;
        }
        
        .visit-info {
          padding-right: 20px;
        }
        
        .visit-section-label {
          font-size: 0.75rem;
          font-weight: 600;
          letter-spacing: 0.2em;
          text-transform: uppercase;
          color: var(--eahl-accent);
          margin-bottom: 16px;
          display: block;
        }
        
        .visit-title {
          font-size: clamp(1.8rem, 3vw, 2.4rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 20px !important;
          letter-spacing: -0.02em;
        }
        
        .visit-intro {
          font-size: 1.1rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          margin-bottom: 40px;
        }
        
        .visit-intro strong {
          color: var(--eahl-navy);
          font-weight: 600;
        }
        
        .contact-details {
          display: flex;
          flex-direction: column;
          gap: 20px;
        }
        
        .contact-item {
          display: flex;
          align-items: flex-start;
          gap: 16px;
        }
        
        .contact-icon {
          width: 44px;
          height: 44px;
          border-radius: 12px;
          display: flex;
          align-items: center;
          justify-content: center;
          font-size: 1rem;
          flex-shrink: 0;
          background: rgba(74, 144, 164, 0.1);
          color: var(--eahl-accent);
        }
        
        .contact-text {
          flex: 1;
        }
        
        .contact-label {
          font-size: 0.85rem;
          font-weight: 600;
          color: var(--eahl-text-light);
          text-transform: uppercase;
          letter-spacing: 0.05em;
          margin-bottom: 4px;
          display: block;
        }
        
        .contact-value {
          font-size: 1.05rem;
          color: var(--eahl-navy);
          line-height: 1.5;
        }
        
        .contact-value a {
          color: var(--eahl-accent) !important;
          text-decoration: none !important;
          transition: color 0.2s ease;
        }
        
        .contact-value a:hover {
          color: var(--eahl-coral) !important;
        }
        
        /* ===== MAP CARD ===== */
        .map-card {
          background: var(--eahl-cream);
          border-radius: 20px;
          overflow: hidden;
          border: 1px solid #e5e7eb;
        }
        
        .map-embed {
          width: 100%;
          height: 280px;
          border: none;
          display: block;
        }
        
        .map-footer {
          padding: 24px 28px;
          display: flex;
          align-items: center;
          justify-content: space-between;
          gap: 16px;
          flex-wrap: wrap;
        }
        
        .map-address {
          font-size: 0.95rem;
          color: var(--eahl-text);
          line-height: 1.5;
        }
        
        .map-address strong {
          display: block;
          color: var(--eahl-navy);
          font-weight: 600;
          margin-bottom: 2px;
        }
        
        .directions-btn {
          display: inline-flex;
          align-items: center;
          gap: 6px;
          font-size: 0.9rem;
          font-weight: 600;
          color: var(--eahl-accent) !important;
          text-decoration: none !important;
          padding: 10px 20px;
          border: 1px solid var(--eahl-accent);
          border-radius: 100px;
          transition: all 0.2s ease;
        }
        
        .directions-btn:hover {
          background: var(--eahl-accent);
          color: #ffffff !important;
        }
        
        /* ===== CONTACT FORM ===== */
        .join-contact-section {
          background: var(--eahl-cream) !important;
        }
        
        .form-container {
          max-width: 600px;
          margin: 0 auto;
          text-align: center;
        }
        
        .form-title {
          font-size: clamp(1.6rem, 3vw, 2rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 12px !important;
        }
        
        .form-subtitle {
          font-size: 1.1rem;
          color: var(--eahl-text-light);
          margin-bottom: 40px;
        }
        
        .contact-form-card {
          background: #ffffff;
          border: 1px solid #e5e7eb;
          border-radius: 20px;
          padding: 40px;
          text-align: left;
        }
        
        .form-group {
          margin-bottom: 24px;
        }
        
        .form-label {
          display: block;
          font-size: 0.9rem;
          font-weight: 600;
          color: var(--eahl-navy);
          margin-bottom: 8px;
        }
        
        .form-input,
        .form-textarea {
          width: 100%;
          padding: 14px 18px;
          font-size: 1rem;
          font-family: 'Source Sans 3', sans-serif;
          color: var(--eahl-navy);
          background: var(--eahl-cream);
          border: 1px solid #e5e7eb;
          border-radius: 12px;
          transition: all 0.2s ease;
          box-sizing: border-box;
        }
        
        .form-input:focus,
        .form-textarea:focus {
          outline: none;
          border-color: var(--eahl-accent);
          box-shadow: 0 0 0 3px rgba(74, 144, 164, 0.1);
        }
        
        .form-textarea {
          min-height: 140px;
          resize: vertical;
        }
        
        .form-submit {
          width: 100%;
          padding: 16px 32px;
          font-size: 1.05rem;
          font-weight: 600;
          font-family: 'Source Sans 3', sans-serif;
          color: #ffffff;
          background: var(--eahl-navy);
          border: none;
          border-radius: 100px;
          cursor: pointer;
          transition: all 0.3s ease;
        }
        
        .form-submit:hover {
          background: var(--eahl-accent);
          transform: translateY(-2px);
          box-shadow: 0 12px 24px rgba(74, 144, 164, 0.25);
        }
        
        /* ===== RESPONSIVE ===== */
        @media (max-width: 900px) {
          .visit-container {
            grid-template-columns: 1fr;
            gap: 48px;
          }
          .visit-info { padding-right: 0; }
        }
        
        @media (max-width: 768px) {
          .opportunities-grid { grid-template-columns: 1fr; }
          .opportunity-card { padding: 36px 28px; }
          .contact-form-card { padding: 28px 24px; }
          .map-footer { flex-direction: column; align-items: flex-start; }
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
        <div class="join-hero-content">
          <div class="join-hero-label">Join Our Team</div>
          <h1 class="join-hero-title">
            Let's shape the future of <em>hearing together.</em>
          </h1>
          <p class="join-hero-subtitle">
            Whether you're a student ready to dive into research or a community member eager to participate in studies, we want to hear from you.
          </p>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "80px", "20px"]
      css_class: "join-page join-hero"

  # -----------------------------------------------------------------------------
  # 2. OPPORTUNITIES
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="opportunities-grid">
          <div class="opportunity-card" style="--card-accent: #4a90a4; --icon-bg: rgba(74, 144, 164, 0.12); --icon-color: #4a90a4; --check-bg: rgba(74, 144, 164, 0.12); --check-color: #4a90a4; --btn-bg: #4a90a4; --btn-shadow: rgba(74, 144, 164, 0.3);">
            <div class="opportunity-icon">
              <i class="fas fa-graduation-cap"></i>
            </div>
            <h3 class="opportunity-title">PhD Opportunities</h3>
            <p class="opportunity-desc">
              Join a dynamic team at the intersection of engineering and neuroscience. We provide full funding, travel support, and hands-on mentorship.
            </p>
            <ul class="opportunity-benefits">
              <li>
                <span class="benefit-icon"><i class="fas fa-check"></i></span>
                Full Tuition & Stipend
              </li>
              <li>
                <span class="benefit-icon"><i class="fas fa-check"></i></span>
                Conference Travel Funding
              </li>
              <li>
                <span class="benefit-icon"><i class="fas fa-check"></i></span>
                Advanced Signal Processing Training
              </li>
            </ul>
            <a href="mailto:narslan@southalabama.edu?subject=PhD%20Application%20Inquiry" class="opportunity-btn">
              Apply Now <span>→</span>
            </a>
          </div>
          
          <div class="opportunity-card" style="--card-accent: #e07a5f; --icon-bg: rgba(224, 122, 95, 0.12); --icon-color: #e07a5f; --check-bg: rgba(224, 122, 95, 0.12); --check-color: #e07a5f; --btn-bg: #e07a5f; --btn-shadow: rgba(224, 122, 95, 0.3);">
            <div class="opportunity-icon">
              <i class="fas fa-users"></i>
            </div>
            <h3 class="opportunity-title">Study Participation</h3>
            <p class="opportunity-desc">
              Have a cochlear implant? Help us improve hearing technology for everyone. Our studies are safe, non-invasive, and work around your schedule.
            </p>
            <ul class="opportunity-benefits">
              <li>
                <span class="benefit-icon"><i class="fas fa-check"></i></span>
                Paid Compensation ($/hr)
              </li>
              <li>
                <span class="benefit-icon"><i class="fas fa-check"></i></span>
                Free Reserved Parking
              </li>
              <li>
                <span class="benefit-icon"><i class="fas fa-check"></i></span>
                Flexible Scheduling
              </li>
            </ul>
            <a href="mailto:narslan@southalabama.edu?subject=Study%20Participation" class="opportunity-btn">
              Join a Study <span>→</span>
            </a>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["0", "20px", "100px", "20px"]
      css_class: "join-page join-opportunities"

  # -----------------------------------------------------------------------------
  # 3. VISIT THE LAB
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="visit-container">
        <div class="visit-info">
        <span class="visit-section-label">Location</span>
        <h2 class="visit-title">Visit the Lab</h2>
        <p class="visit-intro">
        The <strong>Electric & Acoustic Hearing Lab</strong> is located in the <strong>Health Sciences Building (HAHN)</strong> at the University of South Alabama.
        </p>

        <div class="contact-details">
        <div class="contact-item">
        <div class="contact-icon">
        <i class="fas fa-envelope"></i>
        </div>
        <div class="contact-text">
        <span class="contact-label">Email</span>
        <div class="contact-value">
        <a href="mailto:niyaziarslan@southalabama.edu">niyaziarslan@southalabama.edu</a>
        </div>
        </div>
        </div>

        <div class="contact-item">
        <div class="contact-icon">
        <i class="fas fa-phone"></i>
        </div>
        <div class="contact-text">
        <span class="contact-label">Phone</span>
        <div class="contact-value">
        <a href="tel:+12514606000">+1 (251) 460-6000</a>
        </div>
        </div>
        </div>

        <div class="contact-item">
        <div class="contact-icon">
        <i class="fas fa-clock"></i>
        </div>
        <div class="contact-text">
        <span class="contact-label">Office Hours</span>
        <div class="contact-value">By Appointment</div>
        </div>
        </div>
        </div>
        </div>

        <div class="map-card">
        <iframe 
        class="map-embed"
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3450.8!2d-88.1786!3d30.6966!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMzDCsDQxJzQ3LjgiTiA4OMKwMTAnNDMuMCJX!5e0!3m2!1sen!2sus!4v1"
        allowfullscreen=""
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade">
        </iframe>
        <div class="map-footer">
        <div class="map-address">
        <strong>Health Sciences Building (HAHN)</strong>
        5721 USA Drive North<br>
        Mobile, AL 36688
        </div>
        <a href="https://www.google.com/maps/dir/?api=1&destination=30.6966,-88.1786" target="_blank" class="directions-btn">
        <i class="fas fa-directions"></i> Get Directions
        </a>
        </div>
        </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "100px", "20px"]
      css_class: "join-page join-visit"

  # -----------------------------------------------------------------------------
  # 4. CONTACT FORM
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="form-container">
          <h2 class="form-title">Send Us a Message</h2>
          <p class="form-subtitle">Have questions? We'd love to hear from you.</p>
          <div class="contact-form-card">
            <form name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field">
              <input type="hidden" name="form-name" value="contact">
              <p style="display:none;">
                <label>Don't fill this out: <input name="bot-field"></label>
              </p>   
              <div class="form-group">
                <label class="form-label" for="name">Your Name</label>
                <input type="text" id="name" name="name" class="form-input" required placeholder="John Doe">
              </div>
              <div class="form-group">
                <label class="form-label" for="email">Email Address</label>
                <input type="email" id="email" name="email" class="form-input" required placeholder="john@example.com">
              </div>
              <div class="form-group">
                <label class="form-label" for="subject">Subject</label>
                <input type="text" id="subject" name="subject" class="form-input" placeholder="PhD Inquiry / Study Participation / General">
              </div>
              <div class="form-group">
                <label class="form-label" for="message">Message</label>
                <textarea id="message" name="message" class="form-textarea" required placeholder="Tell us how we can help..."></textarea>
              </div>
              <button type="submit" class="form-submit">Send Message →</button>
            </form>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "120px", "20px"]
      css_class: "join-page join-contact-section"
---