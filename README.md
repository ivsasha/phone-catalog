# Phone Catalog

A modern, fully responsive e-commerce single-page application (SPA) featuring a comprehensive phone catalog with shopping cart functionality, favorites system, and detailed product browsing capabilities.

## 🚀 [Live Demo](https://ivsasha.github.io/phone-catalog/)

## 📱 Project Description

This is a feature-rich phone catalog application that provides users with an intuitive shopping experience. Browse through a wide selection of smartphones, add items to your cart, save favorites, and enjoy a seamless responsive design that works perfectly on all devices.

## 🛠 Technologies Used

- **React** - Component-based user interface library
- **TypeScript** - Type-safe JavaScript development
- **SCSS** - Modern CSS preprocessor for advanced styling
- **React Router** - Client-side routing and navigation
- **Local Storage** - Data persistence for cart and favorites
- **GitHub Pages** - Deployment and hosting
- **ESLint** - Code quality and consistency

## 🚀 Getting Started

Follow these instructions to get the project running locally on your machine.

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ivsasha/phone-catalog.git
   cd phone-catalog
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```
3. **Install Swiper**
   ```
   npm list swiper
   ```
4. **Install lodash**
   ```
   npm install lodash.debounce
   ```
5. **Run the project locally:**
   ```bash
   npm start
   # or
   yarn start
   ```

The application will be available at `http://localhost:3000`.

### Build for Production

```bash
npm run build
# or
yarn build
```

### Deploy to GitHub Pages

```bash
npm run deploy
# or
yarn deploy
```

## ✨ Key Features

- **Product Catalog** - Browse through an extensive collection of smartphones with detailed specifications
- **Advanced Filtering** - Filter products by brand, price range, features, and more
- **Shopping Cart** - Add, remove, and manage items in your shopping cart
- **Favorites System** - Save your favorite phones for quick access later
- **Product Search** - Find specific phones quickly with the search functionality
- **Responsive Design** - Optimized experience across desktop, tablet, and mobile devices
- **Product Details** - Detailed product pages with high-quality images and specifications
- **Local Storage** - Cart and favorites data persist between sessions
- **Modern UI/UX** - Clean, intuitive interface with smooth animations
- **TypeScript Integration** - Type-safe development for better code quality

## 📱 Pages & Components

- **Home Page** - Featured products and categories overview
- **Catalog Page** - Complete product listing with filtering options
- **Product Detail Page** - Comprehensive product information and images
- **Shopping Cart** - Review and manage selected items
- **Favorites** - Quick access to saved products
- **Search Results** - Dynamic search functionality

## 📁 Project Structure

```
phone-catalog/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   ├── types/
│   ├── utils/
│   ├── data/
│   └── App.tsx
├── package.json
└── README.md
```

## 🎨 Styling

The project uses SCSS for styling with:
- Modern CSS Grid and Flexbox layouts
- Responsive breakpoints for all device sizes
- Custom CSS variables for consistent theming
- Smooth animations and transitions
- Mobile-first design approach
- [Design Figma](https://www.figma.com/file/BUusqCIMAWALqfBahnyIiH/Phone-catalog-(V2)-Original-Dark)

## 📊 Data Management

- Product data stored in JSON format
- Local Storage for cart persistence
- State management using React hooks
- TypeScript interfaces for type safety

