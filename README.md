# Lakeview University Website (React + Vite)

## Run
    npm install
    npm run dev

Open the local address shown in the terminal (usually http://localhost:5173).

## Build for production
    npm run build
    npm run preview

## Structure
- src/components: Header, Navbar, Button, Footer, PageBanner, ServiceCard, FormMessage (reusable, props-driven)
- src/pages: Home, About, Services, Registration, Gallery, Contact
- src/data.js: navigation links, services, gallery items, programmes
- src/index.css: responsive styling (desktop, tablet, mobile)
- public/images: six SVG images used on Home, About and Gallery

## React features used
- useState: mobile menu (Header), expandable service cards (Services), registration form state and validation, gallery lightbox, contact form
- Props: Header, Navbar, Button, ServiceCard, FormMessage, PageBanner
- Event handling: onClick, onChange, onSubmit
- Routing: react-router-dom
