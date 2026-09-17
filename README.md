# 🇰🇷 한글_OS — Belajar Bahasa Korea dari Nol

App web interaktif untuk belajar bahasa Korea dari dasar. Dark theme, responsive, dan bisa diinstall sebagai PWA (Progressive Web App).

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## ✨ Fitur

### 📖 Alfabet Lengkap
- **14 konsonan dasar** (ㄱ-ㅎ)
- **10 vokal dasar** (ㅏ-ㅣ)
- **5 konsonan ganda** (ㄲ, ㄸ, ㅃ, ㅆ, ㅉ)
- **9 vokal gabungan** (ㅐ, ㅔ, ㅘ, dll)
- Semua dalam **satu tampilan unified** — konsonan & vokal tidak dipisah!
- Klik huruf untuk lihat detail: nama, cara baca, tips, contoh kata

### 🧩 Suku Kata Builder
- Pilih konsonan + vokal → langsung jadi blok suku kata (가, 나, 한, dll)
- Real-time Unicode composition

### 🔍 Bedah Kata
- Klik kata → lihat cara **setiap suku kata disusun** dari huruf-huruf dasar
- Contoh: 안녕하세요 → 안(ㅇ+ㅏ+ㄴ) + 녕(ㄴ+ㅕ+ㅇ) + 하(ㅎ+ㅏ) + 세(ㅅ+ㅔ) + 요(ㅛ)
- Penjelasan step-by-step kenapa dibaca seperti itu

### 🎯 Kuis 10 Level
| Level | Materi |
|-------|--------|
| 1 | Konsonan Dasar |
| 2 | Vokal Dasar |
| 3 | Konsonan + Vokal Campur |
| 4 | Konsonan Ganda |
| 5 | Vokal Gabungan |
| 6 | Semua Huruf Campur |
| 7 | Suku Kata Pertama |
| 8 | Suku Kata + Batchim |
| 9 | Kata Sehari-hari |
| 10 | Boss Level — Kalimat |

- ⭐ Sistem bintang (1-3) berdasarkan skor
- 🔒 Level terkunci — harus lulus dulu untuk buka berikutnya
- 💾 Progress tersimpan (localStorage)

### 📱 PWA (Progressive Web App)
- Bisa diinstall di HP & desktop
- Offline support — tetap bisa dipakai tanpa internet
- Fullscreen app experience

### 💬 Kosakata Dasar
- 12 kata sehari-hari dengan text-to-speech (Web Speech API)

### 🎮 XP System
- Dapat XP setiap jawaban benar
- XP bertambah sesuai level (10-50 per jawaban)

## 🚀 Cara Pakai

1. Buka `index.html` di browser
2. Atau deploy ke GitHub Pages / Netlify / Vercel

### Install sebagai PWA
1. Buka di Chrome/Edge
2. Klik icon "Install" di address bar
3. App akan terinstall seperti native app

## 🛠 Tech Stack

- **HTML5** — semantic markup
- **CSS3** — custom properties, grid, animations, backdrop-filter
- **Vanilla JavaScript** — zero dependencies
- **Web Speech API** — text-to-speech untuk kosakata
- **Service Worker** — offline caching
- **Web App Manifest** — PWA installability

## 📂 Struktur File

```
korean-app/
├── index.html          # Main app (single file)
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
├── icons/
│   ├── icon-192.svg   # App icon 192px
│   └── icon-512.svg   # App icon 512px
└── README.md
```

## 📄 License

MIT — bebas dipakai, dimodifikasi, dan didistribusikan.

---

Dibuat dengan ❤️ untuk siapa saja yang mau belajar bahasa Korea dari nol.
