<div align="center">

# 🌌 ushift Matrix v5
### ⚡ The Ultimate Enterprise Edge Management Gateway

[![Cloudflare](https://img.shields.io/badge/Deployed%20on-Cloudflare%20Workers-orange?style=for-the-badge&logo=cloudflare)](https://workers.cloudflare.com/)
[![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](LICENSE)
[![Version](https://img.shields.io/badge/Version-5.0.0--Pro-blueviolet?style=for-the-badge)](https://github.com/)

---

**ushift Matrix v5** is a high-performance, aesthetically superior dashboard designed for the modern edge. It transforms standard connectivity into a professional enterprise experience with glassmorphism aesthetics and lightning-fast responsiveness.

[Explore Features](#-key-features) • [Quick Deploy](#-deployment-guide) • [UI Showcase](#-design-language)

</div>

---

## 💎 Key Features

<table width="100%">
  <tr>
    <td width="50%">
      <h4>🎨 Cosmic UI/UX</h4>
      Experience the future with a <b>Glassmorphism Design System</b>, featuring backdrop blurs, vibrant gradients, and smooth micro-animations.
    </td>
    <td width="50%">
      <h4>📱 Mobile Native Feel</h4>
      Not just responsive, but mobile-first. Includes a professional <b>Slide-in Navigation Drawer</b> and custom mobile header.
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h4>🔐 Lockdown Security</h4>
      Protected by <b>SHA-224 encryption</b>. Secure access to your configuration via tokenized JSON-fetch initialization.
    </td>
    <td width="50%">
      <h4>🛰️ Global Connectivity</h4>
      Leverage <b>Anycast routing</b> via Cloudflare's global network for ultra-low latency subscription generation.
    </td>
  </tr>
</table>

---

## 🚀 Deployment Guide

### Easy Setup
1. **Copy Script**: Grab the entire content of `_worker.js`.
2. **Create Worker**: Go to your [Cloudflare Dashboard](https://dash.cloudflare.com/) and create a new Worker.
3. **Paste & Deploy**: Clear the default code, paste Matrix v5, and hit `Save and Deploy`.

### Environment Setup (Variables)
| Key | Type | Importance | Description |
| :--- | :--- | :--- | :--- |
| `PASSWORD` | Secret | 🔴 Critical | The master key for your dashboard |
| `UUID` | String | 🟡 High | Your Vless/Socks5 Unique ID |
| `PROXYIP` | String | 🟡 High | Target Cloudflare IP/Domain |
| `SUB` | URL | 🔵 Optional | Subscription Backend URL |

---

## 📐 Design Language

Matrix v5 is crafted with attention to every pixel:
- **Primary Accent**: `#7c4dff` (Electric Violet)
- **Background**: `#05060f` (Deep Space Dark)
- **Typography**: `Outfit` for headers, `JetBrains Mono` for metadata.
- **Components**: Glass cards with `rgba(255, 255, 255, 0.03)` transparency and 1px border.

---

## � Tech Stack

<div align="left">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" />
</div>

---

<div align="center">

### ✨ Join the Matrix
If you find this project useful, don't forget to **Star** the repository!

Built with 💜 by **https://t.me/masluom**

</div>
