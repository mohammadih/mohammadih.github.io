---
# Display name
title: Hossein Mohammadi

# Full name (for SEO)
first_name: Hossein
last_name: Mohammadi

# Status emoji
status:
  # icon: ☕️

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: Ph.D. Candidate and Graduate Research Assistant

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Mississippi State University
    url: https://www.msstate.edu/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:hmohammadi.phycom@gmail.com'
    label: Email
  - icon: envelope
    url: 'mailto:hm1125@msstate.edu'
    label: Academic Email
  - icon: brands/github
    url: https://github.com/mohammadih
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/hossein-mohammadi-a14722b3
  - icon: academicons/google-scholar
    url: https://scholar.google.com/citations?user=-XJ86EAAAAAJ&hl=en
  - icon: academicons/researchgate
    url: https://www.researchgate.net/profile/Hossein-Mohammadi-16

education:
  - area: Ph.D. Candidate in Electrical and Electronics Engineering
    institution: Mississippi State University
    date_start: 2021-05-01
    date_end: ''
    summary: |
      Minor in Computer Science.
  - area: M.Sc. in Electrical Engineering — Communication Systems
    institution: University of Tehran
    date_start: 2016-09-01
    date_end: 2019-09-30
    summary: |
      Thesis: _Self-Interference Management in In-Band Full-Duplex Systems_.
work:
  - position: Graduate Research Assistant
    company_name: Mississippi State University
    company_url: ''
    company_logo: ''
    date_start: 2021-01-01
    date_end: ''
    summary: |
      **NSF SWIFT-SAT / INTERACT — Learning-Based RFI Mitigation for Active–Passive Spectrum Coexistence** (2024–Present)
      - Designed a deep-reinforcement-learning (DDQN) spectrum-selection framework identifying interference-dominant 5G NR subbands for passive radiometer receivers operating in shared spectrum.
      - Developed neural successive-interference-cancellation modules — U-Net time–frequency masking and a two-stage MLP — to suppress structured 5G OFDM interference while preserving passive radiometric baselines.
      - Built end-to-end MATLAB/Python simulation and evaluation workflows (3GPP-compliant 5G NR waveform generation, Sionna CDL channel modeling, model training and baseline comparison).
      - First-authored the IEEE DySPAN 2025 paper on AI-assisted successive interference cancellation and two follow-on manuscripts extending the framework.

      **NSF Convergence Accelerator Track G — Combating Vulnerability and Unawareness in 5G Network Security** (2023–Present)
      - First-authored the IEEE MILCOM 2024 paper on defending 5G networks against jamming attacks with multipath communications.
      - Contributed to a three-path 5G Standalone architecture combining threshold secret sharing with path diversity for resilience against eavesdropping, jamming, and infrastructure failure.
      - Contributed to an error-pattern steganographic communication framework concealing covert data within standard 5G traffic, and to hardware-in-the-loop validation on a 5G Standalone COTS testbed (srsRAN, Open5GS, USRP B210).

      **O-RAN, Federated Learning, and 6G Network Management** (Dissertation Research, 2021–Present)
      - Developed SliceFed, a federated constrained multi-agent deep-reinforcement-learning framework (Lagrangian primal–dual PPO with federated averaging) for dynamic spectrum slicing with URLLC latency guarantees in dense 6G radio access networks (submitted to IEEE DySPAN 2026).
      - Evaluated reinforcement-learning schemes for trajectory optimization of aerial radio units in non-terrestrial 6G deployments (IEEE ICC 2023).
      - Co-authored studies on AI-driven fuzzing for vulnerability assessment of O-RAN traffic-steering algorithms and on auditable geographic fairness for multi-operator LEO spectrum sharing.

      **AI-Enabled Radio Transceivers and Nonlinear Receivers**
      - Developed AI-driven demodulation approaches for nonlinear receivers operating in shared spectrum with high-power blockers (IEEE WCNC 2022).
      - Co-authored a symbol-error-rate characterization of communication receivers under receiver nonlinearity (IEEE VTC-Spring 2020).
      - Investigated opportunities and challenges of artificial-neural-network architectures for radio transceivers (IEEE VTC-Fall 2021).
  - position: Graduate Researcher
    company_name: University of Tehran
    company_url: ''
    company_logo: ''
    date_start: 2016-01-01
    date_end: 2019-12-31
    summary: |
      - Investigated self-interference management in in-band full-duplex systems.
      - Compared modulation schemes and their performance.
      - Performed up/down-sampling, windowing, and power spectral density analysis.
      - Simulated adaptive beamforming methods.
      - Simulated STBC and MIMO systems.
      - Explored neural-network applications in wireless communication.

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Programming and Scientific Computing
    items:
      - name: Python (proficient)
      - name: MATLAB (proficient)
      - name: Bash
      - name: Linux
  - name: AI and Machine Learning
    items:
      - name: Deep learning
      - name: Multi-layer perceptrons
      - name: U-Net architectures
      - name: Deep reinforcement learning (DDQN, PPO)
      - name: Constrained MDPs
      - name: Federated learning
  - name: ML Frameworks
    items:
      - name: TensorFlow/Keras
      - name: PyTorch
      - name: Sionna
  - name: Wireless and Communication Systems
    items:
      - name: 5G NR
      - name: O-RAN/Open RAN
      - name: Network slicing
      - name: Wireless resource allocation
      - name: Non-terrestrial networks
      - name: Spectrum sharing
      - name: RF sensing and passive radiometry
      - name: Interference mitigation
      - name: Wireless security
      - name: MIMO, MU-MIMO, and massive MIMO
      - name: Millimeter-wave communications
      - name: Adaptive beamforming
      - name: Full-duplex communications
  - name: Signal Processing and Analysis
    items:
      - name: Digital and statistical signal processing
      - name: Information theory
      - name: STFT and PSD analysis
      - name: OFDM waveform analysis
      - name: Channel modeling (CDL)
      - name: Estimation theory
      - name: Adaptive filtering
      - name: Monte Carlo evaluation
  - name: Testbeds and Platforms
    items:
      - name: srsRAN
      - name: GNU Radio
      - name: USRP B210
      - name: MATLAB 5G Toolbox
      - name: Wireshark
      - name: POWDER wireless testbed
      - name: Hardware-in-the-loop 5G experimentation
  - name: Research and Documentation
    items:
      - name: LaTeX
      - name: Git/GitHub
      - name: Overleaf
      - name: IEEE manuscript preparation
      - name: Technical writing
      - name: Reproducible research

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: Selected Participant, CyberPowder Fellows Program
    date_start: '2026-01-01'
    date: '2026-01-01'
    awarder: University of Utah (NSF POWDER/PAWR wireless testbed)
  - title: Second Place, ECE Research Symposium
    date_start: '2025-01-01'
    date: '2025-01-01'
    awarder: Department of Electrical and Computer Engineering, Mississippi State University
  - title: Third Place, ECE Research Symposium
    date_start: '2024-01-01'
    date: '2024-01-01'
    awarder: Department of Electrical and Computer Engineering, Mississippi State University
  - title: Selected Participant, COLOSSEUM Open RAN Digital Twin Workshop
    date_start: '2023-01-01'
    date: '2023-01-01'
    awarder: Northeastern University
---

## About Me

**Wireless Communications and AI/ML Research — 5G/6G RAN, Dynamic Spectrum Sharing, and Machine Learning**

Hossein Mohammadi is a Ph.D. Candidate and Graduate Research Assistant in Electrical Engineering, with a minor in Computer Science, at Mississippi State University, working at the intersection of 5G/6G radio access networks, dynamic spectrum sharing, and machine learning. He has first-authored IEEE publications spanning VTC, WCNC, ICC, MILCOM, DySPAN, and CCNC, and contributes to two NSF-funded programs on active–passive spectrum coexistence and secure 5G communications. His work centers on designing deep-learning and reinforcement-learning methods for interference mitigation, spectrum selection, and network resource management, validated through system-level simulation and SDR-based 5G testbeds.
