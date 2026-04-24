# Inkwell Blogging Platform - Frontend

This is the frontend application for the Inkwell Blogging Platform. It is built using modern web technologies to provide a fast, responsive, and dynamic user experience.

## Tech Stack

- **Framework**: [React](https://react.dev/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Animations**: [Framer Motion](https://www.framer.com/motion/)
- **Routing**: [React Router](https://reactrouter.com/)
- **Rich Text Editor**: [Tiptap](https://tiptap.dev/)
- **Icons**: [Lucide React](https://lucide.dev/)

## Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Riya-Teepa-12/Blogging-platform-frontend.git
   cd Blogging-platform-frontend
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   
   Create a `.env` file in the root directory based on the provided `.env.example` file:
   
   ```bash
   cp .env.example .env
   ```
   
   Update the variables in `.env` to point to your local or deployed backend services.

4. **Start the development server:**

   ```bash
   npm run dev
   ```

   The application will be available at `http://localhost:5173` (or the port specified by Vite).

## Building for Production

To create a production build, run:

```bash
npm run build
```

This will generate a `dist` folder containing the compiled and minified static assets, which can be deployed to any static hosting service.

## Project Structure

- `src/` - Source code for the application.
  - `components/` - Reusable UI components.
  - `pages/` - Page-level components.
  - `assets/` - Static assets like images and styles.
- `public/` - Public static files (e.g., `index.html`, favicon).

## Branching Strategy

This project follows a standard branching workflow:

- `main` - Production-ready code.
- `dev` - Integration branch for ongoing development.
- `feature/*` - Topic branches for developing new features.

## Contributing

1. Create a feature branch from `dev` (e.g., `feature/my-new-feature`).
2. Make your changes and commit them with descriptive messages.
3. Push your feature branch to the remote repository.
4. Create a Pull Request against the `dev` branch.
