# OpenFav Development Project

A modern web application built with Astro, React, and Supabase for managing and organizing favorite websites and resources.

## 🚀 Tech Stack

- ⚡ [Astro](https://astro.build/) - The web framework for content-driven websites
- 🎨 [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework
- 🔐 [Supabase](https://supabase.com/) - Open source Firebase alternative
- ⚛️ [React](https://react.dev/) - JavaScript library for building user interfaces
- 📦 [Nanostores](https://github.com/nanostores/nanostores) - Tiny state manager
- 🎭 [TypeScript](https://www.typescriptlang.org/) - Type-safe JavaScript
- 🎯 [Vercel](https://vercel.com/) - Cloud platform for static sites and Serverless Functions

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/TrevorReznick/openfav-dev.git
   cd openfav-dev
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   ```
   Update the `.env` file with your Supabase credentials.

## 🔧 Configuration

1. Create a new project on [Supabase](https://supabase.com/)
2. Set up authentication in the Supabase dashboard
3. Configure environment variables in `.env`:
   ```
   PUBLIC_SUPABASE_URL=your-supabase-url
   PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
   ```

## 🚀 Development

| Command          | Action                                         |
| ---------------- | ---------------------------------------------- |
| `npm install`    | Install dependencies                           |
| `npm run dev`    | Start development server at `localhost:4321`   |
| `npm run build`  | Build for production                           |
| `npm run preview`| Preview production build locally               |
| `npm run astro`  | Run Astro CLI commands                         |

## 📁 Project Structure

```
├── public/             # Static files
├── src/
│   ├── assets/         # Static assets
│   ├── components/     # Reusable UI components
│   ├── layouts/        # Page layouts
│   ├── middleware/     # Server middleware
│   ├── pages/          # Application routes
│   ├── providers/      # Context providers
│   ├── scripts/        # Utility scripts and API builders
│   ├── store/          # State management
│   └── types/          # TypeScript type definitions
├── test/               # Test files
├── vendor/             # Third-party integrations
├── astro.config.ts     # Astro configuration
├── package.json        # Project dependencies
└── tsconfig.json      # TypeScript configuration
```

## 🚀 Deployment

This project is optimized for deployment on Vercel. The Vercel configuration is already set up in `vercel.json`.

1. Push your code to a Git repository
2. Import the repository into Vercel
3. Set up environment variables in the Vercel dashboard
4. Deploy!

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) before making a pull request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

- **Author**: Trevor Reznick
- **Email**: electrics.sheeps@gmail.com
- **Website**: [OpenFav](https://openfav-auth.vercel.app)

