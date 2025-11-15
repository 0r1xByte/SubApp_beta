# Basketball Rotation Manager 🏀

A modern web application for managing basketball team rotations, player substitutions, and game time tracking. Built with React, TypeScript, and Tailwind CSS.

![Basketball Rotation Manager](https://img.shields.io/badge/React-18.3.1-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-blue)
![Vite](https://img.shields.io/badge/Vite-5.4.2-purple)
![License](https://img.shields.io/badge/license-MIT-green)

## 🌐 Live Demo

Visit the live application: [https://0r1xbyte.github.io/SubApp_beta/](https://0r1xbyte.github.io/SubApp_beta/)

## ✨ Features

### Setup Phase
- **Player Management**: Add up to 15 players to your roster
- **Custom Roles**: Define custom player roles (e.g., Shooter, Playmaker, Rebounder)
- **Starting Five Selection**: Choose your starting lineup from your roster
- **Game Plan Creation**: Pre-plan substitutions for each interval in both halves

### Live Game Management
- **Real-time Clock**: Track game time with play/pause controls
- **Automatic Substitutions**: Execute pre-planned substitutions at set intervals
- **Manual Substitutions**: Make on-the-fly substitutions during the game
- **Player Statistics**: Track playing time for each player
- **Position Tracking**: Monitor which players are on court at each position (PG, SG, SF, PF, C)
- **Bench Management**: View available bench players with their stats

### Customization
- **Configurable Game Settings**:
  - Half length (5-30 minutes)
  - Substitution intervals (1-10 minutes)
- **Toggle position labels** for cleaner interface
- **Two-half game structure** with separate game plans

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/0r1xByte/SubApp_beta.git
cd SubApp_beta/project
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 📦 Build

To build the application for production:

```bash
npm run build
```

The built files will be in the `dist` directory.

## 🛠️ Tech Stack

- **Frontend Framework**: React 18.3.1
- **Language**: TypeScript 5.5.3
- **Build Tool**: Vite 5.4.2
- **Styling**: Tailwind CSS 3.4.1
- **Icons**: Lucide React 0.344.0
- **Backend (Optional)**: Supabase 2.57.4

## 📁 Project Structure

```
SubApp_beta/
├── project/
│   ├── src/
│   │   ├── App.tsx          # Main application component
│   │   ├── main.tsx         # Application entry point
│   │   └── index.css        # Global styles
│   ├── public/              # Static assets
│   ├── index.html           # HTML template
│   ├── vite.config.ts       # Vite configuration
│   ├── tailwind.config.js   # Tailwind CSS configuration
│   └── package.json         # Dependencies and scripts
└── .github/
    └── workflows/
        └── deploy.yml       # GitHub Actions deployment workflow
```

## 🎮 How to Use

1. **Add Players**: Enter player names (minimum 5 required)
2. **Configure Game Settings**: Set half length and substitution intervals
3. **Assign Roles** (Optional): Create and assign custom roles to players
4. **Select Starting Five**: Choose your starting lineup
5. **Create Game Plan**: Pre-plan substitutions for each interval
6. **Start Game**: Begin tracking with the game clock
7. **Manage Live**: Use play/pause controls and manual substitutions as needed

## 🚢 Deployment

This project is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Setup GitHub Pages

1. Go to your repository settings: `https://github.com/0r1xByte/SubApp_beta/settings/pages`
2. Under "Source", select **GitHub Actions**
3. Push changes to the `main` or `master` branch to trigger automatic deployment

The app will be available at: `https://0r1xbyte.github.io/SubApp_beta/`

## 📜 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint
- `npm run typecheck` - Run TypeScript type checking

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**0r1xByte**

- GitHub: [@0r1xByte](https://github.com/0r1xByte)

## 🙏 Acknowledgments

- Built with [Vite](https://vitejs.dev/)
- Icons by [Lucide](https://lucide.dev/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)

