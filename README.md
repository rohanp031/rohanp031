<!-- =====  README for Rohan Poddar  ===== -->

<!-- Adaptive Banner: the `src` values are placeholders — replace them with actual image file paths in your repo.
     Dev note: I've included your uploaded file path as a placeholder so you (or an automation) can replace it with the generated banner. -->
<p align="center">
  <picture>
    <!-- dark mode banner (preferred for dark-mode viewers) -->
    <source srcset="/banner-dark.png" media="(prefers-color-scheme: dark)">
    <!-- light mode / fallback banner -->
    <img alt="Rohan Poddar - Banner" src="/banner-light.png" width="900" style="max-width:100%;border-radius:12px;">
  </picture>
</p>

<h1 align="center">👋 Hi, I'm Rohan Poddar</h1>
<p align="center">
  <em>Full-Stack • AI/ML • Cybersecurity enthusiast</em><br>
  <sub>Based in Bengaluru, KA, India • B.E CSE (IoT & Cybersecurity with Blockchain Tech)</sub>
</p>

<p align="center">
  <!-- Animated badges -->
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-green?style=for-the-badge&logo=linkedin" alt="Open to work" />
  <img src="https://img.shields.io/badge/Top%20Langs-Java%2FPython-blue?style=for-the-badge" alt="Top Langs" />
  <img src="https://img.shields.io/badge/Experience-Infosys%20Springboard-orange?style=for-the-badge" alt="Internship" />
  <img src="https://img.shields.io/badge/OCI-2025%20Certified-brightgreen?style=for-the-badge&logo=oracle" alt="OCI Certified" />
</p>

---

## 🚀 About Me
- B.E. in CSE (IoT, Cybersecurity & Blockchain) — Bangalore Institute of Technology. :contentReference[oaicite:1]{index=1}  
- Built an ensemble CNN + Flask full-stack app during an internship (LeNet-5 family + custom CNN, voting ensemble). :contentReference[oaicite:2]{index=2}  
- Working on projects in **ML**, **Web**, and **Network Security** with a strong interest in practical, production-ready systems.

---

## 🧰 Tech & Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,python,cpp,c,js,html,css,react,pytorch,flask,git,github,linux" alt="tech icons" />
</p>

---

## ✨ GIF Sections

### Skills
<p align="center">
  <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" width="320" alt="skills gif"/>
</p>
- Java | Python | C | C++ | JavaScript | HTML/CSS  
- PyTorch | React | Next.js | Flask  
- Git, Linux, OCI Networking

### Projects
<p align="center">
  <img src="https://media.giphy.com/media/3o7aD4vG0V0f9hW0bO/giphy.gif" width="420" alt="projects gif"/>
</p>

**Featured**
- **Handwritten Digit Recognition (LeNet5 + ensemble)** — Flask + PyTorch. Repo: `rohanp031/Handwritten-Digit-Recognition-with-LeNet5-Model-in-PyTorch`. :contentReference[oaicite:3]{index=3}  
- **Automated OMR System** — OMR preprocessing, scoring interface. Repo: `rohanp031/automated-omr-system`. :contentReference[oaicite:4]{index=4}

### GitHub Stats (animated)
<p align="center">
  <img src="https://media.giphy.com/media/3o7bu3XilJ5BOiSGic/giphy.gif" width="340" alt="stats gif"/>
</p>

---

## 📊 3D Contribution Calendar (placeholder)
<p align="center">
  <!-- Once generated, replace the GIF path below with the produced `contrib-3d.gif` inside your repo. -->
  <img src="/contrib-3d.gif" alt="3D GitHub contributions calendar" width="700" style="max-width:100%;border-radius:8px;">
</p>

> Tip: If `/contrib-3d.gif` isn't present yet, follow the instructions below to generate it automatically with GitHub Actions (script + action included below).

---

## 🛠️ How to generate the assets automatically (banner / 3D calendar / badges)

### 1) Generate custom banner images
- Create `banner-dark.png` and `banner-light.png` (900×250 recommended).
- Tools: Figma / Canva / ImageMagick + text overlay. Use your name "Rohan Poddar", a short tagline, and subtle icons.
- Quick ImageMagick example (local):

```bash
convert -size 900x250 xc:#0f172a \
  -gravity center \
  -font Arial -pointsize 46 -fill white \
  -annotate +0+0 "Rohan Poddar" \
  banner-dark.png
