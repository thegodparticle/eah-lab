---
title: Join Us
date: "2026-01-01"

sections:
  # -----------------------------------------------------------------------------
  # 1. HERO: The "Open Door" Welcome
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        <div style="text-align: center; max-width: 800px; margin: 0 auto;">
        <h1 style="color: #1d1d1f; font-size: clamp(2.5rem, 5vw, 3.5rem); font-weight: 800; letter-spacing: -0.02em; line-height: 1.1; margin-bottom: 20px;">Let's shape the future of hearing.</h1>
        <p style="font-size: clamp(1.2rem, 2vw, 1.4rem); color: #6e6e73; line-height: 1.6; font-weight: 400;">Whether you are a student ready to research or a community member ready to participate, we want to hear from you.</p>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "0", "60px", "0"]
      background:
        color: "#ffffff"

  # -----------------------------------------------------------------------------
  # 2. RECRUITMENT GRID (FIXED)
  #    Indentations removed to fix the "Raw Code" glitch.
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 40px; max-width: 1100px; margin: 0 auto;">
        <div style="background: #F5F5F7; border-radius: 32px; padding: 50px 40px; text-align: left; transition: transform 0.3s ease; border: 1px solid rgba(0,0,0,0.05);">
        <div style="width: 60px; height: 60px; background: #007AFF; border-radius: 16px; display: flex; align-items: center; justify-content: center; margin-bottom: 30px; box-shadow: 0 10px 20px rgba(0, 122, 255, 0.3);">
        <i class="fas fa-graduation-cap" style="color: #fff; font-size: 1.8rem;"></i>
        </div>
        <h3 style="color: #1d1d1f; font-size: 2rem; font-weight: 700; margin-bottom: 15px;">PhD Opportunities</h3>
        <p style="color: #48484a; font-size: 1.1rem; line-height: 1.6; margin-bottom: 30px;">Join a dynamic team at the intersection of engineering and neuroscience. We provide full funding, travel support, and hands-on mentorship.</p>
        <ul style="list-style: none; padding: 0; margin-bottom: 40px; color: #48484a;">
        <li style="margin-bottom: 10px;"><i class="fas fa-check-circle" style="color: #007AFF; margin-right: 10px;"></i> Full Tuition & Stipend</li>
        <li style="margin-bottom: 10px;"><i class="fas fa-check-circle" style="color: #007AFF; margin-right: 10px;"></i> Conference Travel Funding</li>
        <li style="margin-bottom: 10px;"><i class="fas fa-check-circle" style="color: #007AFF; margin-right: 10px;"></i> Advanced Signal Processing Training</li>
        </ul>
        <a href="mailto:narslan@southalabama.edu?subject=PhD%20Application%20Inquiry" style="display: inline-block; background: #007AFF; color: #fff; padding: 15px 30px; border-radius: 30px; font-weight: 600; text-decoration: none; box-shadow: 0 5px 15px rgba(0, 122, 255, 0.2);">Apply Now &rarr;</a>
        </div>
        <div style="background: #F5F5F7; border-radius: 32px; padding: 50px 40px; text-align: left; transition: transform 0.3s ease; border: 1px solid rgba(0,0,0,0.05);">
        <div style="width: 60px; height: 60px; background: #FF2D55; border-radius: 16px; display: flex; align-items: center; justify-content: center; margin-bottom: 30px; box-shadow: 0 10px 20px rgba(255, 45, 85, 0.3);">
        <i class="fas fa-users" style="color: #fff; font-size: 1.8rem;"></i>
        </div>
        <h3 style="color: #1d1d1f; font-size: 2rem; font-weight: 700; margin-bottom: 15px;">Study Participation</h3>
        <p style="color: #48484a; font-size: 1.1rem; line-height: 1.6; margin-bottom: 30px;">Do you have a cochlear implant? Help us improve hearing technology for everyone. Our studies are safe, non-invasive, and flexible.</p>
        <ul style="list-style: none; padding: 0; margin-bottom: 40px; color: #48484a;">
        <li style="margin-bottom: 10px;"><i class="fas fa-check-circle" style="color: #FF2D55; margin-right: 10px;"></i> Paid Compensation ($/hr)</li>
        <li style="margin-bottom: 10px;"><i class="fas fa-check-circle" style="color: #FF2D55; margin-right: 10px;"></i> Free Reserved Parking</li>
        <li style="margin-bottom: 10px;"><i class="fas fa-check-circle" style="color: #FF2D55; margin-right: 10px;"></i> Flexible Scheduling</li>
        </ul>
        <a href="mailto:narslan@southalabama.edu?subject=Study%20Participation" style="display: inline-block; background: #FF2D55; color: #fff; padding: 15px 30px; border-radius: 30px; font-weight: 600; text-decoration: none; box-shadow: 0 5px 15px rgba(255, 45, 85, 0.2);">Join a Study &rarr;</a>
        </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["0", "0", "100px", "0"]
      background:
        color: "#ffffff"

  # -----------------------------------------------------------------------------
  # 3. CONTACT INFO & FORM
  # -----------------------------------------------------------------------------
  - block: contact
    content:
      title: Visit the Lab
      text: |
        The **Electric & Acoustic Hearing Lab** is located in the **Health Sciences Building (HAHN)** at the University of South Alabama.
      email: niyaziarslan@southalabama.edu
      phone: '+1 (251) 460-6000'
      address:
        street: 5721 USA Drive North
        city: Mobile
        region: AL
        postcode: '36688'
        country: United States
        country_code: US
      coordinates:
        latitude: '30.6966'
        longitude: '-88.1786'
      directions: Health Sciences Building (HAHN), Department of Speech Pathology and Audiology.
      office_hours:
        - 'By Appointment'
      appointment_url: ''
      form:
        provider: netlify
        netlify:
          captcha: true
    design:
      columns: '2'
      spacing:
        padding: ["80px", "0", "100px", "0"]
      background:
        color: "#F5F5F7"
      css_class: "contact-section"

type: landing
---