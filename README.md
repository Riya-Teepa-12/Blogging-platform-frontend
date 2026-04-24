<br />
<div align="center">
  <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/React-Dark.svg" alt="React" width="60" height="60" style="margin: 0 10px;" />
  <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Vite-Dark.svg" alt="Vite" width="60" height="60" style="margin: 0 10px;" />
  <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/TailwindCSS-Dark.svg" alt="Tailwind CSS" width="60" height="60" style="margin: 0 10px;" />
  
  <h1 align="center">Inkwell Blogging Platform - Frontend</h1>

  <p align="center">
    A modern, high-performance web interface designed for a seamless reading and writing experience.
    <br />
    <br />
    <a href="#-features"><strong>Explore the features »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Riya-Teepa-12/Blogging-platform-frontend/issues">Report Bug</a>
    ·
    <a href="https://github.com/Riya-Teepa-12/Blogging-platform-frontend/issues">Request Feature</a>
  </p>
</div>

<div align="center">

[![Contributors](https://img.shields.io/github/contributors/Riya-Teepa-12/Blogging-platform-frontend.svg?style=for-the-badge&color=blue)](https://github.com/Riya-Teepa-12/Blogging-platform-frontend/graphs/contributors)
[![Forks](https://img.shields.io/github/forks/Riya-Teepa-12/Blogging-platform-frontend.svg?style=for-the-badge&color=blue)](https://github.com/Riya-Teepa-12/Blogging-platform-frontend/network/members)
[![Stargazers](https://img.shields.io/github/stars/Riya-Teepa-12/Blogging-platform-frontend.svg?style=for-the-badge&color=blue)](https://github.com/Riya-Teepa-12/Blogging-platform-frontend/stargazers)
[![Issues](https://img.shields.io/github/issues/Riya-Teepa-12/Blogging-platform-frontend.svg?style=for-the-badge&color=blue)](https://github.com/Riya-Teepa-12/Blogging-platform-frontend/issues)
[![MIT License](https://img.shields.io/github/license/Riya-Teepa-12/Blogging-platform-frontend.svg?style=for-the-badge&color=blue)](https://github.com/Riya-Teepa-12/Blogging-platform-frontend/blob/main/LICENSE)

</div>

---

## 📖 Table of Contents
- [About The Project](#-about-the-project)
  - [Tech Stack](#-tech-stack)
  - [Key Features](#-key-features)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Environment Variables](#-environment-variables)
- [Project Structure](#-project-structure)
- [Available Scripts](#-available-scripts)
- [Contributing](#-contributing)

---

## 🚀 About The Project

**Inkwell** is an elegant, highly responsive blogging platform built with a focus on typography, readability, and a frictionless authoring experience. Designed with a mobile-first approach, it utilizes the power of **Vite** and **React** for lightning-fast navigation, while **Tailwind CSS** ensures a highly customized and beautiful UI.

### 🛠 Tech Stack

* **Core:** [React 19](https://react.dev/) & [Vite](https://vitejs.dev/)
* **Routing:** [React Router v7](https://reactrouter.com/)
* **Styling & UI:** [Tailwind CSS](https://tailwindcss.com/)
* **Motion:** [Framer Motion](https://www.framer.com/motion/)
* **Rich Text Editing:** [Tiptap Editor](https://tiptap.dev/)
* **Icons:** [Lucide React](https://lucide.dev/)

### ✨ Key Features

* **Rich Text Editor:** A fully customized WYSIWYG editor using Tiptap, allowing authors to format text, add links, and structure articles effortlessly.
* **Modern Aesthetic:** A sleek UI crafted with Tailwind CSS featuring harmonious color palettes, fluid typography, and glassmorphism touches.
* **Fluid Animations:** Micro-interactions and page transitions powered by Framer Motion to provide a premium feel.
* **Responsive Design:** Completely mobile-friendly layouts that adapt beautifully across all screen sizes.

---

## ⚙️ Getting Started

Follow these steps to set up the project locally for development.

### Prerequisites

You need the following installed on your system:
* [Node.js](https://nodejs.org/) (v18.0.0 or higher)
* `npm`, `yarn`, or `pnpm`

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Riya-Teepa-12/Blogging-platform-frontend.git
   ```

2. **Navigate into the project folder**
   ```bash
   cd Blogging-platform-frontend
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

---

## 🔐 Environment Variables

Create a local `.env` file based on the provided example.

```bash
cp .env.example .env
```

Ensure the following variables are configured in your `.env` file to communicate with the Inkwell Backend services:

| Variable Name | Description | Example |
| ------------- | ----------- | ------- |
| `VITE_API_BASE_URL` | The endpoint for the backend API | `http://localhost:8080/api/v1` |

> [!WARNING]  
> Never commit your `.env` file. It is safely ignored by `.gitignore`.

---

## 📁 Project Structure

Here is a high-level overview of the application's structure:

```text
inkwell-frontend/
├── public/               # Publicly accessible static assets
├── src/                  # Source code
│   ├── components/       # Shared UI components (Buttons, Navbar, Cards)
│   ├── context/          # React Context providers (Auth, Theme)
│   ├── pages/            # Routable page components
│   ├── lib/              # API clients and utility functions
│   ├── main.jsx          # Application entry point
│   └── styles.css        # Tailwind & Global styles
├── .env.example          # Environment variable template
├── tailwind.config.js    # Tailwind configuration
└── vite.config.js        # Vite bundler configuration
```

---

## 💻 Available Scripts

Run these scripts from the project root using your package manager:

* `npm run dev`: Starts the local development server at `http://localhost:5173` with Hot Module Replacement (HMR).
* `npm run build`: Compiles and optimizes the application for production deployment into the `dist` folder.
* `npm run preview`: Bootstraps a local web server to preview your production build.

---

## 🤝 Contributing

We welcome contributions to make **Inkwell** even better! 

1. **Fork** the repository
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request against the `dev` branch.

<p align="center">
  <br/>
  Made with ❤️ by the Inkwell Team.
</p>
