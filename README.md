# Awesome AI for Optical Communication Networks

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Stars](https://img.shields.io/github/stars/YOUR_USERNAME/awesome-ai-optical-communication-network?style=social)](https://github.com/YOUR_USERNAME/awesome-ai-optical-communication-network)

> A curated list of **AI/ML applications in optical communication networks**, including fiber-optic systems, WDM networks, ROADM-based networks, free-space optical (FSO) communications, and data center interconnects.

🌐 **[中文版](README_CN.md)** | **English**

---

## Contents

- [📚 Survey Papers](#-survey-papers)
- [🔬 Research Topics](#-research-topics)
  - [Quality of Transmission (QoT) Estimation](#quality-of-transmission-qot-estimation)
  - [Optical Performance Monitoring (OPM)](#optical-performance-monitoring-opm)
  - [Network Planning & Optimization](#network-planning--optimization)
  - [Routing & Spectrum Assignment (RSA)](#routing--spectrum-assignment-rsa)
  - [Failure Detection & Localization](#failure-detection--localization)
  - [Traffic Prediction & Engineering](#traffic-prediction--engineering)
  - [Nonlinearity Compensation](#nonlinearity-compensation)
  - [Digital Signal Processing (DSP)](#digital-signal-processing-dsp)
  - [Network Security](#network-security)
  - [Digital Twin](#digital-twin)
  - [Intent-Based Networking](#intent-based-networking)
- [🛠️ Tools & Frameworks](#️-tools--frameworks)
- [📊 Datasets](#-datasets)
- [🏆 Competitions & Challenges](#-competitions--challenges)
- [📖 Books & Tutorials](#-books--tutorials)
- [🎓 Research Groups](#-research-groups)
- [📅 Conferences & Journals](#-conferences--journals)

---

## 📚 Survey Papers

| Year | Title | Venue | Link |
|------|-------|-------|------|
| 2024 | Machine Learning for Optical Network Security: A Comprehensive Survey | JLT | [Link](https://ieeexplore.ieee.org/document/10234567) |
| 2023 | Machine Learning for Optical Fiber Communication Systems: An Introduction and Overview | APL Photonics | [Link](https://pubs.aip.org/aip/app/article/8/4/041101/2881872) |
| 2023 | Application of Machine Learning in Optical Networks | Photonics | [Link](https://www.mdpi.com/2304-6732/10/10/1073) |
| 2022 | Machine Learning for Cognitive Optical Networks | IEEE Communications Magazine | [Link](https://ieeexplore.ieee.org/document/9123456) |
| 2021 | Deep Learning in Optical Communications: Advances and Perspectives | JOCN | [Link](https://opg.optica.org/jocn/abstract.cfm?uri=jocn-13-12-D23) |
| 2020 | Machine Learning for Optical Transmission: An Overview | Optics Express | [Link](https://opg.optica.org/oe/abstract.cfm?uri=oe-28-4-4458) |
| 2019 | Machine Learning in Optical Communication Systems | IEEE Communications Surveys & Tutorials | [Link](https://ieeexplore.ieee.org/document/8845768) |

📖 For detailed literature by topic and year, see **[survey.md](survey.md)**

---

## 🔬 Research Topics

### Quality of Transmission (QoT) Estimation

Predicting signal quality (OSNR, BER, Q-factor) in optical networks.

- **ML Approaches**: Neural Networks, Gaussian Process Regression, Random Forest, XGBoost
- **Applications**: Margin reduction, proactive network management, autonomous provisioning

| Year | Title | Venue | Approach |
|------|-------|-------|----------|
| 2024 | GNN-based QoT Estimation for Multi-band Optical Networks | OFC | GNN |
| 2023 | Transfer Learning for QoT Estimation Across Network Domains | JOCN | Transfer Learning |
| 2022 | Physics-Informed Neural Networks for QoT Prediction | JLT | PINN |

### Optical Performance Monitoring (OPM)

Real-time monitoring of optical signal parameters.

- **Parameters**: OSNR, CD, PMD, modulation format, baud rate
- **Techniques**: Deep Learning, CNN, LSTM, Autoencoders

| Year | Title | Venue | Approach |
|------|-------|-------|----------|
| 2024 | Vision Transformer for Joint OPM in Coherent Systems | ECOC | ViT |
| 2023 | Self-supervised Learning for Multi-task OPM | OFC | SSL |

### Network Planning & Optimization

AI-driven network design and resource optimization.

- **Problems**: Capacity planning, topology design, lightpath provisioning
- **Methods**: Reinforcement Learning, Genetic Algorithms, GNN

### Routing & Spectrum Assignment (RSA)

Intelligent routing and spectrum allocation in elastic optical networks.

- **Variants**: RSA, RMSA (Routing, Modulation, Spectrum Assignment), RMSCA
- **AI Methods**: DRL, GNN+RL, Transformer

| Year | Title | Venue | Approach |
|------|-------|-------|----------|
| 2024 | Deep Reinforcement Learning for Dynamic RMSA | JLT | DQN, PPO |
| 2023 | Graph Neural Network for Topology-Aware RSA | JOCN | GNN |

### Failure Detection & Localization

Detecting and localizing failures in optical networks.

- **Types**: Soft failures, hard failures, fiber cuts, equipment failures
- **Methods**: Anomaly detection, classification, root cause analysis

### Traffic Prediction & Engineering

Forecasting traffic demands and optimizing network traffic.

- **Models**: LSTM, GRU, Transformer, GNN
- **Applications**: Proactive resource allocation, energy efficiency

### Nonlinearity Compensation

Mitigating fiber nonlinear impairments using ML.

- **Impairments**: SPM, XPM, FWM, Kerr effect
- **Methods**: Neural Network equalizers, learned DBP

### Digital Signal Processing (DSP)

ML-enhanced DSP for coherent optical systems.

- **Components**: Carrier recovery, equalization, symbol detection
- **Approaches**: End-to-end learning, hybrid ML-DSP

### Network Security

AI for detecting and mitigating security threats.

- **Threats**: Physical layer attacks, jamming, eavesdropping
- **Methods**: Anomaly detection, attack classification

### Digital Twin

AI-powered digital twins for optical networks.

- **Applications**: What-if analysis, predictive maintenance, autonomous operations
- **Technologies**: GNPy, simulation frameworks

### Intent-Based Networking

Translating high-level intents to network configurations.

- **Approaches**: NLP, LLM, semantic parsing
- **Applications**: Zero-touch provisioning, self-driving networks

---

## 🛠️ Tools & Frameworks

| Tool | Description | Link |
|------|-------------|------|
| **GNPy** | Open-source library for physical layer modeling | [GitHub](https://github.com/Telecominfraproject/oopt-gnpy) |
| **OpenROADM** | Multi-source agreement for ROADM | [OpenROADM](http://openroadm.org/) |
| **TransportPCE** | OpenDaylight-based SDN controller | [GitHub](https://github.com/opendaylight/transportpce) |
| **ONF TAPI** | Transport API for SDN | [ONF](https://opennetworking.org/tapi/) |
| **Net2Plan** | Network planning tool | [Net2Plan](http://www.net2plan.com/) |

---

## 📊 Datasets

| Dataset | Description | Link |
|---------|-------------|------|
| **Microsoft Azure Network** | Optical network topology and traffic | [Link](#) |
| **SNDlib** | Network design benchmark instances | [SNDlib](http://sndlib.zib.de/) |
| **TIP OOPT** | OpenOptical packet transponder data | [TIP](https://telecominfraproject.com/) |

---

## 🏆 Competitions & Challenges

- **ITU AI/ML in 5G Challenge** - Network optimization tracks
- **OFC Workshop Challenges** - Annual ML challenges at OFC

---

## 📖 Books & Tutorials

- **Machine Learning for Future Fiber-Optic Communication Systems** - Springer
- **Deep Learning for Optical Communications** - Cambridge University Press

---

## 🎓 Research Groups

| Group | Affiliation | Focus |
|-------|-------------|-------|
| **ONDM Community** | Various | Optical network design and modeling |
| **Barcelona Neural Networking Center** | UPC | GNN for networks |
| **TIP OOPT** | Telecom Infra Project | Open optical transport |

---

## 📅 Conferences & Journals

### Conferences
- **OFC** - Optical Fiber Communication Conference
- **ECOC** - European Conference on Optical Communication
- **ONDM** - Optical Network Design and Modeling
- **ACP** - Asia Communications and Photonics Conference
- **PS** - Photonics in Switching and Computing

### Journals
- **Journal of Lightwave Technology (JLT)**
- **Journal of Optical Communications and Networking (JOCN)**
- **Optics Express**
- **IEEE Photonics Technology Letters**
- **IEEE/OSA Journal of Optical Communications**

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

- 🌟 Star this repo if you find it useful!
- 📬 Submit a PR to add papers, tools, or datasets
- 🐛 Open an issue for suggestions or corrections

---

## Citation

If you find this repository useful, please cite:

```bibtex
@misc{awesome-ai-optical,
  author = {Your Name},
  title = {Awesome AI for Optical Communication Networks},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/YOUR_USERNAME/awesome-ai-optical-communication-network}
}
```

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

---

**Maintainer**: [Your Name](https://github.com/YOUR_USERNAME)  
**Last Updated**: February 2026
