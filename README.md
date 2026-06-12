# CodexPlay Landing Page

A modern, responsive gaming platform landing page built with HTML, Tailwind CSS, and JavaScript. Featuring a retro pixel-art aesthetic, dark mode support, and interactive e-commerce functionality.

![CodexPlay](https://img.shields.io/badge/CodexPlay-Landing%20Page-purple)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📝 Description

CodexPlay is a gaming discovery platform landing page designed to showcase games with an immersive, retro-inspired user interface. The project features a pixel-art design system, smooth animations, and a fully functional shopping cart system. Built as part of a hands-on internship, emphasizing real-world problem solving, performance optimization, and modern UI/UX practices.

## ✨ Features

### Design & UI
- **Retro Pixel-Art Aesthetic** - Custom pixel-style borders, shadows, and grid overlay backgrounds
- **Dark Mode Support** - Toggle between light and dark themes with localStorage persistence
- **Responsive Design** - Fully responsive layout optimized for mobile, tablet, and desktop
- **Smooth Animations** - Float animations, scroll reveals, and modal transitions
- **Custom Typography** - Silkscreen (pixel font), Outfit (display), and DM Sans (body) fonts

### Interactive Elements
- **Shopping Cart System** - Add games to cart, view cart modal, remove items, and checkout
- **Confirmation Modals** - Interactive dialogs for add-to-cart and buy-now actions
- **Mobile Navigation** - Collapsible hamburger menu for mobile devices
- **Scroll Effects** - Navbar transforms on scroll, active section highlighting
- **Smooth Scrolling** - Anchor links with offset for sticky navbar

### Sections
- **Hero Section** - Eye-catching headline with CTA buttons and animated background shapes
- **Games Grid** - Display of 6 games with images, descriptions, prices, and purchase buttons
- **Features Section** - 3-column layout highlighting platform features
- **How It Works** - Step-by-step guide with numbered badges
- **Testimonials** - Horizontal scrollable review cards with user ratings
- **Footer** - Links, social icons, and copyright information

## 🛠 Tech Stack

- **HTML5** - Semantic markup and structure
- **Tailwind CSS v3.4.17** - Utility-first CSS framework
- **JavaScript (Vanilla)** - Interactive functionality and DOM manipulation
- **Google Fonts** - Outfit, DM Sans, and Silkscreen fonts
- **CSS Custom Properties** - Theme variables for dark mode

## 📁 Folder Structure

```
Landing_Page/
├── assets/                    # Static assets
│   ├── GTA VII.jpg           # Game thumbnail
│   ├── Minecraft.webp        # Game thumbnail
│   ├── Mystic Realms.jpg     # Game thumbnail
│   ├── Pixel Odyssey.png     # Game thumbnail
│   ├── Shadow Tactics.webp   # Game thumbnail
│   └── Velocity Rush.jpg    # Game thumbnail
├── dist/
│   └── output.css            # Compiled/minified CSS output
├── src/
│   ├── input.css             # Tailwind CSS source with custom styles
│   └── main.js               # JavaScript functionality
├── index.html                # Main HTML file
├── package.json              # Project dependencies and scripts
├── package-lock.json         # Lock file for dependencies
├── tailwind.config.js        # Tailwind CSS configuration
└── README.md                 # Project documentation
```

## 🎨 Layout & Section Breakdown

### Hero Section
- Full-width hero with gradient text and pixel-style badge
- Primary and secondary CTA buttons
- Animated floating 2D shapes in background
- Pixel grid overlay texture

### Games Section
- Responsive grid layout (1 column mobile, 2 tablet, 3 desktop)
- 6 game cards with:
  - Game thumbnail images
  - Title and description
  - Price display
  - "Add to Cart" and "Buy Now" buttons
- Hover effects on cards

### Features Section
- 3-column feature cards
- Custom icon containers with gradient backgrounds
- Pixel-style card borders and shadows
- Hover transform effects

### How It Works Section
- 3-step process with numbered badges
- Step connector lines (desktop only)
- Icon and description for each step

### Testimonials Section
- Horizontal scrollable card layout
- Snap scrolling for mobile
- 5-star rating display
- User avatars and credentials

### Footer
- Multi-column layout with links
- Social media icons
- Copyright information

## ⚙️ How It Works

### JavaScript Functionality (`main.js`)

1. **Cart System**
   - Maintains cart array in memory
   - `renderCart()` function updates cart UI, count, and total
   - Add/remove items with confirmation modals
   - Checkout clears cart and shows success message

2. **Modal System**
   - Cart modal for viewing items
   - Add-to-cart confirmation modal
   - Buy-now confirmation modal
   - Fade-in/fade-out animations

3. **Theme Management**
   - Dark mode toggle with localStorage persistence
   - System preference detection on page load
   - Prevents dark mode flicker with inline script

4. **Navigation**
   - Mobile menu toggle with aria-expanded states
   - Navbar scroll effect (adds shadow on scroll)
   - Active section highlighting using IntersectionObserver
   - Smooth anchor scrolling with offset

5. **Animations**
   - Scroll reveal animations using IntersectionObserver
   - Hero entrance animation on page load
   - Floating background shapes (CSS animations)

## 🚀 Setup & Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Landing_Page
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Build CSS**
   ```bash
   npm run build
   ```

   Or for development with watch mode:
   ```bash
   npm run watch:css
   ```

4. **Open in browser**
   - Open `index.html` directly in your browser
   - Or use a local server (e.g., Live Server extension in VS Code)

## 📖 Usage

### Viewing the Site
1. Open `index.html` in a web browser
2. Navigate through sections using the navbar
3. Toggle dark mode using the sun/moon icon
4. Add games to cart and complete checkout flow
5. Test responsive design by resizing browser

### Customization
- **Colors**: Modify CSS variables in `src/input.css` under `:root` and `.dark`
- **Fonts**: Change font families in `tailwind.config.js`
- **Content**: Update text and images in `index.html`
- **Styles**: Add custom Tailwind classes in `src/input.css`

## 🖼️ Screenshots

### Hero Section
![Hero Section](/assets/Img1.png)

### Games Grid
![Games Section](/assets/Img2.png)
![Games Section](/assets/Img3.png)

### Dark Mode
![Dark Mode](/assets/Img4.png)

### Mobile View
![Mobile View](/assets/Img5.png)

## 🔮 Future Improvements

- [ ] Backend integration for real cart persistence
- [ ] User authentication and account system
- [ ] Game search and filter functionality
- [ ] Category-based game organization
- [ ] Payment gateway integration
- [ ] Game detail pages with more information
- [ ] User reviews and ratings system
- [ ] Wishlist functionality
- [ ] Social sharing features
- [ ] Performance optimization (lazy loading, image optimization)
- [ ] Accessibility improvements (ARIA labels, keyboard navigation)
- [ ] Unit and integration tests

## 👤 Author

**Krish**
- Frontend Development Internship Project
- Built with modern web technologies and best practices

## 🧩 Internship Note

Built as part of a hands-on internship, emphasizing real-world problem solving, performance optimization, and modern UI/UX practices.

---

## 📄 License

This project is for educational and portfolio purposes.

## 🤝 Contributing

This is a portfolio project. For suggestions or improvements, please open an issue or contact the author.

---

**© 2026 Krish | Built with ❤️ and Code | All Rights Reserved**
