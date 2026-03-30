# CORE NEXUS FF Manager - Free Fire Tournament Management System

CORE NEXUS FF Manager is a professional, high-performance web application designed for Free Fire tournament organizers. It provides a comprehensive suite of tools to manage team registrations, calculate scores automatically across multiple matches, and generate high-quality, exportable leaderboards with a distinct gamer aesthetic.

## 🚀 Features

- **Multi-Group Management:** Organize tournaments into multiple groups (A, B, C, D, E, F, Especial, Finals, 3 Salas).
- **Automated Scoring:** Enter placement and kill data; the system automatically calculates total points based on official tournament rules.
- **Dynamic Leaderboards:** Real-time ranking updates as data is entered.
- **Customizable Themes:** Choose between different design templates (Standard, Cyber, Minimal) to match your tournament's branding.
- **Asset Management:** Upload custom logos for teams, tournament branding, and background images.
- **Sponsor Integration:** Dedicated section to manage and display official tournament partners.
- **High-Quality Exports:** Generate and download professional-grade images directly from the browser for:
  - Results Boards
  - Top 3 Winners Banners
  - Confirmed Teams Lists
  - Tournament Presentation/Info
  - Sponsor Showcases
- **Offline Persistence:** Uses a hybrid approach of LocalStorage and IndexedDB to ensure your data is saved locally in your browser.

## 🛠️ Tech Stack

- **Frontend:** HTML5, Vanilla JavaScript (ES6+).
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (via Play CDN).
- **Typography:** [Google Fonts](https://fonts.google.com/) (Inter & Orbitron).
- **Persistence:** IndexedDB & LocalStorage.
- **Rendering:** Native HTML5 Canvas API for image generation.
- **Build Tool:** [Vite](https://vitejs.dev/) (for development and bundling).

## 📁 Project Structure

```text
├── components/           # UI Component definitions (Button, Leaderboard, etc.)
├── services/             # Data management and persistence logic
├── migrated_prompt_history/ # History of project evolution
├── App.tsx               # Main React-like entry (if applicable)
├── index.html            # Primary application entry and core logic
├── index.css             # Global styles and Tailwind imports
├── types.ts              # TypeScript type definitions
├── metadata.json         # Application metadata and permissions
└── package.json          # Project dependencies and scripts
```

## 🚦 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository or download the source code.
2. Install dependencies:
   ```bash
   npm install
   ```

### Development

Run the development server:
```bash
npm run dev
```
The application will be available at `http://localhost:3000`.

### Build

To create a production-ready build:
```bash
npm run build
```
The output will be in the `dist/` directory.

## 📖 Usage Guide

1. **Group Selection:** Use the top horizontal bar to switch between tournament groups.
2. **Data Entry:** Navigate to the **Data Entry** tab to add teams, upload logos, and enter match results (Placement and Kills).
3. **Settings:** Use the **Settings** tab to customize the tournament name, date, prizes, and upload branding assets (Logo, Background, Sponsors).
4. **Exporting:** Go to the **Results** tab to view the generated boards. Click the "SAVE" buttons to download high-resolution images for social media sharing.

---

*Developed for the Free Fire competitive community.*
