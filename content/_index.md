---
# Leave the homepage title empty to use the site title.
title: ""
date: 2026-07-18
type: landing
summary: Personal research website of Hossein Mohammadi, focused on AI-assisted O-RAN, 6G non-terrestrial networks, wireless resource management, and intelligent radio systems.

design:
  spacing: "5rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: /uploads/Hossein_Summarized_CV.pdf
    design:
      css_class: dark
      background:
        color: '#0f172a'
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 0.8
          size: cover
          position: center
          parallax: false

  - block: markdown
    id: research
    content:
      title: Research Focus
      text: |-
        My research examines how artificial intelligence and machine learning can improve the adaptability, reliability, and efficiency of wireless communication systems.

        - AI/ML for wireless communication systems and radio transceivers
        - O-RAN and AI-assisted network slicing
        - 6G non-terrestrial networks
        - Federated learning and distributed resource management
        - Deep reinforcement learning for wireless optimization
        - MIMO, multiuser MIMO, and massive MIMO
        - Spectrum coexistence and interference mitigation
        - Millimeter-wave communication and wireless security
    design:
      columns: '1'

  - block: markdown
    id: research-experience
    content:
      title: Research Experience Highlights
      text: |-
        ### Mississippi State University · Graduate Research Assistant · 2021–Present

        - AI-assisted network and resource management, federated learning, and network slicing for O-RAN and 6G systems
        - AI-driven demodulation and MLP-based self-interference mitigation under receiver nonlinearities and high-power blockers
        - Reinforcement-learning-based aerial radio-unit trajectory analysis and DRL-based RFI mitigation for passive radiometry
        - 5G security experimentation using multipath communication and srsRAN

        ### University of Tehran · Graduate Researcher · 2016–2019

        - In-band full-duplex self-interference management and modulation-performance analysis
        - Signal-processing studies involving sampling, windowing, power spectral density, adaptive beamforming, STBC, and MIMO simulation
        - Neural-network applications in wireless communication

        [View full research experience](/experience/)
    design:
      columns: '1'

  - block: markdown
    id: capabilities
    content:
      title: Technical Capabilities
      text: |-
        **Programming:** Python · MATLAB · C++

        **AI and machine learning:** Machine learning · Deep learning · Multi-layer perceptrons · Deep reinforcement learning · Federated learning

        **Wireless and communication systems:** O-RAN · Network slicing · MIMO and massive MIMO · Adaptive beamforming · Signal processing · Spectrum coexistence · Interference mitigation · Wireless resource allocation

        **SDR and networking tools:** srsRAN · GNU Radio · Wireshark

        **Scientific and documentation tools:** LaTeX · Git · Linux · Adobe Illustrator · Adobe Lightroom · Adobe Photoshop
    design:
      columns: '1'

  - block: resume-awards
    id: awards
    content:
      title: Selected Awards and Distinctions
      username: admin
    design:
      date_format: '2006'

  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |-
        ### Graduate Teaching Assistant · University of Tehran

        **Random Variables and Stochastic Processes**

        Led weekly instructional sessions and prepared problem sets to support student learning.

        [View teaching experience](/teaching/)
    design:
      columns: '1'

  - block: markdown
    id: contact
    content:
      title: Contact and CV
      text: |-
        For research and professional inquiries, contact me at [hmohammadi.phycom@gmail.com](mailto:hmohammadi.phycom@gmail.com). Academic correspondence may also be sent to [hm1125@msstate.edu](mailto:hm1125@msstate.edu).
    design:
      columns: '1'
      spacing:
        padding: [0, 0, 0, 0]

  - block: cta-button-list
    content:
      buttons:
        - text: Download CV
          url: /uploads/Hossein_Summarized_CV.pdf
          icon: document-arrow-down
        - text: Google Scholar
          url: https://scholar.google.com/citations?user=-XJ86EAAAAAJ&hl=en
          icon: brands/google-scholar
        - text: LinkedIn
          url: https://www.linkedin.com/in/hossein-mohammadi-a14722b3
          icon: brands/linkedin
        - text: Email
          url: mailto:hmohammadi.phycom@gmail.com
          icon: envelope
    design:
      spacing:
        padding: [0, 0, 0, 0]
---
