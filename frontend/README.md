# E-Commerce Frontend (React + Tailwind CSS)

This is a modern and responsive frontend for an advanced e-commerce platform built with **React** and **Tailwind CSS**. It provides a smooth and dynamic user experience for browsing, searching, and purchasing tech gadgets.

## Authors
**Prince Wycliff Dickson** (Frontend Developer)  
📧 Email: princed.wycliff@outlook.com  
📱 Phone: +265 886 29 24 23 / +265 993 82 72 85  
🔗 LinkedIn: [https://www.linkedin.com/in/prince-dickson-906149281](www.linkedin.com/in/prince-dickson-906149281)  
💬 WhatsApp: [Chat on WhatsApp](https://wa.me/265886292423)

## Features
- Built with React (Vite)
- Responsive layout using Tailwind CSS
- Reusable Components
- REST API integration
- JWT-based authentication (login/logout)
- Product listing, filtering, searching
- Shopping cart and checkout system
- Form validation
- React Router DOM for client-side routing
- Global state management using Context API

## Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn
- (Optional) Docker (for containerization)

### 1. Clone the Repository
```bash
git clone https://github.com/prince-wycliff/your-ecommerce-frontend.git
cd your-ecommerce-frontend
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Setup Environment Variables
Create a `.env` file in the root directory:
```env
VITE_API_URL=http://localhost:8080/api
```

### 4. Run the Application
```bash
npm run dev
```

## Folder Structure
```
gadgetnest/
│── frontend/                   # React Frontend
│   ├── public/                 # Public Assets (index.html, favicon)
│   ├── src/
│   │   ├── components/         # Reusable Components (Navbar, Footer, etc.)
│   │   ├── pages/              # Pages (Home, Product, Checkout)
│   │   ├── hooks/              # Custom React Hooks
│   │   ├── context/            # State Management (React Context API)
│   │   ├── services/           # API Calls to Backend
│   │   ├── App.jsx             # Main App Component
│   │   ├── main.jsx            # React Entry Point
│   ├── Dockerfile              # Frontend Docker Config
│   ├── package.json            # Dependencies
│   ├── README.md               # Frontend Documentation
```

## Dependencies Used

### Frontend
**Framework & Core**
- React (Vite)
- React Router DOM

**Styling**
- Tailwind CSS
- DaisyUI

**API & Auth**
- Axios
- JWT Decode

**Icons & Fonts**
- Heroicons
- Font Awesome
- Google Fonts

**State Management**
- Context API

**Developer Tools**
- ESLint
- Prettier
- Vite
- GitLens

## About
A fully functional E-Commerce Practice Project built with React JS and integrated with a secure Spring Boot backend.

## Resources
- [React Documentation](https://reactjs.org)
- [Tailwind CSS Documentation](https://tailwindcss.com)
- [Vite Documentation](https://vitejs.dev)