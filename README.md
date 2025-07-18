# Capture Moments - Modern Photography Booking Platform

A modern, responsive web application for connecting clients with professional photographers. Built with Flask, Tailwind CSS, and featuring a beautiful dark mode interface.

## ✨ Features

### 🎨 Modern Design System
- **Minimal & Modern UI** with clean, professional aesthetics
- **Dark Mode Support** with automatic theme detection and toggle
- **Responsive Design** that works perfectly on all devices
- **Tailwind CSS** for fast, utility-first styling
- **Smooth Animations** and hover effects for enhanced UX

### 👥 User Interfaces

#### Client Dashboard
- **Upcoming Bookings** with status tracking
- **Photo Album Viewer** and download links
- **Quick Actions** for common tasks
- **Featured Photographers** recommendations
- **Notifications Panel** for updates
- **Statistics Cards** showing booking metrics

#### Photographer Dashboard
- **Booking Requests** with accept/reject actions
- **Revenue Analytics** and earnings tracking
- **Client Management** with quick view
- **Gallery Upload Manager** (placeholder)
- **Profile Customization** options
- **Performance Metrics** and ratings

### 🔐 Authentication & Security
- **Modern Login/Signup** forms with social login options
- **Role-based Access** (Client vs Photographer)
- **Secure Session Management**
- **Password Hashing** and validation

### 📅 Booking System
- **Interactive Booking Form** with real-time price calculation
- **Date/Time Selection** with availability checking
- **Booking Summary** with detailed breakdown
- **Status Tracking** (Pending, Accepted, Rejected, Completed)
- **Payment Integration** ready

### 🎯 Key Pages
- **Homepage** with hero section, services, and featured photographers
- **Photographer Directory** with search and filtering
- **Profile Pages** with detailed information
- **Booking Management** for both clients and photographers

## 🚀 Technology Stack

### Frontend
- **Tailwind CSS** - Utility-first CSS framework
- **Alpine.js** - Lightweight JavaScript framework for interactivity
- **Font Awesome** - Icon library
- **Responsive Design** - Mobile-first approach

### Backend
- **Flask** - Python web framework
- **SQLAlchemy** - Database ORM
- **SQLite** - Local database (with AWS DynamoDB support)
- **Werkzeug** - Security and utilities

### Deployment
- **Heroku** ready with Procfile
- **AWS Integration** for DynamoDB
- **Environment Variables** for configuration

## 🎨 Design System

### Color Palette
- **Primary**: Teal (#14b8a6) to Blue (#0ea5e9) gradient
- **Neutrals**: Gray scale for backgrounds and text
- **Accents**: Purple, Pink, Green for different service types
- **Dark Mode**: Deep grays with blue/teal accents

### Typography
- **Headings**: Bold, large text for hierarchy
- **Body**: Clean, readable fonts
- **Interactive**: Hover states and focus indicators

### Components
- **Cards**: Rounded corners with subtle shadows
- **Buttons**: Gradient backgrounds with hover effects
- **Forms**: Clean inputs with focus rings
- **Navigation**: Responsive with mobile menu

## 📱 Responsive Features

- **Mobile-First** design approach
- **Breakpoint System**: sm, md, lg, xl
- **Touch-Friendly** interface elements
- **Optimized Images** and loading
- **Progressive Enhancement**

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd capture-moments
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

4. **Initialize database**
   ```bash
   python -c "from app import db; db.create_all()"
   ```

5. **Run the application**
   ```bash
   python app.py
   ```

## 🌐 Deployment

### Heroku
```bash
heroku create your-app-name
git push heroku main
```

### AWS
```bash
python deploy_aws.py
```

## 🎯 Key Features Implemented

### ✅ Completed
- [x] Modern responsive design with Tailwind CSS
- [x] Dark mode toggle with system preference detection
- [x] Client and photographer dashboards
- [x] Booking system with real-time calculations
- [x] User authentication and role management
- [x] Photographer directory with search/filter
- [x] Mobile-responsive navigation
- [x] Interactive forms with validation
- [x] Professional homepage with hero section
- [x] Statistics and analytics cards

### 🚧 Future Enhancements
- [ ] Photo gallery upload and management
- [ ] Payment processing integration
- [ ] Real-time messaging system
- [ ] Advanced search and filtering
- [ ] Review and rating system
- [ ] Email notifications
- [ ] Calendar integration
- [ ] Social media sharing

## 📊 Performance

- **Fast Loading** with CDN resources
- **Optimized Images** and assets
- **Minimal JavaScript** for better performance
- **Progressive Loading** for better UX

## 🔒 Security

- **CSRF Protection** on forms
- **Input Validation** and sanitization
- **Secure Session Management**
- **Environment Variable** configuration
- **SQL Injection Prevention** with ORM

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- **Tailwind CSS** for the amazing utility-first framework
- **Font Awesome** for the beautiful icons
- **Alpine.js** for lightweight interactivity
- **Flask** community for the robust web framework

---

**Capture Moments** - Where every moment becomes a masterpiece. 📸✨
