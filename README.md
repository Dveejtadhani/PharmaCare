# PharmaCare - Modern Pharmacy Management System

A modern, responsive pharmacy management system built with React and Django, featuring a beautiful dark theme design with glass morphism effects and smooth animations.

## 🎨 Design System

### Modern Dark Theme
- **Primary Colors**: Indigo (#6366f1) and Purple (#8b5cf6) gradients
- **Secondary Colors**: Emerald (#10b981) and Cyan (#06b6d4) gradients
- **Background**: Deep slate (#0f172a) with layered card backgrounds
- **Typography**: Inter font family for modern, clean readability
- **Effects**: Glass morphism, subtle shadows, and smooth animations

### Key Design Features
- ✨ **Glass Morphism**: Translucent cards with backdrop blur effects
- 🌈 **Gradient Accents**: Beautiful color transitions throughout the UI
- 🎭 **Smooth Animations**: Fade-in, float, and hover effects
- 📱 **Responsive Design**: Optimized for all device sizes
- 🎯 **Modern Icons**: React Icons with consistent styling
- 🌙 **Dark Theme**: Easy on the eyes with excellent contrast

## 🚀 Features

### Customer Features
- **Browse Medicines**: Search and filter through available medications
- **Shopping Cart**: Add items and manage quantities
- **Order Management**: View order history and track status
- **User Profile**: Manage account information and preferences
- **Responsive Design**: Works seamlessly on mobile and desktop

### Admin Features
- **Dashboard**: Overview of sales, inventory, and orders
- **Medicine Management**: Add, edit, and manage medicine inventory
- **Stock Orders**: Manage supplier orders and stock levels
- **Customer Orders**: Process and track customer orders
- **Analytics**: View sales reports and inventory statistics

## 🛠️ Technology Stack

### Frontend
- **React 18**: Modern React with hooks and functional components
- **Bootstrap 5**: Responsive CSS framework
- **React Router**: Client-side routing
- **React Icons**: Beautiful icon library
- **CSS Variables**: Custom properties for theming

### Backend
- **Django**: Python web framework
- **Django REST Framework**: API development
- **SQLite**: Database (can be easily switched to PostgreSQL/MySQL)

## 🎨 Design Components

### CSS Variables
```css
:root {
  /* Primary Colors */
  --primary-color: #6366f1;
  --primary-dark: #4f46e5;
  --primary-light: #a5b4fc;
  
  /* Background Colors */
  --bg-primary: #0f172a;
  --bg-secondary: #1e293b;
  --bg-card: #1e293b;
  
  /* Gradients */
  --gradient-primary: linear-gradient(135deg, #6366f1 0%, #8b5cf6 100%);
  --gradient-secondary: linear-gradient(135deg, #10b981 0%, #06b6d4 100%);
}
```

### Utility Classes
- `.modern-card`: Glass morphism card with hover effects
- `.glass-effect`: Translucent background with blur
- `.gradient-text`: Text with gradient color
- `.float-animation`: Subtle floating animation
- `.glow-effect`: Glowing border/shadow effects

## 📱 Responsive Design

The application is fully responsive with:
- **Mobile First**: Optimized for mobile devices
- **Tablet Support**: Adaptive layouts for tablets
- **Desktop Enhancement**: Enhanced features for larger screens
- **Touch Friendly**: Optimized touch targets and interactions

## 🎭 Animations & Effects

### Loading States
- Custom loading spinners with brand colors
- Skeleton loading for content areas
- Smooth transitions between states

### Hover Effects
- Card elevation on hover
- Button transform effects
- Gradient overlays on navigation

### Page Transitions
- Fade-in animations for page loads
- Smooth navigation transitions
- Modal animations with backdrop blur

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- Python (v3.8 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd pharmacy-management-system
   ```

2. **Install Frontend Dependencies**
   ```bash
   cd Frontend/pharmacy-frontend
   npm install
   ```

3. **Install Backend Dependencies**
   ```bash
   cd Backend/pharmacy_backend
   pip install -r requirements.txt
   ```

4. **Run the Development Servers**

   **Backend (Django)**
   ```bash
   cd Backend/pharmacy_backend
   python manage.py runserver
   ```

   **Frontend (React)**
   ```bash
   cd Frontend/pharmacy-frontend
   npm start
   ```

5. **Access the Application**
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:8000

## 🎨 Customization

### Theme Colors
Modify the CSS variables in `src/index.css` to customize the theme:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --bg-primary: #your-background;
}
```

### Component Styling
Each component uses the design system classes. You can:
- Add new utility classes in `src/App.css`
- Modify existing components to use different effects
- Create new animations in the CSS files

## 📁 Project Structure

```
Frontend/pharmacy-frontend/
├── src/
│   ├── admin/           # Admin dashboard components
│   ├── auth/            # Authentication components
│   ├── customer/        # Customer interface components
│   ├── api/             # API integration
│   ├── images/          # Static images
│   ├── App.css          # Main application styles
│   ├── index.css        # Global styles and theme
│   └── App.js           # Main application component
├── public/
│   └── index.html       # HTML template
└── package.json         # Dependencies and scripts
```

## 🔧 Development

### Available Scripts
- `npm start`: Start development server
- `npm build`: Build for production
- `npm test`: Run tests
- `npm eject`: Eject from Create React App

### Code Style
- Use functional components with hooks
- Follow the established design system
- Maintain consistent naming conventions
- Add proper error handling and loading states

## 🎯 Future Enhancements

### Planned Features
- [ ] Dark/Light theme toggle
- [ ] Advanced search and filtering
- [ ] Real-time notifications
- [ ] Payment integration
- [ ] Mobile app (React Native)
- [ ] Advanced analytics dashboard
- [ ] Multi-language support
- [ ] Accessibility improvements

### Design Improvements
- [ ] More animation variations
- [ ] Custom illustrations
- [ ] Advanced color schemes
- [ ] Micro-interactions
- [ ] Performance optimizations

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Follow the design system guidelines
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- **React Icons**: Beautiful icon library
- **Bootstrap**: Responsive CSS framework
- **Inter Font**: Modern typography
- **Glass Morphism**: Modern UI design trend

---

**PharmaCare** - Modern Pharmacy Management System  
Built with ❤️ and modern design principles
