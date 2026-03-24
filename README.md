<img src="https://capsule-render.vercel.app/api?type=waving&color=0:060610,100:00c8ff&height=220&section=header&text=Gamith+Ranasinghe&fontSize=50&fontColor=ffffff&fontAlignY=38&desc=Personal+Portfolio+Website&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<div align="center">

[![React](https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://fonts.google.com/)

[![Live Portfolio](https://img.shields.io/badge/View_Portfolio-00c8ff?style=for-the-badge&logo=githubpages&logoColor=black)](https://github.com/Gamibro)

</div>

---

## 📌 Overview

This is my **personal developer portfolio website** built entirely with **React.js**. It is designed to give recruiters, clients, and collaborators a clear, professional, and visually engaging overview of who I am, what I have built, the technologies I work with, and how to reach me.

The portfolio features a **dark space-themed aesthetic** with an animated particle background, smooth scroll reveal animations, a typing effect hero section, and a fully responsive layout — all built without any external UI libraries, using only React hooks and inline styles with CSS animations.

---

## 🏗️ Tech Stack

| Layer | Technology |
|---|---|
| **Framework** | React.js |
| **Language** | JavaScript (ES6+) |
| **Styling** | Inline CSS + CSS Animations (via `<style>` injection) |
| **Fonts** | Google Fonts — Syne (headings) + DM Sans (body) |
| **Animations** | CSS Keyframes + IntersectionObserver API |
| **Canvas** | HTML5 Canvas API (particle system) |
| **Deployment** | GitHub Pages |

---

## ✨ Features

### 🎨 Design & Animations
- **Dark space theme** with a deep navy background (`#060610`) and electric cyan & purple accent colors
- **Animated particle canvas** — 100 floating particles with connecting lines rendered on an HTML5 Canvas, creating a live dynamic background throughout the entire page
- **Smooth scroll reveal** — every section fades and slides upward into view using the `IntersectionObserver` API as the user scrolls down the page
- **Floating photo ring** — profile photo in the hero section with a CSS float animation and a gradient ring border
- **Typing animation** — the subtitle in the hero cycles through three roles (Software Engineer, Full Stack Developer, Aspiring Data Scientist) with a blinking cursor effect
- **Hover micro-interactions** — every card, tag, button, and link has a custom hover state with smooth transitions

---

### 🧭 Navigation
- Fixed top navigation bar with **blur backdrop filter** for a frosted glass effect
- Navigation background dynamically darkens on scroll via a `scroll` event listener
- Smooth scroll to each section on nav link click

---

### 🏠 Hero Section
- Animated "Available for Opportunities" badge with a pulsing green dot
- Profile photo with a floating animation and gradient ring
- Large display name with a multi-color gradient text effect
- Typing animation cycling through job titles with a blinking cursor
- Short personal introduction paragraph
- Two CTA buttons — **View My Work** and **Get In Touch** — with hover lift and glow effects
- Animated scroll indicator at the bottom

---

### 📊 Stats Section
- Four metric cards displaying key facts at a glance:
  - **7+ Projects Built**
  - **6 Months Internship**
  - **HND Distinction**
  - **AI/ML Passion**
- Cards have hover lift and border glow effects

---

### 🛠️ Tech Stack Section
- Six category cards covering Frontend, Backend, Database & APIs, AI & Data, Tools, and Soft Skills
- Each card contains clickable skill tags with hover highlight effects
- Tags cover the full breadth of the technology stack — React, Node.js, C#, PHP, Java, Python, MySQL, MongoDB, OpenAI GPT-4, LangChain, and more

---

### 💼 Experience Section
- Dedicated card for the **6-month Full Stack Web Development Internship** at **Dockyard Total Solutions — Colombo Dockyard**
- Gradient top border bar across the card
- Bullet-point list of key responsibilities including app development, QA, ER diagrams, DFDs, documentation, and the Leadership Dashboard project
- Completion badge displayed on the card

---

### 🚀 Projects Section
- Responsive grid of **8 key projects** built across healthcare, finance, fitness, salon, tuition, food ordering, and data visualization domains
- Each project card includes:
  - Project emoji icon
  - Project title
  - Technology stack tags (purple accent style)
  - Short project description
  - GitHub link (where available)
  - Animated bottom bar that slides in on hover
- Projects include: CeyHealth, Money Lending System, Salon Management, Cake Tuition, FitnessWeb, Food Ordering System, Leadership Dashboard, and LuxeVista

---

### 📌 Currently Section
- Three cards showing current status:
  - 📚 Pursuing a **Bachelor's Degree in Data Science**
  - 💼 **Open to Work** — internship completed, seeking full-time roles
  - 🤖 Actively exploring **AI and Machine Learning**

---

### 📫 Contact Section
- Three contact cards linking to:
  - 📧 **Email** — gamithranasinghe001@gmail.com
  - 💼 **LinkedIn** — gamith-ranasinghe
  - 💻 **GitHub** — Gamibro
- Each card has a hover glow and lift animation

---

## 🗂️ Project Structure

```
portfolio/
│
├── public/
│   └── index.html
│
├── src/
│   ├── Portfolio.jsx        # Main portfolio component (all sections)
│   └── index.js             # React entry point
│
├── package.json
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v16 or above)
- [npm](https://www.npmjs.com/)

---

### 🚀 Running Locally

**1. Clone the repository**
```bash
git clone https://github.com/Gamibro/portfolio.git
```

**2. Navigate to the project directory**
```bash
cd portfolio
```

**3. Install dependencies**
```bash
npm install
```

**4. Start the development server**
```bash
npm start
```

Opens at **http://localhost:3000**

---

### 🌐 Deploying to GitHub Pages

**1. Install gh-pages**
```bash
npm install gh-pages --save-dev
```

**2. Add to `package.json`**
```json
"homepage": "https://Gamibro.github.io/portfolio",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```

**3. Deploy**
```bash
npm run deploy
```

---

## 📫 Contact

Built by **Gamith Ranasinghe**

📧 [gamithranasinghe001@gmail.com](mailto:gamithranasinghe001@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/gamith-ranasinghe)
💻 [GitHub](https://github.com/Gamibro)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c8ff,100:060610&height=120&section=footer&animation=fadeIn" width="100%"/>
