# Readium - Free E-Book Platform

A modern, professional e-book platform built with Vue 3 and Vite. Readium provides free access to professional development books, technical guides, and career resources in PDF format.

## 🌟 Features

### Public Features
- **Home Page**: Hero section with featured books and key highlights
- **Book Catalog**: Complete catalog with filtering by category and search functionality
- **Category Pages**: Browse books organized by topics (Software Engineering, Career, Programming, etc.)
- **Author Pages**: Explore books by specific authors with author biographies
- **Book Details**: Detailed book information with download links
- **Responsive Design**: Mobile-first design that works on all devices
- **Modern UI**: Clean, professional interface with consistent rounded corners and spacing

### Admin Features
- **Admin Dashboard**: Full content management system for books, authors, and categories
- **Local Management**: Manage content locally without a database
- **Secure Authentication**: Password-protected admin area
- **CRUD Operations**: Add, edit, and delete books, authors, and categories
- **Real-time Updates**: Changes reflect immediately in the application

> 📖 **For detailed admin documentation, see [README_ADMIN.md](./README_ADMIN.md)**

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd e-book
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file (for admin features):
```bash
cp .env.example .env
```

Edit `.env` and set your admin credentials:
```env
VITE_ADMIN_PASSWORD=your_secure_password
VITE_ADMIN_MODE=true
```

4. Start the development server:
```bash
npm run dev
```

5. Open your browser and navigate to `http://localhost:5173`

## 📁 Project Structure

```
e-book/
├── src/
│   ├── components/          # Vue components
│   │   ├── Navbar.vue      # Navigation bar
│   │   ├── BookCard.vue    # Book card component
│   │   ├── Footer.vue      # Footer component
│   │   └── admin/          # Admin components
│   ├── views/               # Page views
│   │   ├── Home.vue        # Home page
│   │   ├── AllBooks.vue    # Book catalog
│   │   ├── Categories.vue
│   │   ├── Authors.vue      # Author listing
│   │   └── admin/          # Admin pages
│   ├── data/                # JSON data files
│   │   ├── books.json      # Book data
│   │   ├── authors.json    # Author data
│   │   └── categories.json # Category data
│   ├── router/              # Vue Router configuration
│   ├── store/               # State management
│   └── style.css            # Global styles
├── public/                  # Static assets
└── package.json            # Dependencies
```

## 🛠️ Built With

- **Vue 3** - Progressive JavaScript framework
- **Vue Router** - Official router for Vue.js
- **Vite** - Next generation frontend tooling
- **Tailwind CSS** - Utility-first CSS framework
- **Manrope Font** - Modern typography

## 🎨 Design Features

- **Consistent Border Radius**: All interactive elements use `rounded-2xl` for a soft, modern look
- **Dynamic Navigation**: Navbar adapts based on page context
- **Smooth Transitions**: CSS transitions for better user experience
- **Compact Layout**: Optimized spacing for better content density
- **Dark Navigation Bar**: Professional dark navbar across all pages

## 📝 Admin Documentation

For detailed information about the admin dashboard, local data management, and deployment, please refer to the [Admin Documentation](./README_ADMIN.md).

## 🚢 Deployment

### Build for Production

```bash
npm run build
```

The `dist` folder will contain the production-ready static files.

### Deploy to Netlify/Vercel

1. Connect your GitHub repository
2. Set build command: `npm run build`
3. Set publish directory: `dist`
4. Deploy!

The admin features are automatically disabled in production mode.

## 📄 License

This project is available for use as a template for creating e-book platforms.

## 👨‍💻 Development

### Running Tests
```bash
npm run dev
```

### Building
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

## 📞 Support

For issues, questions, or contributions, please open an issue on the GitHub repository.

---

**Readium** - Your Gateway to Free Knowledge 📚
