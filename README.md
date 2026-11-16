# ✨ Free Gemini & Google Flow Watermark Remover (Gemini Omni & Nano Banana)

<p align="center">
  <a href="https://yuvarajamaniraj.github.io/gemini-watermark-remover/">
    <img src="./assets/logo.webp" alt="Gemini Watermark Remover Logo" width="100" height="100" />
  </a>
</p>

<p align="center">
  <strong>Remove visible Gemini and Google Flow watermarks from Gemini Omni videos and Nano Banana AI images online.</strong><br>
  Completely free, private, and runs 100% client-side in your web browser with zero quality loss.
</p>

<p align="center">
  <a href="https://yuvarajamaniraj.github.io/gemini-watermark-remover/"><img src="https://img.shields.io/badge/🚀_Live_Demo-GitHub_Pages-6366f1?style=for-the-badge" alt="Live Demo" /></a>
  <a href="https://github.com/yuvarajamaniraj/gemini-watermark-remover/stargazers"><img src="https://img.shields.io/github/stars/yuvarajamaniraj/gemini-watermark-remover?style=for-the-badge&color=eab308" alt="GitHub Stars" /></a>
</p>

---

## 🌐 Live Website

👉 **Try it online:** [https://yuvarajamaniraj.github.io/gemini-watermark-remover/](https://ishara-madu.github.io/gemini-watermark-remover/)

---

## 💡 Why This Tool?

Most AI watermark removers use **generative AI inpainting**, which hallucinates missing pixels and blurs the background.

Google Gemini, Google Flow, Gemini Omni, and Veo models embed visible watermarks using **transparent alpha blending**. Because the underlying pixels are still present beneath the transparency, **Gemini Watermark Remover** uses exact mathematical unblending to subtract the watermark mask pixel-by-pixel, restoring **100% of your original image & video clarity** with zero quality loss.

$$\text{Original} = \frac{\text{Watermarked} - (\text{Logo} \times \alpha)}{1 - \alpha}$$

---

## 🚀 Features

- 🔒 **100% Private & Client-Side:** Files never leave your device. All rendering is handled locally in your browser via HTML5 Canvas and WebCodecs.
- 🖼️ **Gemini & Nano Banana Image Support:** Clean images (PNG, JPG, WebP) with instant high-resolution lossless PNG export.
- 🎬 **Gemini Omni, Google Flow & Veo 3 Video Support:** Fast frame-by-frame processing with MP4 export while preserving original audio tracks.
- 🎛️ **Live Tuner & Model Presets:** Quick-select model presets for Nano Banana, Gemini Omni, Flow, and Veo alongside real-time sliders and dual zoomed comparison views.
- ⚡ **Zero Quality Loss:** Restores exact pixel colors without blurry inpainting.
- 📱 **Fully Responsive:** Beautiful, clean, modern UI optimized for desktop, tablet, and mobile browsers.
- 🆓 **Unlimited & Free:** No signups, no subscriptions, and no secondary watermarks.

---

## 🛠️ Tech Stack

- **Frontend:** Pure Semantic HTML5, Modern Vanilla CSS (Custom Design System), JavaScript (ES6+)
- **Processing:** HTML5 Canvas API, WebCodecs API, [MediaBunny](https://github.com/diffusion-studio/mediabunny) for high-performance in-browser video unblending and AVC/H.264 muxing
- **Hosting:** GitHub Pages

---

## 💻 Local Development

Run the project locally with any static web server:

```bash
# 1. Clone the repository
git clone https://github.com/ishara-madu/gemini-watermark-remover.git

# 2. Navigate to project folder
cd gemini-watermark-remover

# 3. Start a local server (using Python 3, Node, or VS Code Live Server)
# Option A: Python
python3 -m http.server 8000

# Option B: Node.js (npx serve)
npx serve .
```

Open `http://localhost:8000` in your browser.
