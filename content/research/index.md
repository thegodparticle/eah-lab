---
title: Research Overview
date: "2026-01-01"

sections:
  # -----------------------------------------------------------------------------
  # 1. INTRO: Pure Editorial Text (No Glass)
  #    This sets a serious, academic tone immediately, contrasting with the Home page.
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        <div style="max-width: 800px; margin: 0 auto; text-align: center;">
          <h5 style="color: #007AFF; font-weight: 700; text-transform: uppercase; letter-spacing: 2px; margin-bottom: 20px; font-size: 0.9rem;">Our Methodology</h5>
          <h1 style="color: #1d1d1f; font-size: clamp(2.5rem, 5vw, 3.5rem); font-weight: 800; letter-spacing: -0.02em; line-height: 1.1; margin-bottom: 40px;">
            From Electrode to Cortex.
          </h1>
          <p style="font-size: clamp(1.2rem, 2vw, 1.5rem); color: #48484a; line-height: 1.6; font-weight: 400;">
            We do not just study the ear; we study the <strong>entire auditory pathway</strong>. By combining engineering, psychophysics, and neuroscience, we bridge the gap between artificial stimulation and natural perception.
          </p>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["120px", "0", "100px", "0"]
      background:
        color: "#ffffff"

  # -----------------------------------------------------------------------------
  # 2. PILLAR 1: COCHLEAR IMPLANTS (Left Aligned)
  #    Unique Design: Flat Left Edge + Blue Tech Border
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        <div style="
          background: rgba(28, 28, 30, 0.95);
          backdrop-filter: blur(40px);
          -webkit-backdrop-filter: blur(40px);
          padding: 60px;
          border-radius: 0 32px 32px 0; /* Flat edge on the left looks 'docked' */
          border-top: 4px solid #2997FF; /* Blue 'Tech' Accent */
          box-shadow: 20px 20px 60px rgba(0,0,0,0.4);
          max-width: 650px;
          margin-right: auto; /* Pushes block to the Left */
          text-align: left;">
          
          <h2 style="color: #FFFFFF; font-size: clamp(2rem, 4vw, 2.8rem); font-weight: 700; margin-bottom: 25px; line-height: 1.1;">
            Focused Neural <br> Stimulation
          </h2>
          
          <p style="font-size: 1.2rem; color: #E5E5EA; line-height: 1.7; font-weight: 400; margin-bottom: 30px;">
            Current implants spread current too broadly, muddying the sound. We are developing <strong>focused multipolar stimulation strategies</strong> that shape the electrical field to target specific neural populations.
          </p>
          
          <div style="border-top: 1px solid rgba(255,255,255,0.15); padding-top: 20px; display: flex; flex-wrap: wrap; gap: 20px; font-size: 0.9rem; color: #86868b; font-weight: 600; text-transform: uppercase; letter-spacing: 1px;">
            <span>Tripolar Stimulation</span>
            <span>Current Steering</span>
          </div>

        </div>
    design:
      columns: "1"
      spacing:
        padding: ["120px", "0", "120px", "0"]
      css_class: "fullscreen"
      # Image: Blue Electronics
      css_style: "background-image: url('https://images.unsplash.com/photo-1518770660439-4636190af475?q=80&w=2670&auto=format&fit=crop'); background-size: cover; background-position: center; background-attachment: fixed;"

  # -----------------------------------------------------------------------------
  # 3. PILLAR 2: PSYCHOACOUSTICS (Right Aligned)
  #    Unique Design: Flat Right Edge + Pink Perception Border
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        <div style="
          background: rgba(28, 28, 30, 0.95);
          backdrop-filter: blur(40px);
          -webkit-backdrop-filter: blur(40px);
          padding: 60px;
          border-radius: 32px 0 0 32px; /* Flat edge on the right */
          border-top: 4px solid #FF2D55; /* Pink 'Perception' Accent */
          box-shadow: -20px 20px 60px rgba(0,0,0,0.4);
          max-width: 650px;
          margin-left: auto; /* Pushes block to the Right */
          text-align: left;">
          
          <h2 style="color: #FFFFFF; font-size: clamp(2rem, 4vw, 2.8rem); font-weight: 700; margin-bottom: 25px; line-height: 1.1;">
            Quantifying the <br> Human Experience
          </h2>
          
          <p style="font-size: 1.2rem; color: #E5E5EA; line-height: 1.7; font-weight: 400; margin-bottom: 30px;">
            We don't just measure thresholds; we map the limits of resolution. Using rigorous <strong>psychophysical paradigms</strong> like spectral ripple discrimination, we quantify exactly how much detail an implant user can perceive.
          </p>

          <div style="border-top: 1px solid rgba(255,255,255,0.15); padding-top: 20px; display: flex; flex-wrap: wrap; gap: 20px; font-size: 0.9rem; color: #86868b; font-weight: 600; text-transform: uppercase; letter-spacing: 1px;">
            <span>Spectral Ripple</span>
            <span>Modulation Detection</span>
          </div>

        </div>
    design:
      columns: "1"
      spacing:
        padding: ["120px", "0", "120px", "0"]
      css_class: "fullscreen"
      # Image: Sound Studio
      css_style: "background-image: url('https://images.unsplash.com/photo-1484704849700-f032a568e944?q=80&w=2670&auto=format&fit=crop'); background-size: cover; background-position: center; background-attachment: fixed;"

  # -----------------------------------------------------------------------------
  # 4. PILLAR 3: NEUROSCIENCE (Left Aligned)
  #    Unique Design: Flat Left Edge + Violet Brain Border
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        <div style="
          background: rgba(28, 28, 30, 0.95);
          backdrop-filter: blur(40px);
          -webkit-backdrop-filter: blur(40px);
          padding: 60px;
          border-radius: 0 32px 32px 0;
          border-top: 4px solid #bf5af2; /* Violet 'Brain' Accent */
          box-shadow: 20px 20px 60px rgba(0,0,0,0.4);
          max-width: 650px;
          margin-right: auto;
          text-align: left;">
          
          <h2 style="color: #FFFFFF; font-size: clamp(2rem, 4vw, 2.8rem); font-weight: 700; margin-bottom: 25px; line-height: 1.1;">
            The Plastic Brain
          </h2>
          
          <p style="font-size: 1.2rem; color: #E5E5EA; line-height: 1.7; font-weight: 400; margin-bottom: 30px;">
            The ear is just the beginning. Using <strong>High-Density EEG</strong>, we track how the auditory cortex reorganizes itself after hearing loss. We aim to harness this plasticity to train the brain to hear better.
          </p>

          <div style="border-top: 1px solid rgba(255,255,255,0.15); padding-top: 20px; display: flex; flex-wrap: wrap; gap: 20px; font-size: 0.9rem; color: #86868b; font-weight: 600; text-transform: uppercase; letter-spacing: 1px;">
            <span>Cortical Potentials</span>
            <span>Neuroimaging</span>
          </div>

        </div>
    design:
      columns: "1"
      spacing:
        padding: ["120px", "0", "120px", "0"]
      css_class: "fullscreen"
      # Image: Neural Networks
      css_style: "background-image: url('https://images.unsplash.com/photo-1559757175-5b8d42d634d3?q=80&w=2670&auto=format&fit=crop'); background-size: cover; background-position: center; background-attachment: fixed;"

  # -----------------------------------------------------------------------------
  # 5. CTA: Simple 'Next Steps'
  #    Different from Home page to avoid repetition.
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
         <div style="text-align: center; max-width: 600px; margin: 0 auto;">
           <h3 style="margin-bottom: 20px; font-size: 2rem; font-weight: 800; color: #1d1d1f;">Dive Deeper</h3>
           <p style="color: #6e6e73; font-size: 1.2rem; margin-bottom: 40px;">See how we apply these methods in our published works.</p>
           
           <a href="../publication/" style="
             display: inline-block; 
             border: 2px solid #007AFF; 
             color: #007AFF; 
             padding: 15px 40px; 
             border-radius: 50px; 
             font-weight: 700; 
             text-decoration: none; 
             transition: all 0.3s ease;">
             View Publications &rarr;
           </a>
         </div>
    design:
      columns: "1"
      spacing:
        padding: ["120px", "0", "120px", "0"]
      background:
         color: "#ffffff"

type: landing
---