---
title: Home
type: landing
date: "2026-01-01"

sections:
  # -----------------------------------------------------------------------------
  # 1. HERO: The "Hook"
  #    ADDED: <style> block with @keyframes for entrance animations
  # -----------------------------------------------------------------------------
  - block: hero
    content:
      title: ""
      text: |
        <style>
          /* Define Animations */
          @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(40px); }
            to { opacity: 1; transform: translateY(0); }
          }
          @keyframes gradientFlow {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
          }
          
          /* Animation Classes */
          .anim-entry {
            opacity: 0; /* Hidden initially */
            animation: fadeInUp 0.8s cubic-bezier(0.2, 0.8, 0.2, 1) forwards;
          }
          .delay-1 { animation-delay: 0.2s; }
          .delay-2 { animation-delay: 0.4s; }
          
          /* Glass Container Hover */
          .hero-glass {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
          }
          .hero-glass:hover {
            transform: translateY(-5px);
            box-shadow: 0 50px 120px rgba(0,0,0,0.6) !important;
          }
        </style>

        <div class="hero-glass anim-entry" style="
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

          <h1 class="anim-entry delay-1" style="
            color: #FFFFFF;
            font-size: clamp(2.5rem, 5vw, 4rem);
            font-weight: 800;
            letter-spacing: -0.03em;
            line-height: 1.1;
            margin-bottom: 25px;">
            Electric & Acoustic <br>
            <span style="
              background: linear-gradient(270deg, #2997FF, #60efff, #FF2D55, #2997FF);
              background-size: 300% 300%;
              -webkit-background-clip: text;
              -webkit-text-fill-color: transparent;
              filter: drop-shadow(0 0 30px rgba(41, 151, 255, 0.4));
              animation: gradientFlow 6s ease infinite;">
              Hearing Lab
            </span>
          </h1>

          <p class="anim-entry delay-2" style="
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
      css_style: "background-image: url('https://images.unsplash.com/photo-1655931546508-9f948f52e079?q=80&w=1740&auto=format&fit=crop'); background-size: cover; background-position: center; background-attachment: fixed;"

  # -----------------------------------------------------------------------------
  # 2. PILLARS: What We Do
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        <style>
          /* Card Animations */
          .pillar-card {
            background: #ffffff;
            border-radius: 24px;
            padding: 50px 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275); /* Bouncy transition */
            border: 1px solid rgba(0,0,0,0.05);
            text-align: center;
            opacity: 0; /* Start hidden for animation */
            animation: fadeInUp 0.8s ease-out forwards;
          }
          
          /* Lift Effect */
          .pillar-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 25px 50px rgba(0,0,0,0.1);
            border-color: rgba(0,0,0,0);
          }
          
          /* Icon Container */
          .icon-box {
            width: 80px;
            height: 80px;
            border-radius: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 30px auto;
            font-size: 2rem;
            transition: transform 0.3s ease;
          }
          
          /* Icon Rotate on Hover */
          .pillar-card:hover .icon-box {
            transform: scale(1.1) rotate(5deg);
          }

          /* Staggered Delays for Entrance */
          .delay-100 { animation-delay: 0.2s; }
          .delay-200 { animation-delay: 0.4s; }
          .delay-300 { animation-delay: 0.6s; }
        </style>

        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 40px; max-width: 1200px; margin: 0 auto;">
          
          <div class="pillar-card delay-100">
            <div class="icon-box" style="background: rgba(0, 122, 255, 0.1); color: #007AFF;">
              <i class="fas fa-ear-listen"></i>
            </div>
            <h3 style="font-size: 1.5rem; font-weight: 700; color: #1d1d1f; margin-bottom: 15px;">Cochlear Implants</h3>
            <p style="font-size: 1.05rem; color: #6e6e73; line-height: 1.6;">
              Optimizing electrical stimulation strategies to restore natural hearing perception and pitch coding.
            </p>
          </div>

          <div class="pillar-card delay-200">
            <div class="icon-box" style="background: rgba(255, 45, 85, 0.1); color: #FF2D55;">
              <i class="fas fa-wave-square"></i>
            </div>
            <h3 style="font-size: 1.5rem; font-weight: 700; color: #1d1d1f; margin-bottom: 15px;">Psychoacoustics</h3>
            <p style="font-size: 1.05rem; color: #6e6e73; line-height: 1.6;">
              Quantifying auditory perception through rigorous behavioral testing, detection thresholds, and modeling.
            </p>
          </div>

          <div class="pillar-card delay-300">
            <div class="icon-box" style="background: rgba(175, 82, 222, 0.1); color: #AF52DE;">
              <i class="fas fa-brain"></i>
            </div>
            <h3 style="font-size: 1.5rem; font-weight: 700; color: #1d1d1f; margin-bottom: 15px;">Auditory Neuroscience</h3>
            <p style="font-size: 1.05rem; color: #6e6e73; line-height: 1.6;">
              Mapping neural health, plasticity, and cortical reorganization using high-density EEG.
            </p>
          </div>

        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "0", "100px", "0"]
      background:
        color: "#ffffff"
  # -----------------------------------------------------------------------------
  # 3. MISSION: The "Cinematic" Moment
  #    ADDED: Entrance animations to the text elements
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        <div style="text-align: center; max-width: 900px; margin: 0 auto; position: relative; z-index: 2; padding: 0 20px;">

          <style>
            .mission-anim { opacity: 0; animation: fadeInUp 1s ease-out forwards; }
          </style>

          <h2 class="mission-anim" style="color: #ffffff; font-size: clamp(2rem, 4vw, 3.2rem); line-height: 1.15; font-weight: 300; margin-bottom: 40px; letter-spacing: -0.02em;">
            Hearing is more than sound detection. <br>
            It is the <span class="gradient-text-anim">gateway to connection.</span>
          </h2>

          <div class="mission-anim delay-1" style="width: 80px; height: 4px; background: rgba(255,255,255,0.3); margin: 0 auto 40px auto; border-radius: 2px;"></div>

          <p class="mission-anim delay-2" style="font-size: clamp(1.1rem, 2vw, 1.35rem); color: rgba(255, 255, 255, 0.9); line-height: 1.7; font-weight: 400; max-width: 800px; margin: 0 auto;">
            By combining <span style="color: #fff; font-weight: 600;">computational modeling</span>, <span style="color: #fff; font-weight: 600;">psychophysics</span>, and <span style="color: #fff; font-weight: 600;">neuroimaging</span>, our lab seeks to bridge the critical gap between basic auditory science and clinical rehabilitation.
          </p>

          <div class="mission-anim delay-2" style="margin-top: 50px; display: flex; gap: 15px; flex-wrap: wrap; justify-content: center;">
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
      css_style: "background-image: linear-gradient(rgba(0, 0, 0, 0.85), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1638866411782-5f59287c19e1?q=80&w=1820&auto=format&fit=crop'); background-size: cover; background-position: center; background-attachment: fixed; color: #ffffff;"


# -----------------------------------------------------------------------------
  # 4. CTA: Get Involved (DYNAMIC UPGRADE)
  #    Added: Gentle floating card + Pulsing button + Staggered text entry
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        <style>
          /* 1. Define Animations */
          @keyframes float-ambient {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
          }
          @keyframes pulse-glow {
            0% { box-shadow: 0 10px 30px rgba(0, 122, 255, 0.25); }
            50% { box-shadow: 0 15px 50px rgba(0, 122, 255, 0.5); transform: scale(1.02); }
            100% { box-shadow: 0 10px 30px rgba(0, 122, 255, 0.25); }
          }
          @keyframes slideUpFade {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
          }

          /* 2. Apply Animations */
          .cta-card-dynamic {
            /* Gentle float makes it feel "alive" */
            animation: float-ambient 6s ease-in-out infinite; 
            /* Slide up entrance */
            animation: slideUpFade 1s cubic-bezier(0.2, 0.8, 0.2, 1) forwards; 
            opacity: 0; /* Hidden before animation starts */
          }

          .cta-btn-dynamic {
            /* Rhythmic pulse to grab attention */
            animation: pulse-glow 3s infinite ease-in-out;
          }
          
          /* Pause pulse on hover so the user feels control */
          .cta-btn-dynamic:hover {
            animation: none; 
            transform: scale(1.08) translateY(-3px) !important;
            box-shadow: 0 20px 60px rgba(0, 122, 255, 0.6) !important;
          }

          /* Text Staggering */
          .cta-content { opacity: 0; animation: slideUpFade 0.8s ease-out forwards; }
          .delay-1 { animation-delay: 0.2s; }
          .delay-2 { animation-delay: 0.4s; }
        </style>

        <div class="cta-card-dynamic" style="
          background: rgba(255, 255, 255, 0.9);
          backdrop-filter: blur(50px) saturate(180%);
          -webkit-backdrop-filter: blur(50px) saturate(180%);
          border: 1px solid rgba(255,255,255,1);
          border-radius: 40px;
          padding: 80px 40px;
          max-width: 900px;
          margin: 0 auto;
          text-align: center;
          box-shadow: 0 30px 80px rgba(0,0,0,0.08);">

          <h2 class="cta-content" style="
            color: #1d1d1f; 
            font-size: clamp(2.5rem, 4vw, 3.5rem); 
            font-weight: 800; 
            letter-spacing: -0.03em; 
            margin-bottom: 25px; 
            line-height: 1.1;">
            Ready to shape the future?
          </h2>

          <p class="cta-content delay-1" style="
            font-size: clamp(1.2rem, 2vw, 1.5rem); 
            color: #48484a; 
            line-height: 1.6; 
            margin-bottom: 50px; 
            font-weight: 500; 
            max-width: 750px; 
            margin-left: auto; 
            margin-right: auto;">
            We are actively recruiting <strong style="color: #007AFF;">PhD Students</strong> and <strong style="color: #FF2D55;">Study Participants</strong> to join our research efforts.
          </p>

          <a href="./contact/" class="cta-content delay-2 cta-btn-dynamic" style="
            display: inline-block;
            background: linear-gradient(135deg, #007AFF 0%, #0056b3 100%);
            color: #ffffff;
            padding: 22px 55px;
            border-radius: 50px;
            font-size: 1.2rem;
            font-weight: 700;
            letter-spacing: 0.5px;
            text-decoration: none;
            transition: all 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94);">
            Get Involved &rarr;
          </a>

        </div>
    design:
      columns: "1"
      spacing:
        padding: ["100px", "0", "140px", "0"]
      css_class: "text-center"
      background:
        color: "#F5F5F7"
---