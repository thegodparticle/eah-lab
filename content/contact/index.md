---
title: Join Us
date: "2026-01-01"
lastmod: "2026-02-15"
type: landing

sitemap:
  priority: 0.7
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
          --eahl-gold: #d4a574;
          --eahl-text: #374151;
          --eahl-text-light: #6b7280;
        }
        
        .join-page h1, .join-page h2, .join-page h3 {
          font-family: 'Playfair Display', Georgia, serif !important;
        }
        
        .join-page p, .join-page span, .join-page a, .join-page li, .join-page label {
          font-family: 'Source Sans 3', -apple-system, sans-serif !important;
        }
        
        /* ===== HERO ===== */
        .join-hero {
          background: var(--eahl-navy) !important;
          position: relative;
          overflow: hidden;
        }
        
        .join-hero::before {
          content: '';
          position: absolute;
          inset: 0;
          background: 
            radial-gradient(ellipse at 30% 20%, rgba(74, 144, 164, 0.15) 0%, transparent 50%),
            radial-gradient(ellipse at 70% 80%, rgba(224, 122, 95, 0.1) 0%, transparent 40%);
          pointer-events: none;
        }
        
        .join-hero-content {
          max-width: 800px;
          margin: 0 auto;
          text-align: center;
          padding: 0 24px;
          position: relative;
          z-index: 2;
        }
        
        .join-hero-badge {
          display: inline-block;
          font-size: 0.75rem;
          font-weight: 600;
          letter-spacing: 0.15em;
          text-transform: uppercase;
          color: #ffffff;
          background: var(--eahl-coral);
          padding: 8px 20px;
          border-radius: 100px;
          margin-bottom: 28px;
        }
        
        .join-hero-title {
          font-size: clamp(2.5rem, 5.5vw, 4rem) !important;
          font-weight: 500 !important;
          color: #ffffff !important;
          line-height: 1.1 !important;
          margin-bottom: 24px !important;
          letter-spacing: -0.02em;
        }
        
        .join-hero-title em {
          font-style: italic;
          color: var(--eahl-accent);
        }
        
        .join-hero-divider {
          width: 64px;
          height: 3px;
          background: linear-gradient(90deg, var(--eahl-accent), var(--eahl-coral));
          margin: 0 auto 28px auto;
          border-radius: 2px;
        }
        
        .join-hero-subtitle {
          font-size: 1.2rem;
          color: rgba(255, 255, 255, 0.75);
          line-height: 1.75;
          max-width: 620px;
          margin: 0 auto;
        }
        
        /* ===== SECTION HEADERS ===== */
        .section-header {
          text-align: center;
          margin-bottom: 48px;
        }
        
        .section-label {
          font-size: 0.75rem;
          font-weight: 600;
          letter-spacing: 0.15em;
          text-transform: uppercase;
          color: var(--eahl-accent);
          margin-bottom: 12px;
          display: block;
        }
        
        .section-title {
          font-size: clamp(1.8rem, 3.5vw, 2.5rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 16px !important;
          letter-spacing: -0.02em;
        }
        
        .section-desc {
          font-size: 1.1rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          max-width: 600px;
          margin: 0 auto;
        }
        
        /* ===== OPPORTUNITIES SECTION ===== */
        .join-opportunities {
          background: var(--eahl-cream) !important;
        }
        
        .join-container {
          max-width: 1200px;
          margin: 0 auto;
          padding: 0 24px;
        }
        
        .join-grid {
          display: grid;
          grid-template-columns: repeat(2, 1fr);
          gap: 28px;
        }
        
        .join-card {
          background: #ffffff;
          border: 1px solid #e5e7eb;
          border-radius: 20px;
          padding: 36px 32px;
          position: relative;
          transition: all 0.3s ease;
        }
        
        .join-card::before {
          content: '';
          position: absolute;
          top: 0;
          left: 0;
          right: 0;
          height: 4px;
          background: var(--card-accent);
          border-radius: 20px 20px 0 0;
        }
        
        .join-card:hover {
          transform: translateY(-4px);
          box-shadow: 0 20px 40px rgba(10, 22, 40, 0.08);
          border-color: transparent;
        }
        
        .join-card-header {
          display: flex;
          align-items: flex-start;
          gap: 16px;
          margin-bottom: 20px;
        }
        
        .join-card-icon {
          width: 52px;
          height: 52px;
          border-radius: 14px;
          display: flex;
          align-items: center;
          justify-content: center;
          font-size: 1.4rem;
          flex-shrink: 0;
          background: var(--icon-bg);
          color: var(--icon-color);
        }
        
        .join-card-title-wrap {
          flex: 1;
        }
        
        .join-card-title {
          font-size: 1.25rem !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin: 0 0 4px 0 !important;
        }
        
        .join-card-subtitle {
          font-size: 0.85rem;
          color: var(--eahl-text-light);
          margin: 0;
        }
        
        .join-card-desc {
          font-size: 0.98rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          margin-bottom: 20px;
        }
        
        .join-card-list {
          list-style: none;
          padding: 0;
          margin: 0 0 20px 0;
        }
        
        .join-card-list li {
          position: relative;
          padding-left: 18px;
          margin-bottom: 8px;
          font-size: 0.9rem;
          color: var(--eahl-text);
          line-height: 1.5;
        }
        
        .join-card-list li::before {
          content: '';
          position: absolute;
          left: 0;
          top: 7px;
          width: 5px;
          height: 5px;
          border-radius: 50%;
          background: var(--card-accent);
        }
        
        .join-card-footer {
          display: flex;
          align-items: center;
          justify-content: space-between;
          gap: 12px;
          padding-top: 16px;
          border-top: 1px solid #f3f4f6;
        }
        
        .join-card-status {
          display: inline-block;
          font-size: 0.75rem;
          font-weight: 600;
          text-transform: uppercase;
          letter-spacing: 0.08em;
          padding: 5px 12px;
          border-radius: 6px;
        }
        
        .status-recruiting {
          background: rgba(107, 143, 113, 0.15);
          color: var(--eahl-sage);
        }
        
        .status-open {
          background: rgba(74, 144, 164, 0.15);
          color: var(--eahl-accent);
        }
        
        .join-card-link {
          font-size: 0.9rem;
          font-weight: 600;
          color: var(--card-accent) !important;
          text-decoration: none !important;
          display: inline-flex;
          align-items: center;
          gap: 6px;
          transition: gap 0.2s ease;
        }
        
        .join-card-link:hover {
          gap: 10px;
        }
        
        /* ===== PARTICIPANTS SECTION ===== */
        .join-participants {
          background: #ffffff !important;
        }
        
        .participant-card {
          background: var(--eahl-cream);
          border-radius: 24px;
          padding: 48px;
          max-width: 900px;
          margin: 0 auto;
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 48px;
          align-items: center;
        }
        
        .participant-content h3 {
          font-size: 1.5rem !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin: 0 0 16px 0 !important;
        }
        
        .participant-content p {
          font-size: 1.05rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          margin-bottom: 24px;
        }
        
        .participant-benefits {
          display: flex;
          flex-wrap: wrap;
          gap: 12px;
          margin-bottom: 28px;
        }
        
        .participant-benefit {
          display: inline-flex;
          align-items: center;
          gap: 8px;
          font-size: 0.9rem;
          font-weight: 500;
          color: var(--eahl-navy);
          background: #ffffff;
          padding: 10px 16px;
          border-radius: 100px;
        }
        
        .participant-benefit i {
          color: var(--eahl-sage);
        }
        
        .participant-btn {
          display: inline-flex;
          align-items: center;
          gap: 10px;
          font-size: 1rem;
          font-weight: 600;
          color: #ffffff !important;
          background: var(--eahl-sage);
          padding: 16px 32px;
          border-radius: 100px;
          text-decoration: none !important;
          transition: all 0.3s ease;
        }
        
        .participant-btn:hover {
          background: #5a7d60;
          transform: translateY(-2px);
          box-shadow: 0 12px 24px rgba(107, 143, 113, 0.3);
        }
        
        .participant-image {
          position: relative;
        }
        
        .participant-image-box {
          background: linear-gradient(135deg, var(--eahl-accent) 0%, var(--eahl-sage) 100%);
          border-radius: 20px;
          padding: 40px;
          text-align: center;
        }
        
        .participant-image-box i {
          font-size: 4rem;
          color: rgba(255, 255, 255, 0.9);
          margin-bottom: 20px;
          display: block;
        }
        
        .participant-image-text {
          font-size: 1.1rem;
          font-weight: 500;
          color: #ffffff;
          line-height: 1.5;
        }
        
        .participant-image-text strong {
          display: block;
          font-size: 1.3rem;
          margin-bottom: 4px;
        }
        
        /* ===== VISIT SECTION ===== */
        .join-visit {
          background: var(--eahl-cream) !important;
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
          margin-bottom: 12px;
          display: block;
        }
        
        .visit-title {
          font-size: clamp(1.8rem, 3.5vw, 2.25rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 20px !important;
          letter-spacing: -0.02em;
        }
        
        .visit-intro {
          font-size: 1.05rem;
          color: var(--eahl-text-light);
          line-height: 1.7;
          margin-bottom: 36px;
        }
        
        .visit-intro strong {
          color: var(--eahl-navy);
          font-weight: 600;
        }
        
        .contact-details {
          display: flex;
          flex-direction: column;
          gap: 24px;
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
          background: rgba(74, 144, 164, 0.1);
          color: var(--eahl-accent);
          display: flex;
          align-items: center;
          justify-content: center;
          font-size: 1rem;
          flex-shrink: 0;
        }
        
        .contact-text {
          display: flex;
          flex-direction: column;
          gap: 4px;
        }
        
        .contact-label {
          font-size: 0.8rem;
          font-weight: 600;
          text-transform: uppercase;
          letter-spacing: 0.1em;
          color: var(--eahl-text-light);
        }
        
        .contact-value {
          font-size: 1.05rem;
          color: var(--eahl-navy);
        }
        
        .contact-value a {
          color: var(--eahl-navy) !important;
          text-decoration: none !important;
          transition: color 0.2s ease;
        }
        
        .contact-value a:hover {
          color: var(--eahl-accent) !important;
        }
        
        /* Map Card */
        .map-card {
          background: #ffffff;
          border: 1px solid #e5e7eb;
          border-radius: 20px;
          overflow: hidden;
        }
        
        .map-embed {
          width: 100%;
          height: 280px;
          border: none;
          display: block;
        }
        
        .map-footer {
          padding: 24px;
          display: flex;
          justify-content: space-between;
          align-items: center;
          gap: 16px;
          border-top: 1px solid #e5e7eb;
        }
        
        .map-address {
          font-size: 0.95rem;
          color: var(--eahl-text-light);
          line-height: 1.6;
        }
        
        .map-address strong {
          display: block;
          color: var(--eahl-navy);
          font-weight: 600;
          margin-bottom: 4px;
        }
        
        .directions-btn {
          display: inline-flex;
          align-items: center;
          gap: 8px;
          font-size: 0.9rem;
          font-weight: 600;
          color: var(--eahl-accent) !important;
          text-decoration: none !important;
          padding: 10px 20px;
          border: 1px solid var(--eahl-accent);
          border-radius: 100px;
          transition: all 0.2s ease;
          white-space: nowrap;
        }
        
        .directions-btn:hover {
          background: var(--eahl-accent);
          color: #ffffff !important;
        }
        
        /* ===== CONTACT FORM SECTION ===== */
        .join-contact-section {
          background: #ffffff !important;
        }
        
        .form-container {
          max-width: 600px;
          margin: 0 auto;
          text-align: center;
        }
        
        .form-title {
          font-size: clamp(1.8rem, 3.5vw, 2.25rem) !important;
          font-weight: 500 !important;
          color: var(--eahl-navy) !important;
          margin-bottom: 12px !important;
          letter-spacing: -0.02em;
        }
        
        .form-subtitle {
          font-size: 1.1rem;
          color: var(--eahl-text-light);
          margin-bottom: 40px;
        }
        
        .contact-form-card {
          background: var(--eahl-cream);
          border-radius: 20px;
          padding: 40px 36px;
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
        .form-textarea,
        .form-select {
          width: 100%;
          padding: 14px 18px;
          font-size: 1rem;
          border: 1px solid #e5e7eb;
          border-radius: 12px;
          background: #ffffff;
          transition: all 0.2s ease;
          font-family: 'Source Sans 3', sans-serif !important;
        }
        
        .form-input:focus,
        .form-textarea:focus,
        .form-select:focus {
          outline: none;
          border-color: var(--eahl-accent);
          box-shadow: 0 0 0 4px rgba(74, 144, 164, 0.1);
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
          color: #ffffff;
          background: var(--eahl-navy);
          border: none;
          border-radius: 100px;
          cursor: pointer;
          transition: all 0.3s ease;
          font-family: 'Source Sans 3', sans-serif !important;
        }
        
        .form-submit:hover {
          background: var(--eahl-accent);
          transform: translateY(-2px);
          box-shadow: 0 12px 24px rgba(74, 144, 164, 0.25);
        }
        
        /* ===== RESPONSIVE ===== */
        @media (max-width: 900px) {
          .join-grid {
            grid-template-columns: 1fr;
          }
          .participant-card {
            grid-template-columns: 1fr;
            padding: 32px;
          }
          .participant-image {
            order: -1;
          }
          .visit-container {
            grid-template-columns: 1fr;
            gap: 48px;
          }
          .visit-info { padding-right: 0; }
        }
        
        @media (max-width: 768px) {
          .join-card { padding: 28px 24px; }
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
          <span class="join-hero-badge">Now Recruiting</span>
          <h1 class="join-hero-title">
            Join Our <em>Team</em>
          </h1>
          <div class="join-hero-divider"></div>
          <p class="join-hero-subtitle">
            We're always looking for curious, motivated individuals to advance hearing science with us. Whether you're a student or a community member, there's a place for you here.
          </p>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["140px", "20px", "120px", "20px"]
      css_class: "join-page join-hero"

  # -----------------------------------------------------------------------------
  # 2. STUDENT OPPORTUNITIES
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="join-container">
          <div class="section-header">
            <span class="section-label">For Students</span>
            <h2 class="section-title">Research Opportunities</h2>
            <p class="section-desc">
              Whether you're an undergraduate exploring research or a graduate student seeking a PhD, we have a place for you.
            </p>
          </div>
          
          <div class="join-grid">
            <!-- PhD Students -->
            <div class="join-card" style="--card-accent: #4a90a4; --icon-bg: rgba(74, 144, 164, 0.12); --icon-color: #4a90a4;">
              <div class="join-card-header">
                <div class="join-card-icon">
                  <i class="fas fa-user-graduate"></i>
                </div>
                <div class="join-card-title-wrap">
                  <h3 class="join-card-title">PhD Students</h3>
                  <p class="join-card-subtitle">Speech & Hearing Science Program</p>
                </div>
              </div>
              <p class="join-card-desc">
                Seeking doctoral students interested in cochlear implant psychophysics, neural health assessment, or electrical stimulation optimization.
              </p>
              <ul class="join-card-list">
                <li>Full tuition waiver and competitive stipend</li>
                <li>Training in psychophysics and electrophysiology</li>
                <li>Mentorship in grant writing and publishing</li>
                <li>Conference travel funding</li>
                <li>Access to state-of-the-art CI research equipment</li>
              </ul>
              <div class="join-card-footer">
                <a href="mailto:niyaziarslan@southalabama.edu?subject=PhD%20Program%20Inquiry" class="join-card-link">
                  Inquire →
                </a>
              </div>
            </div>
            <!-- AuD Students -->
            <div class="join-card" style="--card-accent: #e07a5f; --icon-bg: rgba(224, 122, 95, 0.12); --icon-color: #e07a5f;">
              <div class="join-card-header">
                <div class="join-card-icon">
                  <i class="fas fa-stethoscope"></i>
                </div>
                <div class="join-card-title-wrap">
                  <h3 class="join-card-title">AuD Students</h3>
                  <p class="join-card-subtitle">Clinical Doctorate Program</p>
                </div>
              </div>
              <p class="join-card-desc">
                Opportunities for AuD students to gain research experience alongside clinical training. Specifically ideal for those considering research-focused careers.
              </p>
              <ul class="join-card-list">
                <li>Capstone/research project mentorship</li>
                <li>Hands-on experience with CI programming</li>
                <li>Exposure to translational research methods</li>
                <li>Flexible scheduling around clinical rotations</li>
                <li>Potential for conference presentations</li>
              </ul>
              <div class="join-card-footer">
                <a href="mailto:niyaziarslan@southalabama.edu?subject=AuD%20Research%20Opportunity" class="join-card-link">
                  Inquire →
                </a>
              </div>
            </div>
            <!-- Master's Students -->
            <div class="join-card" style="--card-accent: #6b8f71; --icon-bg: rgba(107, 143, 113, 0.12); --icon-color: #6b8f71;">
              <div class="join-card-header">
                <div class="join-card-icon">
                  <i class="fas fa-book-reader"></i>
                </div>
                <div class="join-card-title-wrap">
                  <h3 class="join-card-title">Master's Students</h3>
                  <p class="join-card-subtitle">Thesis-Track Opportunities</p>
                </div>
              </div>
              <p class="join-card-desc">
                MA/MS students in Speech-Language Pathology, Audiology, or related fields can complete thesis research in our lab.
              </p>
              <ul class="join-card-list">
                <li>Thesis project development and mentorship</li>
                <li>Training in research methodology</li>
                <li>Data collection and analysis experience</li>
                <li>Preparation for PhD programs or clinical careers</li>
                <li>Co-authorship opportunities</li>
              </ul>
              <div class="join-card-footer">
                <a href="mailto:niyaziarslan@southalabama.edu?subject=Master's%20Thesis%20Inquiry" class="join-card-link">
                  Inquire →
                </a>
              </div>
            </div>
            <!-- Undergraduate Students -->
            <div class="join-card" style="--card-accent: #d4a574; --icon-bg: rgba(212, 165, 116, 0.12); --icon-color: #d4a574;">
              <div class="join-card-header">
                <div class="join-card-icon">
                  <i class="fas fa-flask"></i>
                </div>
                <div class="join-card-title-wrap">
                  <h3 class="join-card-title">Undergraduate RAs</h3>
                  <p class="join-card-subtitle">Research Assistant Positions</p>
                </div>
              </div>
              <p class="join-card-desc">
                Gain hands-on research experience as an undergraduate. Ideal for students considering graduate school in audiology, SLP, or neuroscience.
              </p>
              <ul class="join-card-list">
                <li>Data collection with cochlear implant users</li>
                <li>Learn MATLAB, R, and signal processing basics</li>
                <li>Exposure to psychophysical testing methods</li>
                <li>Flexible hours around class schedules</li>
                <li>Strong letters of recommendation for grad school</li>
              </ul>
              <div class="join-card-footer">
                <span class="join-card-status status-recruiting">Recruiting</span>
                <a href="mailto:niyaziarslan@southalabama.edu?subject=Undergraduate%20RA%20Position" class="join-card-link">
                  Apply →
                </a>
              </div>
            </div>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "100px", "20px"]
      css_class: "join-page join-opportunities"

  # -----------------------------------------------------------------------------
  # 3. STUDY PARTICIPANTS
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div class="join-container">
          <div class="participant-card">
            <div class="participant-content">
              <h3>Participate in Our Research</h3>
              <p>
                Have a cochlear implant? We're looking for CI users of all experience levels to participate in our studies. Your involvement helps us understand how to improve hearing outcomes for everyone.
              </p>
              <div class="participant-benefits">
                <span class="participant-benefit">
                  <i class="fas fa-check"></i> Compensation for your time
                </span>
                <span class="participant-benefit">
                  <i class="fas fa-check"></i> Flexible scheduling
                </span>
                <span class="participant-benefit">
                  <i class="fas fa-check"></i> Free parking
                </span>
                <span class="participant-benefit">
                  <i class="fas fa-check"></i> All CI brands welcome
                </span>
              </div>
              <a href="mailto:niyaziarslan@southalabama.edu?subject=Study%20Participation%20Interest" class="participant-btn">
                Sign Up for Studies →
              </a>
            </div>
            <div class="participant-image">
              <div class="participant-image-box">
                <i class="fas fa-ear-listen"></i>
                <div class="participant-image-text">
                  <strong>Your Experience Matters</strong>
                  Help shape the future of cochlear implant technology
                </div>
              </div>
            </div>
          </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "20px", "100px", "20px"]
      css_class: "join-page join-participants"

  # -----------------------------------------------------------------------------
  # 4. VISIT THE LAB
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
  # 5. CONTACT FORM
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
                <input type="text" id="name" name="name" class="form-input" required placeholder="Jane Smith">
              </div>
              <div class="form-group">
                <label class="form-label" for="email">Email Address</label>
                <input type="email" id="email" name="email" class="form-input" required placeholder="jane@example.com">
              </div>
              <div class="form-group">
                <label class="form-label" for="interest">I'm interested in...</label>
                <select id="interest" name="interest" class="form-select">
                  <option value="">Select an option</option>
                  <option value="phd">PhD Program</option>
                  <option value="aud">AuD Research Opportunity</option>
                  <option value="masters">Master's Thesis</option>
                  <option value="undergrad">Undergraduate RA Position</option>
                  <option value="participant">Study Participation</option>
                  <option value="other">Other / General Inquiry</option>
                </select>
              </div>
              <div class="form-group">
                <label class="form-label" for="message">Message</label>
                <textarea id="message" name="message" class="form-textarea" required placeholder="Tell us about your background and interests..."></textarea>
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