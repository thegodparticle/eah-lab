---
title: Home
type: landing
date: "2026-01-01"

sections:
  # -----------------------------------------------------------------------------
  # 1. HERO: The "Hook"
  #    Design: Dark Glassmorphism on Neural Background
  # -----------------------------------------------------------------------------
  - block: hero
    content:
      title: "" # Handled via HTML below for styling control
      text: |
        <div style="
          background: rgba(28, 28, 30, 0.75);
          backdrop-filter: blur(50px) saturate(180%);
          -webkit-backdrop-filter: blur(50px) saturate(180%);
          padding: 60px 30px;
          border-radius: 32px;
          border: 1px solid rgba(255,255,255,0.12);
          box-shadow: 0 40px 100px rgba(0,0,0,0.5);
          max-width: 900px;
          margin: 0 auto;
          text-align: center;">

          <h1 style="
            color: #FFFFFF;
            font-size: clamp(2.5rem, 5vw, 4rem);
            font-weight: 800;
            letter-spacing: -0.03em;
            line-height: 1.1;
            margin-bottom: 25px;">
            Electric & Acoustic <br>
            <span style="
              background: linear-gradient(135deg, #2997FF 0%, #FF2D55 100%);
              -webkit-background-clip: text;
              -webkit-text-fill-color: transparent;
              filter: drop-shadow(0 0 30px rgba(41, 151, 255, 0.4));">
              Hearing Lab
            </span>
          </h1>

          <p style="
            font-size: clamp(1.1rem, 2vw, 1.5rem);
            color: #E5E5EA;
            line-height: 1.6;
            font-weight: 400;
            margin-bottom: 0;
            max-width: 750px;
            margin-left: auto;
            margin-right: auto;">
            Investigating the neural code of sound to improve auditory perception for cochlear implant users at the <strong style="color: #fff;">University of South Alabama</strong>.
          </p>

        </div>
    design:
      columns: "1"
      css_class: "hero-text-center"
      spacing:
        padding: ["120px", "0", "120px", "0"]
      # Background: High-res neural network concept
      css_style: "background-image: url('https://images.unsplash.com/photo-1655931546508-9f948f52e079?q=80&w=1740&auto=format&fit=crop'); background-size: cover; background-position: center; background-attachment: fixed;"

  # -----------------------------------------------------------------------------
  # 2. PILLARS: What We Do
  #    Design: Clean White Background for Visual relief/Contrast
  # -----------------------------------------------------------------------------
  - block: features
    id: research-pillars
    content:
      title: ""
      items:
        - name: Cochlear Implants
          description: Optimizing electrical stimulation strategies to restore natural hearing perception and pitch coding.
          icon: ear-listen
          icon_pack: fas
        - name: Psychoacoustics
          description: Quantifying auditory perception through rigorous behavioral testing, detection thresholds, and modeling.
          icon: wave-square
          icon_pack: fas
        - name: Auditory Neuroscience
          description: Mapping neural health, plasticity, and cortical reorganization using high-density EEG.
          icon: brain
          icon_pack: fas
    design:
      columns: "3"
      view: 1 # Icon on top (Centered)
      background:
        color: "#FFFFFF"
      spacing:
        padding: ["100px", "0", "100px", "0"]

  # -----------------------------------------------------------------------------
  # 3. MISSION: The "Cinematic" Moment
  #    Design: Dark Parallax with Animated Text
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        <div style="text-align: center; max-width: 900px; margin: 0 auto; position: relative; z-index: 2; padding: 0 20px;">

          <style>
            @keyframes shimmer {
              0% { background-position: 0% 50%; }
              50% { background-position: 100% 50%; }
              100% { background-position: 0% 50%; }
            }
            .gradient-text-anim {
              background: linear-gradient(270deg, #2997FF, #60efff, #FF2D55, #2997FF);
              background-size: 300% 300%;
              -webkit-background-clip: text;
              -webkit-text-fill-color: transparent;
              animation: shimmer 6s ease infinite;
              font-weight: 800;
            }
            .glass-pill {
              padding: 10px 20px;
              background: rgba(255,255,255,0.1);
              border: 1px solid rgba(255,255,255,0.25);
              border-radius: 100px;
              font-size: 0.95rem;
              color: #fff;
              backdrop-filter: blur(10px);
              -webkit-backdrop-filter: blur(10px);
              transition: transform 0.2s ease;
            }
            .glass-pill:hover {
              transform: translateY(-2px);
              background: rgba(255,255,255,0.2);
            }
          </style>

          <h2 style="color: #ffffff; font-size: clamp(2rem, 4vw, 3.2rem); line-height: 1.15; font-weight: 300; margin-bottom: 40px; letter-spacing: -0.02em;">
            Hearing is more than sound detection. <br>
            It is the <span class="gradient-text-anim">gateway to connection.</span>
          </h2>

          <div style="width: 80px; height: 4px; background: rgba(255,255,255,0.3); margin: 0 auto 40px auto; border-radius: 2px;"></div>

          <p style="font-size: clamp(1.1rem, 2vw, 1.35rem); color: rgba(255, 255, 255, 0.9); line-height: 1.7; font-weight: 400; max-width: 800px; margin: 0 auto;">
            By combining <span style="color: #fff; font-weight: 600;">computational modeling</span>, <span style="color: #fff; font-weight: 600;">psychophysics</span>, and <span style="color: #fff; font-weight: 600;">neuroimaging</span>, our lab seeks to bridge the critical gap between basic auditory science and clinical rehabilitation.
          </p>

          <div style="margin-top: 50px; display: flex; gap: 15px; flex-wrap: wrap; justify-content: center;">
            <span class="glass-pill">🚀 Open Science</span>
            <span class="glass-pill">📊 Reproducible Research</span>
            <span class="glass-pill">🎓 Mentorship</span>
          </div>

        </div>
    design:
      columns: "1"
      spacing:
        padding: ["140px", "0", "140px", "0"]
      css_class: "text-white"
      # Background: Darker overlay for better text readability
      css_style: "background-image: linear-gradient(rgba(0, 0, 0, 0.85), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1638866411782-5f59287c19e1?q=80&w=1820&auto=format&fit=crop'); background-size: cover; background-position: center; background-attachment: fixed; color: #ffffff;"

  # -----------------------------------------------------------------------------
  # 4. CTA: Get Involved
  #    Design: Light Glassmorphism
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <div style="
          background: rgba(255, 255, 255, 0.85);
          backdrop-filter: blur(40px) saturate(180%);
          -webkit-backdrop-filter: blur(40px) saturate(180%);
          border: 1px solid rgba(255,255,255,1);
          border-radius: 32px;
          padding: 80px 40px;
          max-width: 850px;
          margin: 0 auto;
          text-align: center;
          box-shadow: 0 20px 60px rgba(0,0,0,0.08);">

          <h2 style="color: #1d1d1f; font-size: clamp(2.2rem, 4vw, 3rem); font-weight: 800; letter-spacing: -0.03em; margin-bottom: 20px; line-height: 1.1;">
            Ready to shape the future?
          </h2>

          <p style="font-size: clamp(1.1rem, 2vw, 1.4rem); color: #48484a; line-height: 1.6; margin-bottom: 50px; font-weight: 500; max-width: 700px; margin-left: auto; margin-right: auto;">
            We are actively recruiting <strong style="color: #007AFF;">PhD Students</strong> and <strong style="color: #FF2D55;">Study Participants</strong> to join our research efforts.
          </p>

          <a href="./contact/" style="
            display: inline-block;
            background: linear-gradient(135deg, #007AFF 0%, #0056b3 100%);
            color: #ffffff;
            padding: 20px 50px;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: 600;
            letter-spacing: 0.5px;
            text-decoration: none;
            box-shadow: 0 10px 30px rgba(0, 122, 255, 0.25);
            transition: transform 0.2s ease, box-shadow 0.2s ease;">
            Get Involved &rarr;
          </a>

        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "0", "120px", "0"]
      css_class: "text-center"
      background:
        color: "#F5F5F7" # Light grey background to make the white card pop
---