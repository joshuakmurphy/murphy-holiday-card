# Murphy Family Holiday Card 2025 ❄️

A beautiful, interactive Winter Wonderland holiday card built with React. Features animated snowflakes, family member profiles, and a warm seasonal design.

## 🌐 Live Demo

Visit the live site: [virginiaisformurphys.com](https://virginiaisformurphys.com)

## ✨ Features

- **Winter Wonderland Theme** - Gradient backgrounds, animated snowflakes, and festive design
- **Interactive Profiles** - Click on family members to view their stories and 2025 highlights
- **Responsive Design** - Works beautifully on desktop, tablet, and mobile devices
- **Smooth Animations** - Hover effects, transitions, and falling snowflakes
- **Custom Domain** - Deployed with GitHub Pages and custom domain support

## 🛠️ Tech Stack

- **React 18** - Modern React with hooks
- **Vite** - Fast build tool and dev server
- **CSS-in-JS** - Inline styles for component-scoped styling
- **GitHub Pages** - Free hosting with custom domain support
- **GitHub Actions** - Automated deployment pipeline

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm installed
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

### Build for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

## 📝 Customization

### Updating Family Members

Edit the `familyMembers` array in `src/App.jsx`:

```javascript
const familyMembers = [
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

### Changing Colors and Styles

The component uses inline styles. Update colors, fonts, and spacing directly in `src/App.jsx`.

### Updating Year or Location

Update the footer section in `src/App.jsx`:

```javascript
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
│   └── CNAME              # Custom domain configuration
├── src/
│   ├── App.jsx            # Main component with all logic
│   ├── App.css            # Component styles
│   ├── main.jsx           # React entry point
│   └── index.css          # Global styles
├── .github/
│   └── workflows/
│       └── deploy.yml     # GitHub Actions deployment
├── index.html             # HTML template
├── vite.config.js         # Vite configuration
└── package.json           # Dependencies and scripts

```

## 🎨 Design Features

- Gradient backgrounds for depth
- Animated falling snowflakes
- Shimmer effects on decorative elements
- Hover transitions on interactive elements
- Responsive grid layout for family members
- Custom color themes per family member

## 📄 License

This is a personal project. Feel free to use it as inspiration for your own holiday cards!

## 🙏 Acknowledgments

Built with React and Vite for a fast, modern development experience.

---

Made with love in Virginia ❤️
