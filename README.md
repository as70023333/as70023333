# ☁️ CCSP Study Guide — ADHD/Dyslexia Friendly

> 🎯 **Goal**: Help neurodivergent learners (and everyone!) pass the CCSP exam with clarity, not overwhelm.

[![CCSP Badge](https://img.shields.io/badge/Certification-CCSP-blue?style=for-the-badge)](https://www.isc2.org/certifications/ccsp)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Accessibility](https://img.shields.io/badge/Accessibility-ADHD%2FDyslexia%20Friendly-brightgreen)](#-accessibility-features)
[![Last Updated](https://img.shields.io/github/last-commit/YOUR_USERNAME/ccsp-study-guide?label=Updated)]()

---

## 🧭 Quick Navigation

| Domain | Topic | Weight | Link |
|--------|-------|--------|------|
| 🔷 D1 | Cloud Concepts & Design | 17% | [`/docs/domain-01-concepts.md`](./docs/domain-01-concepts.md) |
| 🔷 D2 | ☁️ **Cloud Data Security** | **20%** | [`/docs/domain-02-data-security.md`](./docs/domain-02-data-security.md) |
| 🔷 D3 | Platform & Infrastructure | 17% | [`/docs/domain-03-infrastructure.md`](./docs/domain-03-infrastructure.md) |
| 🔷 D4 | Application Security | 17% | [`/docs/domain-04-app-security.md`](./docs/domain-04-app-security.md) |
| 🔷 D5 | Security Operations | 16% | [`/docs/domain-05-operations.md`](./docs/domain-05-operations.md) |
| 🔷 D6 | Legal, Risk & Compliance | 13% | [`/docs/domain-06-legal-compliance.md`](./docs/domain-06-legal-compliance.md) |

> 💡 **Pro Tip**: Start with **Domain 2** (highest weight!) or **Domain 1** (foundation). Your choice — no wrong path.

---

## ♿ Accessibility Features

This guide is designed for neurodivergent learners:

✅ **Chunked content** — Short sections, clear headers, no walls of text  
✅ **Visual anchors** — Emojis, tables, and diagrams for pattern recognition  
✅ **Plain language** — Simple explanations before technical terms  
✅ **Multiple formats** — Markdown + suggestions for audio/PDF conversion  
✅ **Focus-friendly** — Minimal distractions, clear progression  

### 🎧 Preferred Learning Tools
```bash
# Text-to-Speech friendly
$ pandoc docs/domain-01-concepts.md -o domain-01-audio.txt

# High-contrast PDF
$ markdown-pdf --css-path assets/high-contrast.css docs/domain-01-concepts.md

# Flashcards (Anki format)
$ python scripts/md-to-anki.py practice/flashcards/domain-01.md
