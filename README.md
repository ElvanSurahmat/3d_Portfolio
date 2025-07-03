# 3d_Portfolio# 3D Portfolio

A modern, interactive 3D portfolio website built with React, Three.js, GSAP, and TailwindCSS.  
Showcase your work, skills, and experience with engaging animations and 3D visuals.

## Features

- **Animated Hero Section** with 3D room model and floating particles
- **Work Showcase** with animated project cards
- **Skills/Tech Stack** grid with animated icons
- **Professional Experience** timeline with scroll-triggered animations
- **Customer Testimonials** with glowing card effects
- **Contact Form** with EmailJS integration
- **Responsive Design** for all devices
- **Smooth Animations** using GSAP and Three.js
- **Logo Marquee** and feature highlights

## Demo

> _Add a link to your deployed site here if available_

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/3d_Portfolio.git
   cd 3d_Portfolio
   ```

2. **Install dependencies:**

   ```sh
   npm install
   # or
   yarn install
   ```

3. **Set up EmailJS (for contact form):**
   - Create a `.env` file in the root directory.
   - Add your EmailJS credentials:
     ```
     VITE_APP_EMAILJS_SERVICE_ID=your_service_id
     VITE_APP_EMAILJS_TEMPLATE_ID=your_template_id
     VITE_APP_EMAILJS_PUBLIC_KEY=your_public_key
     ```

### Running the Project

Start the development server:

```sh
npm run dev
# or
yarn dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Building for Production

```sh
npm run build
# or
yarn build
```

Preview the production build:

```sh
npm run preview
# or
yarn preview
```

## Project Structure

```
├── public/
│   └── images/, models/      # Static assets (images, 3D models)
├── src/
│   ├── components/           # Reusable UI components
│   ├── constants/            # Data/constants (skills, testimonials, etc.)
│   ├── sections/             # Page sections (Hero, Experience, Contact, etc.)
│   ├── App.jsx               # Main app component
│   ├── main.jsx              # Entry point
│   └── index.css             # Tailwind & custom styles
├── index.html
├── package.json
└── vite.config.js
```

## Customization

- **Content:**  
  Update your skills, experience, testimonials, and images in [`src/constants/index.js`](src/constants/index.js).
- **3D Models:**  
  Place your `.glb` models in `public/models/` and reference them in the constants or components.
- **Styling:**  
  Modify Tailwind classes or add custom styles in [`src/index.css`](src/index.css).

## Dependencies

- [React](https://react.dev/)
- [Three.js](https://threejs.org/)
- [@react-three/fiber](https://docs.pmnd.rs/react-three-fiber/)
- [@react-three/drei](https://docs.pmnd.rs/drei/)
- [GSAP](https://gsap.com/)
- [TailwindCSS](https://tailwindcss.com/)
- [EmailJS](https://www.emailjs.com/) (for contact form)

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---
