<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=654ea3,eaafc8&height=200&section=header&text=intelliscan-a-code-plagarism-detection-sdk&fontSize=26&fontColor=ffffff&animation=twinkling" width="100%" />

<img src="https://img.icons8.com/?id=48332&format=png&size=100" width="90" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2500&pause=1000&color=654ea3&center=true&vCenter=true&width=700&height=50&lines=Code%20Quality%20%26%20Plagiarism%20Scanning%20UI;Next.js%20+%20MegaLinter" alt="Typing SVG" />

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](#)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)](#)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](#)
[![License](https://img.shields.io/github/license/AfnanSharif/intelliscan-a-code-plagarism-detection-sdk?style=for-the-badge&color=yellow)](LICENSE)

</div>

---

## 📖 Overview

**intelliscan** (package name `intellidetect`) is a Next.js frontend for running code-quality
and plagiarism/similarity scans, built against the same **MegaLinter** analysis engine used by
[safescan](https://github.com/AfnanSharif/safescan) — `docker-compose-megalinter.yml` runs the
scanning backend that the UI talks to.

## 🏗️ Project Layout

```
intelliscan-a-code-plagarism-detection-sdk/
├── src app pages         # Next.js app
├── cypress/                # E2E tests
├── docker-compose.yml         # App container
├── docker-compose-megalinter.yml  # MegaLinter analysis engine
└── mkdocs.yml                        # Docs site config
```


## ⚡ Setup & Run

### 🪟 Windows / 🍎 macOS / 🐧 Linux
```bash
git clone https://github.com/AfnanSharif/intelliscan-a-code-plagarism-detection-sdk.git
cd intelliscan-a-code-plagarism-detection-sdk
npm install
npm run dev
```
Open **http://localhost:3000**.

### 🐳 Analysis engine (Docker, all platforms)
```bash
docker compose -f docker-compose-megalinter.yml up
```

---

<div align="center">

**Created by [AfnanSharif](https://github.com/AfnanSharif)** · ⭐ star this repo if it helped you

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=654ea3,eaafc8&height=80&section=footer" width="100%" />

</div>
