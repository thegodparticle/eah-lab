---
# Display name
title: Niyazi Arslan, PhD

# Full name (for SEO)
first_name: Niyazi 
last_name: Arslan

# Is this the primary user of the site?
superuser: true

# Role/Position
role: Assistant Professor & Lab Director

# Organizations/Affiliations
organizations:
  - name: University of South Alabama
    url: 'https://www.southalabama.edu/'

# Short bio (displayed in user profile at bottom of posts)
bio: Understanding variability in cochlear implant outcomes through neural health assessment and personalized stimulation strategies.

# Education (Hugo will display these automatically)
education:
  courses:
    - course: PhD in Speech and Hearing Science
      institution: Arizona State University
      year: 2025
    - course: MSc in Audiology and Speech Disorders
      institution: Marmara University, Istanbul
      year: 2019
    - course: BSc in Audiology
      institution: Bezmialem Vakif University, Istanbul
      year: 2017

# Social/Academic Links
social:
  - icon: envelope
    icon_pack: fas
    link: mailto:narslan@southalabama.edu
    label: Email
    display:
      header: false
  - icon: globe
    icon_pack: fas
    link: https://niyaziarslan.com
    label: Personal Website
    display:
      header: false
  - icon: google-scholar
    icon_pack: ai
    link: https://scholar.google.com/citations?user=cTzzqvMAAAAJ&hl=en
    label: Google Scholar
    display:
      header: false
  - icon: orcid
    icon_pack: ai
    link: https://orcid.org/0000-0000-0000-0000
    label: ORCID
    display:
      header: false
  - icon: researchgate
    icon_pack: ai
    link: https://www.researchgate.net/profile/Niyazi-Arslan
    label: ResearchGate
  - icon: twitter
    icon_pack: fab
    link: https://twitter.com/niyazioarslan
    label: Twitter/X
  - icon: linkedin
    icon_pack: fab
    link: https://www.linkedin.com/in/niyazi-arslan/
    label: LinkedIn

# Highlight the author in author lists?
highlight_name: true

# User groups (for team page organization)
user_groups:
  - Faculty
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;1,400&family=Source+Sans+3:wght@300;400;500;600&display=swap');

:root {
  --eahl-navy: #0a1628;
  --eahl-cream: #faf8f5;
  --eahl-accent: #4a90a4;
  --eahl-coral: #e07a5f;
  --eahl-sage: #6b8f71;
  --eahl-text: #374151;
  --eahl-text-light: #6b7280;
  --eahl-border: #e5e7eb;
}

/* ===== OVERRIDE HUGO PROFILE STYLES ===== */
.article-container { max-width: 900px !important; }

article.article,
.profile-page {
  font-family: 'Source Sans 3', -apple-system, sans-serif !important;
}

article.article h1,
article.article h2,
article.article h3,
.profile-page h1,
.profile-page h2,
.profile-page h3 {
  font-family: 'Playfair Display', Georgia, serif !important;
}

/* ===== PROFILE BIO CONTAINER ===== */
.bio-container {
  margin: 2.5rem 0;
}

/* ===== SECTION HEADERS ===== */
.bio-section {
  margin-top: 3rem;
}

.bio-section-title {
  font-family: 'Playfair Display', Georgia, serif !important;
  font-size: 1.35rem !important;
  font-weight: 500 !important;
  color: var(--eahl-navy) !important;
  margin-bottom: 1.25rem !important;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid var(--eahl-coral);
  display: inline-block;
}

/* ===== MISSION BOX ===== */
.bio-mission {
  background: var(--eahl-cream);
  border-left: 4px solid var(--eahl-accent);
  border-radius: 0 16px 16px 0;
  padding: 28px 32px;
  margin: 2rem 0;
}

.bio-mission-label {
  font-size: 0.75rem;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: var(--eahl-accent);
  margin-bottom: 8px;
  display: block;
}

.bio-mission-text {
  font-size: 1.15rem;
  color: var(--eahl-navy);
  line-height: 1.7;
  margin: 0;
}

/* ===== INTRO TEXT ===== */
.bio-intro {
  font-size: 1.1rem;
  color: var(--eahl-text);
  line-height: 1.8;
  margin-bottom: 1.5rem;
}

.bio-intro strong {
  color: var(--eahl-navy);
}

/* ===== RESEARCH AIMS LIST ===== */
.bio-aims {
  list-style: none;
  padding: 0;
  margin: 1.5rem 0;
}

.bio-aims li {
  position: relative;
  padding-left: 28px;
  margin-bottom: 12px;
  font-size: 1.05rem;
  color: var(--eahl-text);
  line-height: 1.65;
}

.bio-aims li::before {
  content: '';
  position: absolute;
  left: 0;
  top: 8px;
  width: 8px;
  height: 8px;
  background: var(--eahl-accent);
  border-radius: 50%;
}

/* ===== RESEARCH FOCUS CARDS ===== */
.bio-focus-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 20px;
  margin: 1.5rem 0;
}

.bio-focus-card {
  background: #ffffff;
  border: 1px solid var(--eahl-border);
  border-radius: 16px;
  padding: 28px 24px;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
}

.bio-focus-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: var(--card-accent);
}

.bio-focus-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 16px 32px rgba(10, 22, 40, 0.08);
  border-color: transparent;
}

.bio-focus-icon {
  width: 48px;
  height: 48px;
  border-radius: 12px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.3rem;
  margin-bottom: 16px;
  background: var(--icon-bg);
  color: var(--icon-color);
}

.bio-focus-title {
  font-family: 'Playfair Display', Georgia, serif !important;
  font-size: 1.1rem !important;
  font-weight: 500 !important;
  color: var(--eahl-navy) !important;
  margin: 0 0 8px 0 !important;
}

.bio-focus-desc {
  font-size: 0.95rem;
  color: var(--eahl-text-light);
  line-height: 1.6;
  margin: 0;
}

/* ===== VALUES / OPEN SCIENCE ===== */
.bio-values {
  background: var(--eahl-cream);
  border-radius: 16px;
  padding: 32px;
  margin: 1.5rem 0;
}

.bio-values-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 24px;
}

.bio-value-item {
  display: flex;
  align-items: flex-start;
  gap: 12px;
}

.bio-value-icon {
  width: 40px;
  height: 40px;
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1rem;
  flex-shrink: 0;
  background: #ffffff;
  color: var(--eahl-accent);
}

.bio-value-text {
  flex: 1;
}

.bio-value-title {
  font-size: 0.95rem;
  font-weight: 600;
  color: var(--eahl-navy);
  margin-bottom: 2px;
}

.bio-value-desc {
  font-size: 0.85rem;
  color: var(--eahl-text-light);
  line-height: 1.5;
}

/* ===== QUOTE ===== */
.bio-quote {
  background: var(--eahl-navy);
  border-radius: 16px;
  padding: 32px 36px;
  margin: 2rem 0;
  position: relative;
}

.bio-quote::before {
  content: '"';
  position: absolute;
  top: 16px;
  left: 24px;
  font-family: 'Playfair Display', Georgia, serif;
  font-size: 4rem;
  color: rgba(255, 255, 255, 0.1);
  line-height: 1;
}

.bio-quote p {
  font-family: 'Playfair Display', Georgia, serif;
  font-size: 1.15rem;
  font-style: italic;
  color: rgba(255, 255, 255, 0.9);
  line-height: 1.7;
  margin: 0;
  position: relative;
  z-index: 1;
}

/* ===== PERSONAL SITE LINK ===== */
.bio-personal-site {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  font-size: 0.95rem;
  font-weight: 500;
  color: var(--eahl-accent) !important;
  text-decoration: none !important;
  padding: 10px 20px;
  background: rgba(74, 144, 164, 0.08);
  border: 1px solid rgba(74, 144, 164, 0.2);
  border-radius: 100px;
  transition: all 0.2s ease;
  margin-top: 1rem;
}

.bio-personal-site:hover {
  background: var(--eahl-accent);
  color: #ffffff !important;
  border-color: var(--eahl-accent);
}

/* ===== RESPONSIVE ===== */
@media (max-width: 768px) {
  .bio-focus-grid { grid-template-columns: 1fr; }
  .bio-values { padding: 24px 20px; }
  .bio-quote { padding: 28px 24px; }
}
</style>

<div class="bio-container">

**Niyazi  Arslan** is an Assistant Professor in the Department of Speech Pathology and Audiology at the University of South Alabama and founding director of the **Electric & Acoustic Hearing Lab**.

<a href="https://niyaziarslan.com" target="_blank" class="bio-personal-site">
  <i class="fas fa-globe"></i> Visit Personal Website
</a>

<div class="bio-mission">
  <span class="bio-mission-label">The Central Question</span>
  <p class="bio-mission-text">Why do two patients with the same cochlear implant, implanted by the same surgeon, have vastly different outcomes? Our lab seeks to understand the neural and technical factors that drive this variability—and translate that knowledge into personalized clinical solutions.</p>
</div>

<p class="bio-intro">
Dr. Arslan's research focuses on the role of <strong>auditory nerve condition</strong> in cochlear implant efficacy. His work investigates how patterns of neural degeneration—from myelin sheath thinning to peripheral axon loss—affect both the absolute properties and relative changes in psychophysical and electrophysiological responses to electrical stimulation.
</p>

<p class="bio-intro">
By combining <strong>psychophysical methods</strong>, <strong>electrophysiology</strong>, and <strong>computational approaches</strong>, the lab aims to:
</p>

<ul class="bio-aims">
  <li>Develop reliable, objective measures of neural health that can be assessed clinically</li>
  <li>Understand how site-specific neural degeneration limits pitch perception and spectral resolution</li>
  <li>Design personalized stimulation strategies matched to each patient's neural condition</li>
  <li>Translate research findings into improved clinical fitting procedures</li>
</ul>

<div class="bio-section">
  <h3 class="bio-section-title">Research Focus Areas</h3>
  
  <div class="bio-focus-grid">
    <div class="bio-focus-card" style="--card-accent: #4a90a4; --icon-bg: rgba(74, 144, 164, 0.12); --icon-color: #4a90a4;">
      <div class="bio-focus-icon">
        <i class="fas fa-heartbeat"></i>
      </div>
      <h4 class="bio-focus-title">Neural Health Assessment</h4>
      <p class="bio-focus-desc">Developing and validating measures to infer auditory nerve survival patterns from psychophysical and electrophysiological responses in CI users.</p>
    </div>
    <div class="bio-focus-card" style="--card-accent: #e07a5f; --icon-bg: rgba(224, 122, 95, 0.12); --icon-color: #e07a5f;">
      <div class="bio-focus-icon">
        <i class="fas fa-sliders-h"></i>
      </div>
      <h4 class="bio-focus-title">Personalized Stimulation</h4>
      <p class="bio-focus-desc">Testing how stimulation parameters—including polarity, pulse shape, and current focusing—can be optimized based on local neural condition.</p>
    </div>
    <div class="bio-focus-card" style="--card-accent: #6b8f71; --icon-bg: rgba(107, 143, 113, 0.12); --icon-color: #6b8f71;">
      <div class="bio-focus-icon">
        <i class="fas fa-music"></i>
      </div>
      <h4 class="bio-focus-title">Pitch & Spectral Perception</h4>
      <p class="bio-focus-desc">Investigating the perceptual limits of place-pitch sensitivity and how neural health constrains spectral resolution in electrical hearing.</p>
    </div>
  </div>
</div>

<div class="bio-section">
  <h3 class="bio-section-title">Lab Values</h3>
  
  <div class="bio-values">
    <div class="bio-values-grid">
      <div class="bio-value-item">
        <div class="bio-value-icon">
          <i class="fas fa-flask"></i>
        </div>
        <div class="bio-value-text">
          <div class="bio-value-title">Translational Focus</div>
          <div class="bio-value-desc">Research that moves from bench to clinic</div>
        </div>
      </div>  
      <div class="bio-value-item">
        <div class="bio-value-icon">
          <i class="fas fa-users"></i>
        </div>
        <div class="bio-value-text">
          <div class="bio-value-title">Mentorship</div>
          <div class="bio-value-desc">Training the next generation of hearing scientists</div>
        </div>
      </div>   
      <div class="bio-value-item">
        <div class="bio-value-icon">
          <i class="fas fa-check-double"></i>
        </div>
        <div class="bio-value-text">
          <div class="bio-value-title">Rigor</div>
          <div class="bio-value-desc">Transparent methods and reproducible results</div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="bio-quote">
  <p>The key to improving cochlear implant outcomes may lie not in building better devices, but in understanding and adapting to each patient's unique auditory neurobiology.</p>
</div>

</div>