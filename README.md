# 📰 Margin Notes — Day 04 / 7-Day Build Challenge

> An architectural editorial publication and in-browser writing platform built with zero dependencies using semantic HTML5, modern CSS, and vanilla JavaScript.

---

## 📖 Overview

**Margin Notes** is a lightweight, client-side digital magazine designed around high-contrast typography, reading ergonomics, and browser-native state persistence. 

Built completely framework-free, it provides a magazine-style reading experience with live search and category filtering, alongside a built-in publishing suite that lets readers write, style, and store their own essays directly inside `localStorage`.

---

## ✨ Features

- **In-Browser Authoring Modal:**
  - Create posts with real-time field validation.
  - Markdown-style shorthand for section headers (`## `) and pull quotes (`> `).
  - Dynamic category assignment with support for on-the-fly custom tag creation.
- **Dynamic Cover Generation:**
  - **Color Mode:** Dynamic HSL hue slider with algorithmic lead-letter typography glyphs (automatically filtering out common English stop words).
  - **Photo Mode:** Local file upload using the `FileReader` API, coupled with an off-screen HTML5 `<canvas>` to automatically downscale images into compressed JPEG data URIs to conserve browser storage quotas.
- **Client-Side Persistence:**
  - Custom articles and light/dark theme choices persist locally across browser sessions via `localStorage`.
  - Built-in safe deletion flow with a two-step confirmation toggle.
- **Reading Ergonomics & UI:**
  - Top-mounted reading progress bar mapped to the prose scroll position.
  - Dynamic
