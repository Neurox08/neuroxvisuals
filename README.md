# 📸 NeuroX Photography Portfolio

Welcome to my photography portfolio website.  
This site showcases my work in various photography categories with a clean, responsive layout and powerful features for both users and photographers.

🔗 **Live Site:** [https://neurox08.github.io](https://neurox08.github.io)

---

## 🎯 Features

- ✅ Fully responsive layout for desktop and mobile
- 🌙 Dark/Light theme toggle
- 🔍 Search bar to filter images by tags
- 🖼️ Lazy loading for faster image performance
- ⬇️ Optional download button per photo
- 📂 Organized gallery by categories
- 📱 Hamburger menu navigation
- 🧭 Portfolio-ready structure for future expansion

---

## 🧰 Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- Hosted via **GitHub Pages**

---

## 📁 How to Use / Edit

1. Upload your images into the `images/` folder.
2. In `index.html`, add your image like this:

```html
<div class="photo" data-tags="nature sunset">
  <img src="images/sunset.jpg" alt="Sunset" loading="lazy">
  <button class="download-btn" onclick="downloadImage('images/sunset.jpg')">Download</button>
</div>
