# Spylt-website

Recreating a website frontend that has won an Awwwards Site of the Day, using GSAP, ReactJS, and Tailwind CSS.

## пїЅ Live Demo

Check out the live demo here: **[https://h1690066-star.github.io/Spylt-website/](https://h1690066-star.github.io/Spylt-website/)**

## пїЅрџЋЁ Description

This project is a clone of an Awwwards-awarded website (Site of the Day). It showcases smooth and modern animations with a clean and responsive user interface. The site features multiple dynamic sections including product benefits, a flavor gallery, and customer testimonials.

## рџљЂ Features

- **Advanced GSAP Animations** : Smooth and performant animations for an exceptional user experience
- **Responsive Design** : Interface adapted to all devices (mobile, tablet, desktop)
- **Dynamic Sections** : Hero, Benefits, Flavors, Nutrition, Testimonials, Messages
- **Smooth Navigation** : Interactive navigation bar
- **Multimedia Gallery** : Integrated images and videos
- **Interactive Slider** : Flavor selection with intuitive navigation

## рџ› пёЏ Technologies Used

- **React 19** : JavaScript library for building user interfaces
- **Vite** : Ultra-fast build tool for development
- **Tailwind CSS 4** : Utility-first CSS framework for styling
- **GSAP 3** : Professional animation library
- **React Responsive** : Media queries management in React
- **ES Modules** : Modern JavaScript syntax

## рџ“¦ Installation

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/h1690066-star/Spylt-website.git
   cd Spylt-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

## рџ“ќ Available Scripts

```bash
# Start the development server
npm run dev

# Build for production
npm run build

# Check code linting
npm run lint

# Preview the production build
npm run preview
```

## рџ“Ѓ Project Structure

```
src/
в”њв”Ђв”Ђ components/          # Reusable components
в”‚   в”њв”Ђв”Ђ ClipPathTitle.jsx
в”‚   в”њв”Ђв”Ђ FlavorSlider.jsx
в”‚   в”њв”Ђв”Ђ FlavorTitle.jsx
в”‚   в”њв”Ђв”Ђ NavBar.jsx
в”‚   в””в”Ђв”Ђ VideoPinSection.jsx
в”њв”Ђв”Ђ sections/           # Main page sections
в”‚   в”њв”Ђв”Ђ HeroSection.jsx
в”‚   в”њв”Ђв”Ђ BenefitSection.jsx
в”‚   в”њв”Ђв”Ђ FlavorSection.jsx
в”‚   в”њв”Ђв”Ђ NutritionSection.jsx
в”‚   в”њв”Ђв”Ђ TestimonialSection.jsx
в”‚   в”њв”Ђв”Ђ MessageSection.jsx
в”‚   в””в”Ђв”Ђ FooterSection.jsx
в”њв”Ђв”Ђ constants/          # Constants and data
в”њв”Ђв”Ђ App.jsx            # Main component
в”њв”Ђв”Ђ main.jsx           # Entry point
в””в”Ђв”Ђ index.css          # Global styles
```

## рџЋЇ Main Sections

- **HeroSection** : Landing section with introduction animation
- **BenefitSection** : Product benefits presentation
- **FlavorSection** : Interactive flavor gallery with slider
- **NutritionSection** : Nutritional information
- **TestimonialSection** : Customer testimonials
- **MessageSection** : Call-to-action or promotional message
- **FooterSection** : Footer with links and information

## рџЊђ Deployment

To deploy the production version:

```bash
npm run build
```

Compiled files will be available in the `dist/` folder.

## рџ“± Responsiveness

The project uses Tailwind CSS and React Responsive to ensure an optimal experience on:
- Mobile devices (320px and above)
- Tablets (768px and above)
- Desktops (1024px and above)

## рџ’Ў Development Notes

- GSAP animations are integrated via `@gsap/react` for better React integration
- Images and videos are stored in the `public/` folder
- Custom fonts are imported from Google Fonts

