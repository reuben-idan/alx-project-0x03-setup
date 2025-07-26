# Splash App

[![Build](https://img.shields.io/github/actions/workflow/status/reuben-idan/alx-project-0x03-setup/ci.yml?style=flat-square)](https://github.com/reuben-idan/alx-project-0x03-setup/actions)
[![Last Commit](https://img.shields.io/github/last-commit/reuben-idan/alx-project-0x03-setup?style=flat-square)](https://github.com/reuben-idan/alx-project-0x03-setup/commits/main)
[![Open Issues](https://img.shields.io/github/issues/reuben-idan/alx-project-0x03-setup?style=flat-square)](https://github.com/reuben-idan/alx-project-0x03-setup/issues)
[![License](https://img.shields.io/github/license/reuben-idan/alx-project-0x03-setup?style=flat-square)](LICENSE)

Splash App is a modern Next.js application offering AI-powered utilities such as text generation and text-to-image conversion. The codebase is written in TypeScript, styled with Tailwind CSS, and follows clean architecture principles for scalability and easy maintenance.

## Table of Contents
1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Getting Started](#getting-started)
4. [Available Scripts](#available-scripts)
5. [Project Structure](#project-structure)
6. [Contributing](#contributing)
7. [License](#license)

## Features
- Next.js 15 (pages router)
- TypeScript with centralized interface definitions
- Tailwind CSS utility-first styling
- Reusable component library
- Custom 404 error page
- ESLint & Prettier configured for consistent code style
- Ready for CI/CD and deployment to Vercel or any Node host

## Tech Stack
| Category | Technology |
|----------|------------|
| Framework | Next.js 15 |
| Language  | TypeScript |
| Styling   | Tailwind CSS |
| Icons     | React Icons |
| Testing   | Jest, React Testing Library |
| Linting   | ESLint, Prettier |

## Getting Started
### Prerequisites
- Node.js >= 20
- npm >= 10 (or yarn / pnpm)

### Installation
```bash
# clone the repository
git clone https://github.com/reuben-idan/alx-project-0x03-setup.git
cd alx-project-0x03-setup/alx-project-0x03

# install dependencies
npm install
```

### Development
```bash
# start the development server
npm run dev
# visit http://localhost:3000
```

### Production Build
```bash
npm run build
npm start
```

## Available Scripts
| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot-reload |
| `npm run build` | Compile and bundle the application for production |
| `npm start` | Start the production server |
| `npm run lint` | Run ESLint checks |
| `npm run test` | Execute unit tests |

## Project Structure
```
alx-project-0x03/
├── components/          # Reusable React components
│   ├── common/
│   └── layouts/
├── interface/           # Centralised TypeScript interfaces
├── pages/               # Application routes
│   ├── api/             # API routes (serverless functions)
│   └── 404.tsx          # Custom error page
├── public/              # Static assets
├── styles/              # Global styles (if any)
├── .eslintrc.json       # ESLint configuration
├── tailwind.config.ts   # Tailwind CSS configuration
└── next.config.js       # Next.js configuration
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Ensure all tests pass and follow the existing code style.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/pages/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn-pages-router) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/pages/building-your-application/deploying) for more details.
