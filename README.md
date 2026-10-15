# 🌌 Antigravity Hub — Global Skills Registry & Marketplace

[![Skills Count](https://img.shields.io/badge/skills-1000%2B-blueviolet.svg?style=flat-square)](https://github.com/antigravity-hub/skills)
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)](LICENSE)
[![Format](https://img.shields.io/badge/spec-SKILL.md-orange.svg?style=flat-square)](https://github.com/antigravity-hub/skills)
[![Antigravity Shield](https://img.shields.io/badge/platform-Antigravity%20Shield-cyan.svg?style=flat-square)](https://github.com/antigravity-hub)

Official open-source decentralized catalog, telemetry registry, and procedural documentation mirror for the **Antigravity Shield** ecosystem and AI coding agents (Gemini, Claude Code, Cursor, Codex, Copilot, Windsurf, Cline, AMP, OpenClaw, and Trae).

---

## 🚀 Overview

This repository serves as the high-availability CDN and delta synchronization source for 1,000+ AI engineering skills. It features:
- **1,000 Curated Production Skills:** Spanning Frontend & React, Next.js, Backend & Microservices, Databases, DevOps & Cloud, AI & Agents, Mobile & Cross-Platform, Security, Testing & Audits, High-End Design & Visuals, and Growth Engineering.
- **Bilingual Documentation (`docs/<slug>/`):** In-depth English and Persian (`doc.fa.md`) procedural architecture guides for every skill.
- **Delta Sync Manifest (`manifest.json`):** Cryptographic SHA-256 hashes, telemetry snapshots (installs, stars, rating), security audits, and agent compatibility matrix.
- **Zero-Latency Ingestion (`catalog.min.json`):** Highly optimized lightweight JSON payload for client-side streaming and instant hydration.

---

## 📂 Repository Structure

```
.
├── catalog.min.json       # Compressed metadata for all 1,000 skills (1.89 MB)
├── manifest.json           # SHA-256 integrity hashes & delta versioning (723 KB)
├── docs/                   # Full markdown documentation and prompt engineering guides
│   ├── find-skills/
│   │   ├── doc.en.md
│   │   └── doc.fa.md
│   ├── ...
└── README.md
```

---

## ⚡ 1-Click Installation in Antigravity Shield

In Antigravity Shield, open the **Skills Marketplace** tab, browse or filter by topic/agent/security audit, and click **Install Skill**. The agent automatically mounts the procedural rule into your active workspace or global configuration (`~/.gemini/config/skills/`).

---

## 🛡️ Zero-Leak Privacy Guarantee

Local custom skills, private API keys, and sensitive workspace configurations are strictly kept on the user's local machine and are never transmitted to this public catalog.

---

## 📄 License
MIT © 2026 Antigravity Hub & Dr. Ershad Zolfi.
