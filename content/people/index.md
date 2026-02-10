---
title: Meet the Team
date: "2026-01-01"

sections:
  # -----------------------------------------------------------------------------
  # 1. HERO: Glass Header
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        <div style="text-align: center; max-width: 800px; margin: 0 auto;">
        <div style="background: rgba(28, 28, 30, 0.85); backdrop-filter: blur(40px); -webkit-backdrop-filter: blur(40px); padding: 50px; border-radius: 32px; border: 1px solid rgba(255,255,255,0.15); box-shadow: 0 30px 60px rgba(0,0,0,0.3);">
        <h1 style="color: #FFFFFF; font-size: clamp(2.5rem, 5vw, 3.5rem); font-weight: 800; letter-spacing: -0.02em; line-height: 1.1; margin-bottom: 20px;">The Minds Behind <br> <span style="background: linear-gradient(135deg, #007AFF, #60efff); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">The Science</span></h1>
        <p style="font-size: 1.25rem; color: #E5E5EA; line-height: 1.6; font-weight: 400; margin-bottom: 0;">We are a multidisciplinary team of audiologists, engineers, and neuroscientists working together to solve the puzzles of perception.</p>
        </div>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["120px", "0", "120px", "0"]
      css_style: "background-image: url('https://images.unsplash.com/photo-1522071820081-009f0129c71c?q=80&w=2670&auto=format&fit=crop'); background-size: cover; background-position: center; background-attachment: fixed;"

  # -----------------------------------------------------------------------------
  # 2. PRINCIPAL INVESTIGATOR
  #    FIX: Changed columns to "2" to force the Image Card layout.
  # -----------------------------------------------------------------------------
  - block: people
    content:
      title: Faculty
      user_groups:
        - Faculty
      sort_ascending: true
      sort_by: Params.last_name
    design:
      show_interests: true
      show_role: true
      show_social: true
      columns: "2"          # <--- CRITICAL FIX: "2" forces the image to show!
      spacing:
        padding: ["80px", "0", "40px", "0"]
      background:
        color: "#ffffff"

  # -----------------------------------------------------------------------------
  # 3. RESEARCH TEAM
  # -----------------------------------------------------------------------------
  - block: people
    content:
      title: Team
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
      columns: "2"          # <--- Keeps the grid layout
      spacing:
        padding: ["40px", "0", "60px", "0"]
      background:
        color: "#F5F5F7"

  # -----------------------------------------------------------------------------
  # 4. ALUMNI
  # -----------------------------------------------------------------------------
  - block: people
    content:
      title: Alumni
      user_groups:
        - Alumni
      sort_ascending: false
      sort_by: Params.last_name
    design:
      show_interests: false
      show_role: true
      show_social: false
      columns: "2"          # <--- Keeps the compact grid layout
      spacing:
        padding: ["60px", "0", "80px", "0"]
      background:
        color: "#ffffff"

type: landing
---