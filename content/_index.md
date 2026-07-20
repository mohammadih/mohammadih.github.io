---
# Leave the homepage title empty to use the site title.
title: ""
date: 2026-07-20
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
        url: /uploads/hossein-mohammadi-cv.pdf
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
    id: stats
    content:
      text: |-
        **9** peer-reviewed papers · **6** IEEE venues · **2** NSF-funded research programs · Ph.D. Candidate since **2021**
    design:
      columns: '1'
      spacing:
        padding: [0, 0, 0, 0]

  - block: markdown
    id: research
    content:
      title: Research Focus
      text: |-
        My research examines how artificial intelligence and machine learning can improve the adaptability, reliability, and efficiency of wireless communication systems.

        - AI/ML-enabled wireless systems and radio transceivers
        - O-RAN, 5G/6G, network slicing, and resource management
        - Dynamic spectrum sharing and active–passive coexistence
        - RF-interference mitigation and passive radiometry
        - Secure and resilient 5G communications
        - Software-defined radio and 5G COTS testbeds
        - MIMO, beamforming, full-duplex, and interference-limited communications
    design:
      columns: '1'

  - block: markdown
    id: research-experience
    content:
      title: Research Experience Highlights
      text: |-
        ### Mississippi State University · Graduate Research Assistant · 2021–Present

        **NSF SWIFT-SAT / INTERACT — Learning-Based RFI Mitigation for Active–Passive Spectrum Coexistence** (2024–Present)
        - Designed a deep-reinforcement-learning (DDQN) spectrum-selection framework identifying interference-dominant 5G NR subbands for passive radiometer receivers operating in shared spectrum.
        - Developed neural successive-interference-cancellation modules — U-Net time–frequency masking and a two-stage MLP — to suppress structured 5G OFDM interference while preserving passive radiometric baselines.
        - First-authored the IEEE DySPAN 2025 paper on AI-assisted successive interference cancellation and two follow-on manuscripts extending the framework.

        **NSF Convergence Accelerator Track G — Combating Vulnerability and Unawareness in 5G Network Security** (2023–Present)
        - First-authored the IEEE MILCOM 2024 paper on defending 5G networks against jamming attacks with multipath communications.
        - Contributed to an error-pattern steganographic communication framework concealing covert data within standard 5G traffic, and to hardware-in-the-loop validation on a 5G Standalone COTS testbed (srsRAN, Open5GS, USRP B210).

        **O-RAN, Federated Learning, and 6G Network Management** (Dissertation Research, 2021–Present)
        - Developed SliceFed, a federated constrained multi-agent deep-reinforcement-learning framework (Lagrangian primal–dual PPO with federated averaging) for dynamic spectrum slicing with URLLC latency guarantees in dense 6G radio access networks (submitted to IEEE DySPAN 2026).
        - Evaluated reinforcement-learning schemes for trajectory optimization of aerial radio units in non-terrestrial 6G deployments (IEEE ICC 2023).

        **AI-Enabled Radio Transceivers and Nonlinear Receivers**
        - Developed AI-driven demodulation approaches for nonlinear receivers operating in shared spectrum with high-power blockers (IEEE WCNC 2022).
        - Investigated opportunities and challenges of artificial-neural-network architectures for radio transceivers (IEEE VTC-Fall 2021).

        ### University of Tehran · Graduate Researcher · 2016–2019

        - Developed self-interference management techniques for in-band full-duplex wireless systems (M.Sc. thesis).
        - Implemented and compared adaptive beamforming algorithms and simulated space–time block coding and MIMO systems.
        - Conducted signal-processing studies on resampling, windowing, and power-spectral-density estimation, and explored neural-network methods for wireless applications.

        [View all publications](/publications/) · [View full research experience](/experience/)
    design:
      columns: '1'

  - block: markdown
    id: capabilities
    content:
      title: Technical Capabilities
      text: |-
        **Programming and scientific computing:** Python (proficient) · MATLAB (proficient) · Bash · Linux

        **AI and machine learning:** Deep learning · Multi-layer perceptrons · U-Net architectures · Deep reinforcement learning (DDQN, PPO) · Constrained MDPs · Federated learning

        **ML frameworks:** TensorFlow/Keras · PyTorch · Sionna

        **Wireless and communication systems:** 5G NR · O-RAN/Open RAN · Network slicing · Wireless resource allocation · Non-terrestrial networks · Spectrum sharing · RF sensing and passive radiometry · Interference mitigation · Wireless security · MIMO, MU-MIMO, and massive MIMO · Millimeter-wave communications · Adaptive beamforming · Full-duplex communications

        **Signal processing and analysis:** Digital and statistical signal processing · Information theory · STFT and PSD analysis · OFDM waveform analysis · Channel modeling (CDL) · Estimation theory · Adaptive filtering · Monte Carlo evaluation

        **Testbeds and platforms:** srsRAN · GNU Radio · USRP B210 · MATLAB 5G Toolbox · Wireshark · POWDER wireless testbed · Hardware-in-the-loop 5G experimentation

        **Research and documentation:** LaTeX · Git/GitHub · Overleaf · IEEE manuscript preparation · Technical writing · Reproducible research
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
          url: /uploads/hossein-mohammadi-cv.pdf
          icon: document-arrow-down
        - text: Publications
          url: /publications/
          icon: book-open
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
