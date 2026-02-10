---
date: "2026-01-01"
sections:
  # -----------------------------------------------------------------------------
  # 1. HERO: The "Hook"
  #    Using the 3D Cochlea image. I added a "Frost" overlay so your dark text 
  #    is easy to read on top of the scientific illustration.
  # -----------------------------------------------------------------------------
  - block: hero
    content:
      title: |
        Unlocking the Neural
        Code of Hearing
      text: |
        <br>
        
        The **Electric & Acoustic Hearing Lab** at the University of South Alabama investigates how the brain processes sound to improve auditory perception for cochlear implant users.
        
      image:
        filename: ""
    design:
      columns: "1"
      spacing:
        padding: ["140px", "0", "140px", "0"]
      css_class: "hero-text-center"
      # Image: 3D Cochlea/Inner Ear
      css_style: "background-image: linear-gradient(rgba(255, 255, 255, 0.4), rgba(255, 255, 255, 0.7)), url('https://images.unsplash.com/photo-1655931546508-9f948f52e079?q=80&w=1740&auto=format&fit=crop'); background-size: cover; background-position: center; background-attachment: fixed;"

  # -----------------------------------------------------------------------------
  # 2. PILLARS: What We Do
  #    Clean white background to contrast with the images above and below.
  # -----------------------------------------------------------------------------
  - block: features
    id: research-pillars
    content:
      title: Core Research Areas
      subtitle: ""
      items:
        - name: Cochlear Implants
          description: Optimizing electrical stimulation strategies to restore natural hearing perception.
          icon: ear-listen
          icon_pack: fas
        - name: Psychoacoustics
          description: Quantifying auditory perception through rigorous behavioral testing and modeling.
          icon: wave-square
          icon_pack: fas
        - name: Auditory Neuroscience
          description: Mapping neural health and plasticity using EEG and electrophysiology.
          icon: brain
          icon_pack: fas
    design:
      columns: "3"
      view: 1          # Icon on top (Centered)
      background:
        color: "#ffffff"

  # -----------------------------------------------------------------------------
  # 3. MISSION: The "Cinematic" Moment
  #    Using the Dark Neural Waves image. The text is forced white to pop against it.
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        We believe that **hearing is more than just sound detection**—it is the gateway to communication and connection. 
        
        By combining computational modeling, psychophysics, and neuroimaging, our lab seeks to bridge the gap between **basic auditory science** and **clinical rehabilitation**. We are dedicated to open science, reproducible research, and training the next generation of auditory scientists.
    design:
      columns: "2"
      spacing:
        padding: ["100px", "0", "100px", "0"]
      css_class: "text-white"
      # FIX: Changed 'color: black' to 'color: #ffffff' and adjusted gradient for better contrast
      css_style: "background-image: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.3)), url('https://images.unsplash.com/photo-1638866411782-5f59287c19e1?q=80&w=1820&auto=format&fit=crop'); background-size: cover; background-position: center; background-attachment: fixed; color: #ffffff;"

  # -----------------------------------------------------------------------------
  # 4. CTA: Simple & Direct
  # -----------------------------------------------------------------------------
  - block: markdown
    content:
      text: |
        ### Interested in joining the lab?
        
        We are actively recruiting PhD students and participants.
        
        <br>
        
        [Contact Us →](./contact/)
    design:
      columns: "1"
      spacing:
        padding: ["80px", "0", "80px", "0"]
      css_class: "text-center"
      background:
        color: "#ffffff"

title: Home
type: landing
---