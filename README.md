# 9jaCoder-Code-Editor-9CE-
Learn and write professional .9ja and .py (Python) codes in popular Nigeria indigeneous languages (Hausa, Yorùbá, Igbo, Fulfulde), with English and French. 9CE is a full-featured PyQt5 code editor built for digital inclusion. Code in your mother tongue..
### Code in Your Mother Tongue. 🇳🇬

**Nigeria's first desktop IDE for programming in Hausa, Yorùbá, Igbo, Fulfulde, English, and French.**

[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20Windows-blue)](#installation)
[![Built with PyQt5](https://img.shields.io/badge/built%20with-PyQt5-41cd52)](#technology)
[![Languages](https://img.shields.io/badge/UI%20languages-6-orange)](#supported-languages)
[![License](https://img.shields.io/badge/license-See%20LICENSE-lightgrey)](#license)
[![Made in Nigeria](https://img.shields.io/badge/made%20in-Lagos%2C%20Nigeria-008751)](#about-artmanntech)

*Formally presented at the National Engineering Conference, Abuja (2022)*

[Why 9CE?](#why-9ce) • [Features](#features) • [Installation](#installation) • [Screenshots](#screenshots) • [Roadmap](#roadmap) • [Contributing](#contributing)

</div>

---

## The Problem

Over 200 million Nigerians speak Hausa, Yorùbá, Igbo, and Fulfulde as first languages — yet every mainstream programming tool assumes fluency in English. For millions of talented young people, especially in underserved northern communities, the English-language barrier arrives *before* the logic barrier. They never find out whether they could have been programmers.

**9CE removes that barrier.**

## Why 9CE?

9CE is a full-featured desktop code editor whose entire interface — menus, dialogs, tooltips, error messages — is available in six languages: **Hausa, Yorùbá, Igbo, Fulfulde, English, and French**.

It was born from a simple conviction: the language you dream in should not disqualify you from building software. The project's founder learned to code on **BBC BASIC**, a language designed to make computing accessible to ordinary British schoolchildren in their own language. 9CE extends that same courtesy to West Africa.

Beyond education, 9CE is part of a broader mission: **digital inclusion as community safety**. Giving young people in northern Nigeria a genuine pathway into technology creates economic opportunity where recruitment into violence often preys on the absence of one.

## Supported Languages

| Language | Region | Status |
|----------|--------|--------|
| 🟢 Hausa | Northern Nigeria, Niger, Ghana | Full UI |
| 🟢 Yorùbá | Southwestern Nigeria, Benin | Full UI |
| 🟢 Igbo | Southeastern Nigeria | Full UI |
| 🟢 Fulfulde | Sahel region, West Africa | Full UI |
| 🟢 English | International | Full UI |
| 🟢 French | Francophone West Africa | Full UI |

*Planned regional editions follow the 9CE naming convention using ISO country codes — e.g., **BjCÉ** for Benin Republic.*

## Features

### ✍️ A Serious Editor
- **High-performance syntax highlighting** — debounced rehighlighting, chunked background processing, and dirty-block tracking keep large files responsive
- **Intelligent autocomplete** powered by a marisa-trie index with case-insensitive matching
- **Jedi-powered hover tooltips** — hover any variable or function for instant documentation
- **Adaptive variable scanning** that scales its scheduling to file size
- **Find & Replace overlay** with a modern, non-blocking inline UI
- **Automatic code detection** — 9CE recognises code in any editor window via its built-in `CodeFileDetector`

### 🎓 Built for Learners
- Full interface localisation in six languages — not just translated menus, but a coherent experience
- **QBasic-to-Python compatibility library** — a gentle bridge for learners coming from BASIC-family languages
- **Console-to-GUI converter** — transforms Python console programs into PyQt5 GUI applications, letting students see their work come alive as real desktop apps

### 📦 Easy to Install
- Native **`.deb` packages** for Debian/Ubuntu
- **AppImage** builds for cross-distro Linux compatibility
- Windows builds via PyInstaller

## Installation

### Debian / Ubuntu
```bash
sudo dpkg -i 9ce_<version>_amd64.deb
sudo apt-get install -f   # resolve dependencies if needed
```

### Any Linux (AppImage)
```bash
chmod +x 9CE-<version>-x86_64.AppImage
./9CE-<version>-x86_64.AppImage
```

### From Source
```bash
git clone https://github.com/artmanntech/9ce.git
cd 9ce
pip install -r requirements.txt
python main.py
```

**Requirements:** Python 3.8+, PyQt5, Jedi, marisa-trie

## Screenshots

> 📸 *Screenshots coming soon — syntax highlighting in Hausa UI, autocomplete in Yorùbá, and the Find & Replace overlay.*

## Technology

9CE is built in **Python with PyQt5**, chosen deliberately: the same stack students learn in is the stack their editor is written in. A curious learner can read the source of the very tool they code with.

| Component | Technology |
|-----------|-----------|
| GUI framework | PyQt5 |
| Code intelligence | Jedi |
| Autocomplete index | marisa-trie |
| Packaging | PyInstaller, dpkg, AppImage |

## Roadmap

- [ ] Indigenous-language keyword aliasing (write `idan` instead of `if` in Hausa mode)
- [ ] Classroom mode with teacher/student sync
- [ ] BjCÉ — Benin Republic localised edition
- [ ] Offline documentation packs in all six languages
- [ ] Plugin system for community language packs

## Contributing

9CE welcomes contributors of all kinds — **you don't need to write code to help**:

- 🌍 **Translators & linguists** — improve or extend our Hausa, Yorùbá, Igbo, and Fulfulde label dictionaries
- 🐍 **Python/Qt developers** — see open issues tagged `good first issue`
- 🎓 **Educators** — pilot 9CE in your classroom and tell us what breaks
- 📖 **Writers** — help with documentation in any supported language

Please read `CONTRIBUTING.md` before opening a pull request.

## About Artmanntech

9CE is developed by **[Artmanntech Solutions](https://artmanntech.com)**, a Lagos-based technology company founded by **Arthur IbukunOluwa Arokhamoni**, building indigenous-language technology for digital inclusion across West Africa.

> *"The first programming language I ever loved spoke to me plainly. Every Nigerian child deserves the same."*

## License

See [LICENSE](LICENSE) for details.

---

<div align="center">

**⭐ If 9CE's mission resonates with you, star this repository — it helps others find us.**

*Nà gòdiyā • Ẹ ṣé • Daalụ • A jaaraama • Thank you • Merci*

</div>
