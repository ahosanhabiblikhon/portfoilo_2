# Ahosan Habib Likhon - Portfolio Website

A modern, premium personal portfolio website built with Next.js, TypeScript, and Tailwind CSS.

## About

This is the personal portfolio website of **Ahosan Habib Likhon**, a Biotechnology & Genetic Engineering student at Islamic University, Bangladesh. The website showcases skills in web development, research work in biotechnology, and photography.

## Features

- 🎨 Modern, premium design with glassmorphism effects
- 🌓 Dark/Light mode toggle
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading and optimized for performance
- 🎭 Smooth animations with Framer Motion
- 🎯 SEO optimized
- 📦 Static export for GitHub Pages deployment
- 🔗 Dynamic GitHub repository integration

## Tech Stack

- **Framework:** Next.js 14
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Animations:** Framer Motion
- **Icons:** Lucide React
- **Theme:** next-themes

## Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. Clone the repository:
\`\`\`bash
git clone https://github.com/ahosanhabiblikhon/portfolio-v3.git
cd portfolio-v3
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
# or
yarn install
\`\`\`

3. Run the development server:
\`\`\`bash
npm run dev
# or
yarn dev
\`\`\`

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Building for Production

### For Vercel/Netlify Deployment

\`\`\`bash
npm run build
npm start
\`\`\`

### For GitHub Pages

1. Build and export static files:
\`\`\`bash
npm run export
\`\`\`

2. The static files will be in the \`out/\` directory.

3. Deploy the contents of \`out/\` to GitHub Pages:
   - Push to the \`gh-pages\` branch, or
   - Configure GitHub Pages to use the \`out/\` directory

## Project Structure

\`\`\`
portfolio-v3/
├── app/                  # Next.js app directory
│   ├── layout.tsx       # Root layout
│   ├── page.tsx         # Home page
│   └── globals.css      # Global styles
├── components/          # React components
│   ├── About.tsx
│   ├── Contact.tsx
│   ├── Footer.tsx
│   ├── Hero.tsx
│   ├── Navbar.tsx
│   ├── Photography.tsx
│   ├── Projects.tsx
│   ├── Research.tsx
│   ├── Skills.tsx
│   └── ThemeProvider.tsx
├── public/              # Static assets
├── next.config.js       # Next.js configuration
├── tailwind.config.js   # Tailwind CSS configuration
├── tsconfig.json        # TypeScript configuration
└── package.json         # Dependencies
\`\`\`

## Sections

1. **Hero** - Introduction with animated headline and social links
2. **About** - Personal story and academic background
3. **Skills** - Technical and creative skills showcase
4. **Projects** - GitHub repositories integration
5. **Research** - Academic work and research interests
6. **Photography** - Photography portfolio showcase
7. **Contact** - Contact form and social media links
8. **Footer** - Quick links and copyright

## Customization

To customize the website for your own use:

1. Update personal information in components
2. Change color scheme in \`tailwind.config.js\`
3. Replace social media links
4. Update GitHub username for project integration
5. Add your own images to \`public/images/\`

## Deployment

### Vercel (Recommended)

1. Push to GitHub
2. Import project in Vercel
3. Deploy automatically

### GitHub Pages

1. Build the static export: \`npm run export\`
2. Push \`out/\` directory to \`gh-pages\` branch
3. Enable GitHub Pages in repository settings

### Netlify

1. Connect your repository
2. Set build command: \`npm run build\`
3. Set publish directory: \`out\`

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

**Ahosan Habib Likhon**

- GitHub: [@ahosanhabiblikhon](https://github.com/ahosanhabiblikhon)
- Facebook: [Ahosan Habib Likhon](https://www.facebook.com/ahosan.habib.likhon.nur)
- Instagram: [@ahosan_habib_likhon](https://www.instagram.com/ahosan_habib_likhon)
- Photography: [@ahosan.photo](https://instagram.com/ahosan.photo)
- LinkedIn: [Md Ahosan Habib Likhon](https://www.linkedin.com/in/md-ahosan-habib-likhon-84707a295/)

---

Built with ❤️ using Next.js, TypeScript, and Tailwind CSS
