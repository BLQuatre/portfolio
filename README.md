# Portfolio

A modern, interactive personal portfolio website built with Vue 3 and TypeScript, featuring an immersive metaballs background animation.

## 🌟 Features

- **Interactive Design**: Mesmerizing metaballs background animation
- **Modern Tech Stack**: Built with Vue 3, TypeScript, and Vite
- **Responsive Layout**: Optimized for all device sizes
- **Clean UI**: Minimalist design with glassmorphism effects
- **Fast Performance**: Powered by Vite for lightning-fast development and builds
- **Type Safety**: Full TypeScript support for robust development

## 🛠️ Tech Stack

- **Framework**: Vue 3 with Composition API
- **Language**: TypeScript
- **Build Tool**: Vite
- **State Management**: Pinia
- **Routing**: Vue Router
- **Package Manager**: pnpm

## 📦 Project Structure

```
src/
├── components/
│   ├── MetaballsBackground.vue    # Interactive background animation
│   └── icons/
│       ├── GithubIcon.vue         # GitHub icon component
│       └── LinkedInIcon.vue       # LinkedIn icon component
├── views/
│   └── HomeView.vue               # Main portfolio page
├── router/
│   └── index.ts                   # Vue Router configuration
├── stores/                        # Pinia store modules
├── assets/
│   └── main.css                   # Global styles
├── App.vue                        # Root component
└── main.ts                        # Application entry point
```

## 🚦 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- pnpm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/BLQuatre/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Start the development server**
   ```bash
   pnpm dev
   ```

4. **Open your browser**

   Navigate to `http://localhost:5173` to view the portfolio.

## 📋 Available Scripts

| Command | Description |
|---------|-------------|
| `pnpm dev` | Start development server |
| `pnpm build` | Build for production |
| `pnpm preview` | Preview production build |
| `pnpm type-check` | Run TypeScript type checking |

## 🌐 Deployment

### Build for Production
```bash
pnpm build
```

The built files will be in the `dist/` directory, ready for deployment to any static hosting service.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ If you found this portfolio interesting, please consider giving it a star!
