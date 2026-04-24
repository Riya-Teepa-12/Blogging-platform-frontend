<br />
<div align="center">
  <h1 align="center">Inkwell Blogging Platform - Frontend</h1>

  <p align="center">
    A modern, feature-rich blogging platform frontend built with React, Vite, and Tailwind CSS.
    <br />
    <br />
    <a href="#features"><strong>Explore the features »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Riya-Teepa-12/Blogging-platform-frontend/issues">Report Bug</a>
    ·
    <a href="https://github.com/Riya-Teepa-12/Blogging-platform-frontend/issues">Request Feature</a>
  </p>
</div>

<!-- BADGES -->
<div align="center">
  [![Contributors][contributors-shield]][contributors-url]
  [![Forks][forks-shield]][forks-url]
  [![Stargazers][stars-shield]][stars-url]
  [![Issues][issues-shield]][issues-url]
  [![MIT License][license-shield]][license-url]
</div>

---

## 📖 Table of Contents
- [About The Project](#about-the-project)
  - [Tech Stack](#tech-stack)
  - [Key Features](#key-features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🚀 About The Project

The Inkwell Frontend is a highly responsive, performant, and user-friendly web interface designed to provide a seamless reading and writing experience. Built on modern web technologies, it features a comprehensive rich text editor, smooth micro-interactions, and a fully customizable aesthetic powered by Tailwind CSS.

### 🛠 Tech Stack

This project leverages the following modern tools and frameworks:

* **Framework:** [React 19](https://react.dev/) & [Vite](https://vitejs.dev/)
* **Routing:** [React Router v7](https://reactrouter.com/)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)
* **Animations:** [Framer Motion](https://www.framer.com/motion/)
* **Editor:** [Tiptap Rich Text Editor](https://tiptap.dev/)
* **Icons:** [Lucide React](https://lucide.dev/)

### ✨ Key Features

* **Rich Text Editing:** Full-featured WYSIWYG editor powered by Tiptap.
* **Modern UI/UX:** Responsive, mobile-first design with smooth Framer Motion transitions.
* **Authentication Ready:** Contexts and layouts pre-configured for robust Auth.
* **Performance Focused:** Vite-powered lightning-fast HMR and optimized production builds.

---

## ⚙️ Getting Started

Follow these instructions to set up the project locally for development and testing purposes.

### Prerequisites

Ensure you have the following installed on your local machine:
* [Node.js](https://nodejs.org/) (v18.0.0 or higher recommended)
* `npm` (v9+) or `yarn` or `pnpm`

### Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/Riya-Teepa-12/Blogging-platform-frontend.git
   ```

2. **Navigate to the project directory**
   ```sh
   cd Blogging-platform-frontend
   ```

3. **Install NPM packages**
   ```sh
   npm install
   ```

---

## 🔐 Environment Variables

To run this project, you will need to add specific environment variables. 
Copy the `.env.example` file to create your own local `.env` file:

```sh
cp .env.example .env
```

| Variable Name | Description | Default / Example |
| ------------- | ----------- | ----------------- |
| `VITE_API_BASE_URL` | The base URL for the backend API | `http://localhost:8080/api/v1` |

*(Note: Never commit your `.env` file to version control. It is ignored by default in this repository's `.gitignore`.)*

---

## 📜 Available Scripts

In the project directory, you can run the following standard commands:

### `npm run dev`
Runs the app in the development mode using Vite. Open [http://localhost:5173](http://localhost:5173) to view it in the browser. The page will reload if you make edits.

### `npm run build`
Builds the app for production to the `dist` folder. It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm run preview`
Locally preview the production build that was generated in the `dist` directory.

---

## 📁 Project Structure

A quick look at the top-level files and directories:

```text
inkwell-frontend/
├── public/               # Static assets that are not processed by Webpack/Vite
├── src/                  # Application source code
│   ├── components/       # Reusable React components (Navbar, Footer, etc.)
│   ├── context/          # React Contexts (Auth, Theme, etc.)
│   ├── pages/            # Top-level Page components (Home, Login, Post, etc.)
│   ├── lib/              # Utility functions and API service layers
│   ├── data/             # Mock data for frontend development
│   ├── styles.css        # Global CSS entries
│   └── main.jsx          # Application entry point
├── .env.example          # Template for required environment variables
├── package.json          # Project metadata, scripts, and dependencies
├── tailwind.config.js    # Tailwind CSS configuration
└── vite.config.js        # Vite bundler configuration
```

---

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request into the `dev` branch.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📬 Contact

Project Link: [https://github.com/Riya-Teepa-12/Blogging-platform-frontend](https://github.com/Riya-Teepa-12/Blogging-platform-frontend)

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/Riya-Teepa-12/Blogging-platform-frontend.svg?style=for-the-badge
[contributors-url]: https://github.com/Riya-Teepa-12/Blogging-platform-frontend/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Riya-Teepa-12/Blogging-platform-frontend.svg?style=for-the-badge
[forks-url]: https://github.com/Riya-Teepa-12/Blogging-platform-frontend/network/members
[stars-shield]: https://img.shields.io/github/stars/Riya-Teepa-12/Blogging-platform-frontend.svg?style=for-the-badge
[stars-url]: https://github.com/Riya-Teepa-12/Blogging-platform-frontend/stargazers
[issues-shield]: https://img.shields.io/github/issues/Riya-Teepa-12/Blogging-platform-frontend.svg?style=for-the-badge
[issues-url]: https://github.com/Riya-Teepa-12/Blogging-platform-frontend/issues
[license-shield]: https://img.shields.io/github/license/Riya-Teepa-12/Blogging-platform-frontend.svg?style=for-the-badge
[license-url]: https://github.com/Riya-Teepa-12/Blogging-platform-frontend/blob/main/LICENSE
