# 🚀 Static Website Deployment Demo

[![GitHub Pages](https://img.shields.io/badge/Deployed%20With-GitHub%20Pages-222222?logo=github&logoColor=white)](https://pages.github.com/)
[![HTML5](https://img.shields.io/badge/HTML5-Structure-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
![Status](https://img.shields.io/badge/Project-Deployment%20Test-orange)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 📌 About This Project

This repository was created **only to test and practice deployment using GitHub**.

The website contains very simple HTML and CSS files.  
There is no backend logic and no production goal — it is purely a **deployment experiment** to understand how static hosting works with GitHub Pages.

---

## 🗂 Project Structure

```pgsql
static-website-demo/
│
├── index.html → Homepage  
├── about.html → About page  
├── 404.html → Custom not found page  
├── css/
│ └── style.css → Styling file
├── LICENSE
└── README.md
```

---

## 🌐 Live Deployment

Once GitHub Pages is enabled, the website will be available at:

```url
https://Maryam-Skaik.github.io/static-website-demo/
```

## 🛠 How to Try This Yourself

If you want to deploy your own simple static website using GitHub Pages, follow these steps:

### 1️⃣ Create Your Project Files

Create a folder containing:

- `index.html`
- `css/style.css`
- (Optional) `about.html`
- (Optional) `404.html`

Make sure `index.html` is in the **root directory**.

---

### 2️⃣ Initialize Git Locally

Open terminal inside your project folder:

```bash
git init
git add .
git commit -m "Initial commit: static website"
```

---

### 3️⃣ Create a GitHub Repository

1. Go to GitHub
2. Click **New Repository**
3. Name it (for example: `static-website-demo`)
4. Do NOT initialize with README (if you already have one locally)

---

### 4️⃣ Connect Local Repo to GitHub

```Bash
git branch -M main
git remote add origin https://github.com/Maryam-Skaik/static-website-demo.git
git push -u origin main
```

---

### 5️⃣ Enable GitHub Pages

1. Go to your repository → **Settings**
2. Click **Pages**
3. Under **Source*, select:
    - Branch: `main`
    - Folder: `/ (root)`
4. Click **Save**

After a few seconds, GitHub will generate your live website URL.

---

## ✅ Why GitHub Pages?

- Completely free
- Permanent hosting for static websites
- No server required
- No sleeping apps
- Automatic redeploy when pushing updates

---

## 🎯 Purpose of This Repository

✔ Practice deployment <br>
✔ Understand static hosting <br>
✔ Experiment with GitHub Pages <br>
✔ Keep a minimal example for future reference <br>

---

Made with ❤️ by **Maryam Skaik**