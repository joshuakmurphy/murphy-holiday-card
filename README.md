# Murphy Family Holiday Card 2025 ❄️

A beautiful, interactive Winter Wonderland holiday card built with React 19 and TypeScript. Features animated snowflakes, family member profiles, accessible design, centralized theming, and modern development tooling.

## 🌐 Live Demo

Visit the live site: [virginiaisformurphys.com](https://virginiaisformurphys.com)

## ✨ Features

- **Winter Wonderland Theme** - Gradient backgrounds, animated snowflakes, and festive design
- **Interactive Profiles** - Click on family members to view their stories and 2025 highlights
- **TypeScript** - Full type safety throughout the application
- **React 19** - Latest React with compiler optimizations and improved performance
- **Accessible** - WCAG 2.1 AA compliant with ARIA labels, keyboard navigation, and semantic HTML
- **Theme System** - Centralized colors, fonts, and spacing for easy customization
- **Code Quality** - ESLint and Prettier for consistent, error-free code
- **Responsive Design** - Works beautifully on desktop, tablet, and mobile devices
- **Custom Domain** - Deployed with GitHub Pages and custom domain support

## 🛠️ Tech Stack

- **React 19.2** - Latest React with compiler optimizations and new features
- **TypeScript 5** - Full type safety and better developer experience
- **Vite 7.2** - Lightning-fast build tool with 45% faster cold starts
- **ESLint 9** - Code quality and best practices enforcement
- **Prettier 3** - Consistent code formatting
- **Theme Constants** - Centralized design system for maintainability
- **GitHub Pages** - Free hosting with custom domain support
- **GitHub Actions** - Automated deployment pipeline

## 🚀 Getting Started

### Prerequisites

- Node.js 20.19+ or 22.12+ (required for Vite 7)
- npm installed
- Git installed

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/joshuakmurphy/murphy-holiday-card.git
cd murphy-holiday-card
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser to `http://localhost:5173`

### Available Scripts

```bash
npm run dev          # Start development server (Vite 7 - fast startup!)
npm run build        # Build for production
npm run preview      # Preview production build
npm run lint         # Check code for errors
npm run lint:fix     # Auto-fix linting issues
npm run format       # Format code with Prettier
npm run format:check # Verify code is formatted
```

### Build for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

## 📝 Customization

### Updating Family Members

Edit the `familyMembers` array in `src/data/familyMembers.ts`:

```typescript
export const familyMembers: FamilyMember[] = [
  {
    id: 'unique-id',
    name: 'Name',
    fullName: 'Full Name',
    title: 'Title/Role',
    emoji: '👨', // Any emoji
    color: '#4A90E2', // Hex color for theme
    highlights: [
      'Achievement 1',
      'Achievement 2',
      // Add more highlights
    ],
    story: 'A brief story about the year...',
    quote: 'A memorable quote'
  },
  // Add more family members
];
```

### Changing Colors and Themes

Update the theme constants in `src/constants/theme.ts`:

```typescript
export const COLORS = {
  winterBlue: '#2C5F7C',
  lightBlue: '#4A90E2',
  purple: '#9B59B6',
  // ... customize colors
};

export const GRADIENTS = {
  background: 'linear-gradient(...)',
  hero: 'linear-gradient(...)',
  // ... customize gradients
};
```

### Updating Year or Location

Update the footer in `src/components/Footer.tsx`:

```typescript
The Murphy Family • Richmond, Virginia • 2025
```

## 🌍 Deployment

This project is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Deploy to GitHub Pages

1. Push to the `main` branch
2. GitHub Actions automatically builds and deploys
3. Site is live at your configured custom domain

### Custom Domain Setup

1. Add a `CNAME` file in the `public` directory with your domain
2. Configure DNS records with your domain provider:
   - 4 A records pointing to GitHub Pages IPs
   - CNAME record for www subdomain
3. Enable custom domain in GitHub Pages settings
4. Enable "Enforce HTTPS" once SSL certificate is provisioned

## 📁 Project Structure

```
murphy-holiday-card/
├── public/
│   └── CNAME                    # Custom domain configuration
├── src/
│   ├── components/              # React components
│   │   ├── FamilyMemberCard.tsx # Individual family member card
│   │   ├── Footer.tsx           # Footer component
│   │   ├── Header.tsx           # Header with title
│   │   ├── HomePage.tsx         # Main landing page
│   │   ├── ProfilePage.tsx      # Individual profile view
│   │   └── Snowflake.tsx        # Animated snowflake
│   ├── constants/
│   │   └── theme.ts             # Theme constants (colors, fonts, spacing)
│   ├── data/
│   │   └── familyMembers.ts     # Family member data
│   ├── types/
│   │   └── index.ts             # TypeScript type definitions
│   ├── App.tsx                  # Main app component
│   ├── App.css                  # Component styles & accessibility
│   ├── main.tsx                 # React entry point
│   └── index.css                # Global styles
├── .github/
│   └── workflows/
│       └── deploy.yml           # GitHub Actions deployment
├── eslint.config.js             # ESLint configuration
├── .prettierrc                  # Prettier configuration
├── tsconfig.json                # TypeScript configuration
├── vite.config.ts               # Vite configuration
└── package.json                 # Dependencies and scripts
```

## 🎨 Design Features

- **Gradient backgrounds** for visual depth
- **Animated falling snowflakes** with CSS keyframes
- **Shimmer effects** on decorative elements
- **Smooth hover transitions** on interactive elements
- **Responsive grid layout** for family members
- **Custom color themes** per family member
- **Keyboard navigation** with visible focus indicators
- **Semantic HTML** for better accessibility
- **ARIA labels** for screen readers

## ♿ Accessibility Features

- **WCAG 2.1 AA Compliant** - Semantic HTML and ARIA labels
- **Keyboard Navigation** - All interactive elements accessible via keyboard
- **Focus Indicators** - Clear visual feedback for keyboard users
- **Screen Reader Support** - Proper labels and landmarks
- **Semantic Landmarks** - Header, nav, section, article tags

## 🧰 Code Quality & Performance

- **TypeScript** - Full type safety and IntelliSense support
- **ESLint** - Catches bugs and enforces best practices
- **Prettier** - Automatic code formatting
- **React 19 Compiler** - Automatic optimizations for better performance
- **Vite 7** - 45% faster dev server startup, improved build times
- **React Best Practices** - Hooks, component composition
- **No Console Logs** - Clean production code (warnings only)

## ⚡ Performance

- **Dev Server**: ~327ms startup time (Vite 7)
- **Production Build**: Sub-second builds
- **Bundle Size**: Optimized with tree-shaking and code splitting
- **React 19**: Built-in compiler optimizations

## 📄 License

This is a personal project. Feel free to use it as inspiration for your own holiday cards!

## 🙏 Acknowledgments

Built with React 19, TypeScript, and Vite 7 for a blazing-fast, type-safe, and modern development experience.

---

Made with love in Virginia ❤️
