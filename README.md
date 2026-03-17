# Ahmed Atif 3D Portfolio

A premium, interactive 3D portfolio website for a graphic designer. Built with React, Vite, Three.js, React Three Fiber, and GSAP. Inspired by Apple product pages and Behance case studies.

## ✨ Features

### 3D Components
- **Hero Section**: Full-screen 3D canvas with animated text and floating particles
- **Cinematic Lighting**: Dynamic lighting with gold and white ambient lights
- **Interactive Particles**: Animated particle system in the background
- **Smooth Animations**: Using GSAP for fluid transitions and camera movements

### Main Sections
1. **3D Hero** - Fullscreen cinematic introduction
2. **Projects** - Featured work with clickable case studies
3. **Skills** - Animated skill bars and tools showcase
4. **About** - Designer biography and statistics
5. **Contact** - Contact form with social links

### Project Pages
- Detailed case studies for each project
- Challenge, Concept, Process, and Results sections
- Tools and technologies used
- Beautiful typography and layout

## 🛠️ Tech Stack

- **React** - Component framework
- **Vite** - Fast build tool
- **Three.js** - 3D graphics library
- **React Three Fiber** - React renderer for Three.js
- **@react-three/drei** - Useful React Three Fiber helpers
- **GSAP** - Animation library

## 🚀 Getting Started

### Prerequisites
- Node.js 16+ 
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

The application will be available at `http://localhost:5174/`

## 📁 Project Structure

```
src/
├── components/
│   ├── Hero3D.jsx              # 3D hero scene
│   ├── FloatingText.jsx         # Animated 3D text
│   ├── Particles.jsx            # Particle system
│   ├── ProjectCards.jsx         # 3D project cards
│   ├── CameraRig.jsx            # Camera animation handler
│   ├── About.jsx                # About section
│   ├── Skills.jsx               # Skills section
│   └── Contact.jsx              # Contact form section
├── pages/
│   └── ProjectDetail.jsx        # Project case study page
├── styles/
│   ├── About.css                # About section styles
│   ├── Skills.css               # Skills section styles
│   ├── Contact.css              # Contact section styles
│   └── ProjectDetail.css        # Project detail styles
├── data/
│   └── projects.js              # Projects and skills data
├── App.jsx                      # Main app component
├── App.css                      # Main styles
└── index.css                    # Global styles
```

## 🎨 Design System

### Color Palette
- **Background**: `#0a0a0a` (Deep Black)
- **Accent**: `#d6a86c` (Warm Gold)
- **Text**: `#ffffff` (White)
- **Secondary**: `rgba(255, 255, 255, 0.6)` (Muted White)

### Typography
- Font Family: SF Pro Display, Inter, Raleway, Arial
- Large headings: 3rem (hero) to 1.3rem (cards)
- Premium Apple-inspired design

## 📱 Responsive Design

- Desktop: Full 3D experience with all interactive elements
- Tablet: Optimized layout with adjusted spacing
- Mobile: Simplified 3D rendering for performance

## 🎬 Key Animations

- **Text Animation**: Floating motion with slight rotation
- **Particles**: Continuous rotation and movement
- **Project Cards**: Hover scale and glow effects
- **Section Transitions**: Fade-in animations on scroll
- **Form Elements**: Interactive hover states

## 📝 Customization

### Edit Projects
Modify `src/data/projects.js` to add or update projects.

### Update Colors
Change the CSS variables in color sections of each CSS file

### Add More Sections
Create new components in `src/components/` and import them in `App.jsx`.

## 🚀 Production

```bash
# Build for production
npm run build

# The dist/ folder contains optimized production files
```

## 📄 License

MIT - Feel free to use this project for personal or commercial purposes.

## 👨‍💻 Author

Ahmed Atif - Graphic Designer

---

**Built with ❤️ using React, Three.js, and creativity**
