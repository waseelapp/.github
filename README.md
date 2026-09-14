<div align="center">

<!-- HEADER HERO BANNER -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320" width="100%">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#022c22" />
      <stop offset="50%" stop-color="#064e3b" />
      <stop offset="100%" stop-color="#022c22" />
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#34d399" />
      <stop offset="100%" stop-color="#06b6d4" />
    </linearGradient>
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#10b981" stop-opacity="0.3" />
      <stop offset="100%" stop-color="#022c22" stop-opacity="0" />
    </radialGradient>
  </defs>
  <rect width="100%" height="100%" fill="url(#bgGrad)" rx="16" />
  <circle cx="600" cy="160" r="220" fill="url(#glow)" />
  <rect x="20" y="20" width="1160" height="280" fill="none" stroke="#059669" stroke-width="1.5" stroke-dasharray="8 6" rx="12" opacity="0.4" />
  <text x="50%" y="115" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-weight="800" font-size="64" fill="url(#textGrad)" text-anchor="middle" letter-spacing="6">WASEEL</text>
  <text x="50%" y="165" font-family="'Traditional Arabic', 'Amiri', 'Scheherazade New', serif" font-weight="bold" font-size="38" fill="#10b981" text-anchor="middle">وسيل</text>
  <text x="50%" y="225" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-weight="400" font-size="20" fill="#a7f3d0" text-anchor="middle" letter-spacing="1.5">Test &amp; Reinforce Your Quran Memory with Precision</text>
</svg>

<br />

<!-- DYNAMIC BADGES -->
[![Build & Deploy Status](https://img.shields.io/github/actions/workflow/status/waseelapp/quranmemorytester/main.yml?branch=main&label=Build%20%26%20Deploy&style=for-the-badge&logo=githubactions&logoColor=white&color=059669)](https://github.com/waseelapp/quranmemorytester/actions/workflows/main.yml)
![PWA Ready](https://img.shields.io/badge/PWA-Installable-10b981?style=for-the-badge&logo=pwa&logoColor=white)
![Cost](https://img.shields.io/badge/License-MIT_Open_Source-06b6d4?style=for-the-badge)
![Registration](https://img.shields.io/badge/Account-No_Sign--Up-34d399?style=for-the-badge)

<br />

# 📖 Waseel (وسيل)

[**🚀 Launch Waseel App ↗**](https://shiftedtech.github.io/waseel/) &nbsp;•&nbsp; [**✨ Features**](#-key-features) &nbsp;•&nbsp; [**💡 How It Works**](#-how-it-works) &nbsp;•&nbsp; [**⚖️ Legal & Licensing**](#️-legal--licensing)

---

</div>

<br />

## 🌟 Overview

**Waseel** is a clean, privacy-focused Web App (PWA) designed for *Huffaz* and Quran students to test instant verse recall and strengthen long-term *Hifz* retention.

Rather than standard linear reading, Waseel generates **targeted random verse prompts** by Juzuk. Test your immediate memory, verify accuracy with audio recitation, and expand your recall by sequentially revealing subsequent verses.

<br />

```gcode
 ┌─────────────────────────────────────────────────────────┐
 │                   ✨ WASEEL DASHBOARD                   │
 ├─────────────────────────────────────────────────────────┤
 │ [ Select Juzuk: All (1 - 30) ▾ ]       [ 🎲 Generate ]  │
 │                                                         │
 │ 📖 Surah Al-Fatiha (1:1) • Juzuk 1                      │
 │                                                         │
 │               بِسْمِ ٱللَّهِ ٱلرَّحْمَٰنِ ٱلرَّحِيمِ               │
 │                                                         │
 │ [ 👁️ Reveal Next Verse ]   [ 🎧 Listen (Al-Hussary) ]   │
 └─────────────────────────────────────────────────────────┘


## <a id="key-features"></a>✨ Key Features

- **🎯 Juzuk Scope Filtering:** Target your revision precisely. Select a single Juzuk you recently memorized or test broad recall across all 30 Juzuk.
- **📖 Sequential Verse Reveal:** Test beyond single verses. Click to reveal the next verse step-by-step to test how far down the Surah you can recite accurately.
- **🎧 Audio Recitation:** Instant playback of clear recitations by Sheikh Mahmoud Khalil Al-Hussary to verify Tajweed, pronunciation, and verse stops.
- **📱 PWA & Offline Access:** Install directly to your iOS/Android home screen or desktop for fast, distraction-free practice without registration.

<br />

---

## <a id="how-it-works"></a>💡 How It Works

<details>
<summary><b>🎯 1. Juzuk Scope Filtering (Click to Expand)</b></summary>

<br />

Filtering allows you to isolate specific portions of the Quran to match your current revision schedule (*Sabqi* or *Manzil*).


[ Select Range ] ──► [ Juzuk 1 - 5 ] ──► Filtered Pool (1,061 Verses)


- **Single Juzuk Focus:** Deep-dive into one Juzuk after a memorization session.
- **Multi-Juzuk Range:** Review specific blocks of memorized Surahs.
- **Full Quran Randomizer:** Challenge ultimate recall across all 6,236 Ayahs.

</details>

<details>
<summary><b>📖 2. Sequential Verse Reveal Mechanism (Click to Expand)</b></summary>

<br />

Testing memory isn't just about identifying a single Ayah—it's about continuing the flow without hesitation.

1. **Initial Prompt:** Receives random Ayah prompt (e.g., *Surah Al-Baqarah 2:255*).
2. **Mental Recall:** Recite the following Ayahs from memory.
3. **Interactive Validation:** Tap **"Reveal Next Verse"** to check *Verse 2:256*, *2:257*, and onward.

</details>

<details>
<summary><b>🎧 3. Audio Verification with Sheikh Al-Hussary (Click to Expand)</b></summary>

<br />

Integrates high-quality audio APIs for instant auditory confirmation.
- **Qari:** Sheikh Mahmoud Khalil Al-Hussary (known for precise *Murattal* rhythm and Tajweed clarity).
- **Playback Control:** On-demand verse playback to verify tricky stops or diacritics (*Harakat*).

</details>

<br />

---

## 🎨 Color Palette & Design Concept

Waseel utilizes a modern, dark-mode Quranic UI designed to minimize eye strain during night-time revision.

| Color | Hex Code | Usage | Visual |
| :--- | :--- | :--- | :---: |
| **Dark Emerald** | `#022c22` | Deep Background / Containers | ![#022c22](https://via.placeholder.com/15/022c22/022c22.png) |
| **Primary Emerald** | `#059669` | Primary Buttons / Highlights | ![#059669](https://via.placeholder.com/15/059669/059669.png) |
| **Mint Green** | `#10b981` | Secondary Accents / Badges | ![#10b981](https://via.placeholder.com/15/10b981/10b981.png) |
| **Bright Teal** | `#34d399` | Gradient Text / Active States | ![#34d399](https://via.placeholder.com/15/34d399/34d399.png) |
| **Cyan Glow** | `#06b6d4` | Gradient Glows / Dynamic Links | ![#06b6d4](https://via.placeholder.com/15/06b6d4/06b6d4.png) |

<br />

---

## 💻 Tech Stack & Automation

- **Frontend Core:** HTML5, Modern JavaScript (ES6+), CSS3 (Custom Dark Emerald Theme)
- **Application Type:** Progressive Web App (PWA) / Offline Storage Ready
- **CI/CD Automation:** GitHub Actions (`.github/workflows/main.yml`) for automated testing and deployment.
- **Hosting:** GitHub Pages

<br />

---

## <a id="legal--licensing"></a>⚖️ Legal & Licensing

- **Quran Text:** The Arabic text of the Holy Quran is in the public domain.
- **Audio Recitations:** Audio files are fetched via open educational APIs (e.g., Quran.com / EveryAyah) for educational and non-commercial memory revision.
- **Source Code License:** Released under the [MIT License](LICENSE). Free for personal use, adaptation, and educational distribution.

---

<div align="center">

### 🟢 Ready to strengthen your Hifz?

[**Open Waseel Web App →**](https://shiftedtech.github.io/waseel/)

*Designed for daily revision and memory retention.*

</div>
