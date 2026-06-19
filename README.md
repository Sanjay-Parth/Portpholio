<h2 align="center">
  Portfolio Website — v2.0<br/>
  <a href="https://sanjay.vercel.app/" target="_blank">sanjay.vercel.app</a>
</h2>

<div align="center">
  <img alt="Portfolio Demo" src="./Images/readme-img1.png" />
</div>

<br/>

<div align="center">

<img width="947" height="462" alt="image" src="https://github.com/user-attachments/assets/cb0b5c40-6b71-444c-a957-8e0bae1e8bd5" />

</div>

<h3 align="center">
  🔹 <a href="https://github.com/Sanjay-Parth/Portfolio/issues/new?assignees=&labels=bug&template=bug_report.md">Report Bug</a> &nbsp;&nbsp;
  🔹 <a href="https://github.com/Sanjay-Parth/Portfolio/issues/new?assignees=&labels=enhancement&template=feature_request.md">Request Feature</a>
</h3>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Live Demo](#-live-demo)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Customization Guide](#-customization-guide)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)

---

## 🧾 Overview

A clean, responsive personal portfolio built with **React.js**, showcasing my projects, technical skills, and resume. Designed for performance and easy customization — fork it and make it your own in minutes.

> If you fork and use this project, please give proper credit by linking back to the original repository. Thanks! 🙏

---

## 🚀 Live Demo

🌐 **[sanjay.vercel.app](https://sanjay.vercel.app/)**

---

## ✨ Features

| Feature | Description |
|---|---|
| 📖 Multi-Page Layout | Dedicated sections for Home, About, Projects, Resume, and Contact |
| 🎨 Themeable UI | Styled with React-Bootstrap and custom CSS — colors are easy to swap |
| 📱 Fully Responsive | Optimized for desktop, tablet, and mobile viewports |
| ⚡ Fast Load | Deployed on Vercel's CDN for near-instant response times |
| 🗂 Project Showcase | Dynamically renders GitHub project cards |
| 📄 Resume Section | Embedded, downloadable resume support |

---

## 🛠 Tech Stack

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

**Backend / Runtime**

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)

**Tools & Deployment**

![VSCode](https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## 🏁 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) `v14+`
- [Git](https://git-scm.com/)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Sanjay-Parth/Portfolio.git

# 2. Navigate into the project directory
cd Portfolio

# 3. Install dependencies
npm install

# 4. Start the development server
npm start
```

The app will be running at [http://localhost:3000](http://localhost:3000).  
The page hot-reloads on file changes.

### Build for Production

```bash
npm run build
```

Generates an optimized production bundle in the `/build` folder.

---

## 📁 Project Structure

```
Portfolio/
├── public/
│   └── index.html
├── src/
│   ├── components/         # All page sections (About, Projects, Resume, etc.)
│   │   ├── About/
│   │   ├── Home/
│   │   ├── Projects/
│   │   └── Resume/
│   ├── Assets/             # Images, icons, and static files
│   ├── App.js
│   └── index.js
├── Images/                 # README screenshots
├── package.json
└── README.md
```

---

## 🎨 Customization Guide

All personal content lives inside `/src/components/`. Here's what to update:

**1. Personal Info & Bio**  
Edit `src/components/Home/Home.js` and `src/components/About/AboutCard.js`.

**2. Skills & Tech Stack**  
Update `src/components/About/Techstack.js` and `Toolstack.js`.

**3. Projects**  
Add or modify project cards in `src/components/Projects/Projects.js`.

**4. Resume**  
Replace the resume file in `src/Assets/` and update the link in `src/components/Resume/ResumeNew.js`.

**5. Social Links**  
Update GitHub, LinkedIn, Twitter, and email links in `src/components/Home/Home.js`.

**6. Colors & Theme**  
Global CSS variables are defined in `src/style.css` — change the palette in one place.

---

## 📦 Deployment

This project is pre-configured for **Vercel** (zero config needed).

**Deploy with Vercel:**

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel
```

Or simply import the GitHub repository on [vercel.com/new](https://vercel.com/new) for automatic CI/CD on every push.

**Other platforms** (Netlify, GitHub Pages):

```bash
npm run build
# Then deploy the /build folder to your platform of choice
```

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add YourFeature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a Pull Request

Please open an [issue](https://github.com/Sanjay-Parth/Portfolio/issues) first for major changes.

---

## 📄 License

This project is open-source and available under the [MIT License](./LICENSE).

---

## 🙏 Acknowledgements

- Inspired by the open-source portfolio community
- Badges via [forthebadge.com](https://forthebadge.com) and [shields.io](https://shields.io)
- Deployed on [Vercel](https://vercel.com)

---

<div align="center">
  If you found this helpful, please consider giving it a ⭐ — it means a lot!
</div>
