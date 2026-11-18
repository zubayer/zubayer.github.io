# LeanQuest — Interactive Lean Green Belt Study Lab

> An independent, browser-based study companion for Lean Green Belt concepts. Learn, practice, and review with an engaging, offline-capable single-page app.

**[Launch the interactive LeanQuest app](https://zubayer.github.io/leanquest/)**

## 🌐 Live demo

Live app on the existing GitHub Pages site:

`https://zubayer.github.io/leanquest/`

The app is published under the `leanquest/` folder of the `zubayer.github.io` repository.

## 🎯 Why LeanQuest?

Traditional static notes can be hard to revise under time pressure. LeanQuest turns an extensive Lean Green Belt curriculum into compact study missions, instant-feedback practice questions, progress tracking, and an exam simulator.

## ✨ Features

| Feature | Details |
|---|---|
| Learning missions | 7 structured modules covering core Lean principles and tools |
| Mini-lessons | 61 short explainers and practical examples |
| Practice bank | 84 independently authored multiple-choice questions, with hints and explanations |
| Flashcards | Self-testing with learned-card tracking |
| Mock exam | 40-question, 120-minute simulation with scoring and review |
| Review mode | Retake missed questions and focus on weaker concepts |
| Study planner | 30-, 45-, 90-, and 120-minute guided revision plans |
| Calculators | Takt time, OEE, and process cycle efficiency / value-added share |
| Progress tracking | Browser-local progress and XP; no user account |
| Portable | One HTML file; no framework, build step, or API needed |

### Study topics

1. Lean foundations and customer value
2. Eight wastes, 5S, and visual management
3. Process mapping and value stream mapping
4. Takt time, flow, and PDCA
5. Pull systems, Kanban, and standard work
6. SMED, TPM, and OEE
7. Poka-yoke, Kaizen, and change management

## 🚀 Getting started

Open [`index.html`](index.html) in a modern browser. No installation or dependencies are necessary.

To use it **offline**, download `index.html` to your computer and open it locally. The hosted GitHub Pages address requires a network connection to load; it does not currently install as an offline web app.

## 📤 Publishing and updates

The app lives at `leanquest/index.html` within `zubayer/zubayer.github.io`. Update that file to update the live app. Do not move or overwrite the repository root `index.html`, which belongs to the existing homepage.

## 🛠️ Technology

- **HTML5** for structure
- **CSS3** for responsive visual design
- **Vanilla JavaScript** for learning navigation, quizzes, mock exam timing, and calculations
- **Browser `localStorage`** for progress preservation

No third-party scripts, API keys, server-side data collection, or user sign-in.

## 🔒 Privacy and data

Learning progress and exam results are saved **locally in the user's current browser** using `localStorage`. Nothing is synced between devices. Clearing site data or opening the app in a different browser may reset progress. The project does not send quiz answers to a server.

## 📷 Mobile and visual previews

Preview the responsive experience by opening the live app on a phone or narrowing your desktop browser.

Open the app's revision tools and formula calculator from its navigation.

## 🧭 Future improvements

- Export/import progress between devices
- Optional accessible high-contrast theme
- More scenario-based engineering cases
- Downloadable study summary
- Optional PWA caching for offline use of the hosted site
- Improved content editor and modular question data

## 📌 Educational disclaimer

LeanQuest is an **independently developed educational study tool**, not an official Institute of Industrial & Systems Engineers (IISE) product or official certification practice exam. It is not affiliated with, approved by, or endorsed by IISE. The original IISE course materials are **not included**. Course slide ranges within the tool are references for students who separately have authorized access to those materials. All third-party names and trademarks belong to their respective owners.

Content and practice questions should be reviewed for accuracy before relying on them in any certification setting. Exam rules may change and should be checked against your own course instructions.

## 📄 Licensing

No open-source license is included by default. The repository owner can decide later whether to add a license (for example, MIT) to grant other people reuse rights. Course materials and third-party trademarks are not licensed by this project.