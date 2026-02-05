# ShopHub - Premium E-Commerce Website

A stunning, modern, and fully responsive e-commerce website frontend inspired by Amazon. Built with vanilla HTML, CSS, and JavaScript featuring premium design aesthetics, smooth animations, and comprehensive functionality.

## 🌟 Features

### Design & UI
- **Premium Modern Design** - Sleek, professional interface with vibrant colors and glassmorphism effects
- **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- **Smooth Animations** - Micro-animations and transitions for enhanced user experience
- **Dark Theme Navigation** - Professional Amazon-style navigation bar
- **Hero Slider** - Auto-rotating banner with smooth transitions
- **Glassmorphism Effects** - Modern frosted glass UI elements

### Pages
1. **Homepage (index.html)**
   - Auto-rotating hero slider
   - Featured products section
   - Trending products section
   - Category showcase
   - Deals section
   - Newsletter subscription
   - Comprehensive footer

2. **Products Page (products.html)**
   - Advanced filtering system (category, price, rating, discount)
   - Multiple sort options
   - Grid/List view toggle
   - Search functionality
   - Pagination
   - Active filter tags

3. **Shopping Cart (cart.html)**
   - Cart item management
   - Quantity controls
   - Promo code system
   - Order summary with tax calculation
   - Free shipping threshold
   - Recommended products
   - Empty cart state

### Functionality
- **Product Management** - Add to cart, wishlist, quick view
- **Shopping Cart** - Full cart functionality with quantity controls
- **Wishlist** - Save favorite products
- **Search** - Product search across pages
- **Filters** - Advanced filtering and sorting
- **Promo Codes** - Discount code system (SAVE10, SAVE20, WELCOME, FIRST50)
- **Local Storage** - Persistent cart and wishlist
- **Notifications** - Toast notifications for user actions
- **Responsive Navigation** - Mobile-friendly menu

## 🎨 Design System

### Color Palette
- **Primary**: #FF9900 (Amazon Orange)
- **Secondary**: #232F3E (Dark Blue)
- **Accent**: #00A8E1 (Bright Blue)
- **Success**: #00C853 (Green)
- **Danger**: #FF3D00 (Red)

### Typography
- **Primary Font**: Inter
- **Secondary Font**: Outfit
- Modern, clean, and highly readable

### Components
- Product cards with hover effects
- Filter sidebar
- Order summary
- Hero slider
- Category cards
- Deal cards
- Newsletter form
- Footer with social links

## 📁 Project Structure

```
e commerce/
├── index.html              # Homepage
├── products.html           # Products listing page
├── cart.html              # Shopping cart page
├── styles/
│   ├── main.css           # Main stylesheet with design system
│   ├── products.css       # Products page specific styles
│   └── cart.css           # Cart page specific styles
└── scripts/
    ├── data.js            # Product data and sample content
    ├── main.js            # Homepage functionality
    ├── products.js        # Products page functionality
    └── cart.js            # Cart page functionality
```

## 🚀 Getting Started

### Installation
1. Clone or download the project
2. Open `index.html` in your web browser
3. No build process or dependencies required!

### Usage
- **Browse Products**: Navigate to products page from homepage
- **Add to Cart**: Click "Add to Cart" on any product
- **Apply Promo**: Use codes like SAVE10, SAVE20, WELCOME, or FIRST50
- **Filter Products**: Use sidebar filters on products page
- **Search**: Use the search bar in navigation

## 🎯 Key Features Explained

### Promo Codes
- **SAVE10**: 10% discount
- **SAVE20**: 20% discount
- **WELCOME**: 15% discount
- **FIRST50**: 50% discount

### Free Shipping
- Orders over $50 get free shipping
- Automatic calculation in cart

### Product Filtering
- Filter by category
- Price range slider
- Customer rating
- Discount percentage
- Availability status

### Responsive Breakpoints
- Desktop: 1024px+
- Tablet: 768px - 1023px
- Mobile: < 768px

## 🎨 Customization

### Changing Colors
Edit CSS variables in `styles/main.css`:
```css
:root {
    --primary-color: #FF9900;
    --secondary-color: #232F3E;
    /* ... more variables */
}
```

### Adding Products
Edit `scripts/data.js` and add products to the arrays:
```javascript
const products = [
    {
        id: 1,
        title: "Product Name",
        category: "Category",
        price: 99.99,
        originalPrice: 149.99,
        discount: 33,
        rating: 4.5,
        reviews: 1234,
        badge: "Best Seller",
        icon: "fa-icon-name"
    }
];
```

### Modifying Promo Codes
Edit `scripts/cart.js`:
```javascript
const promoCodes = {
    'YOURCODE': 0.25  // 25% discount
};
```

## 🌐 Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📱 Mobile Features
- Touch-friendly interface
- Optimized layouts
- Mobile navigation menu
- Responsive images
- Fast loading

## 🔧 Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox & Grid
- **JavaScript (ES6+)** - Vanilla JS, no frameworks
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Inter, Outfit)

## 🎭 Animations
- Hero slider auto-rotation
- Product card hover effects
- Smooth page transitions
- Loading animations
- Toast notifications
- Floating effects

## 💡 Future Enhancements
- User authentication
- Product detail page
- Checkout process
- Order tracking
- User reviews
- Product comparison
- Backend integration
- Payment gateway
- Admin dashboard

## 📄 License
This is a demonstration project. Feel free to use and modify as needed.

## 👨‍💻 Author
Created with ❤️ by Antigravity AI

## 🙏 Acknowledgments
- Design inspired by Amazon and modern e-commerce platforms
- Icons by Font Awesome
- Fonts by Google Fonts

---

**Note**: This is a frontend-only demonstration. For a production e-commerce site, you would need to integrate with a backend API, payment gateway, and database.

## 🎉 Enjoy Shopping!
