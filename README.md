# Beam Management using PPO with OAI + FLEXRIC + RFSIM

This repository contains the LaTeX report and documentation for a project on **AI-enabled Beam Management** in 5G networks using reinforcement learning. The work integrates OpenAirInterface (OAI), FLEXRIC, and RFSIM with a PPO agent, aligned with 5G-Advanced standardization trends.

---

## 📘 Overview

Beam Management (BM) is essential in 5G mmWave systems to sustain reliable directional communication. This project proposes a modular, AI-native BM framework leveraging PPO-based reinforcement learning, simulated entirely using open-source components.

---

## 🔍 System Components

- **OpenAirInterface (OAI)**: Simulates gNB and UE with integrated E2 Agent and performance reporting.
- **FLEXRIC**: Near-RT RIC controller managing metrics (KPM) and beam control (RC).
- **RFSIM**: Emulates radio links over localhost, removing the need for RF hardware.
- **PPO Agent**: Learns beam/power control via RL; interfaces with FLEXRIC through Python.
- **xApp Controller**: Bridges PPO and FLEXRIC, transforming observations into actions.

---

## 📚 References
OAI E2AP Guide

OAI Build Guide

Q. Xue et al., AI/ML for Beam Management in 5G-Advanced, arXiv:2309.10575

