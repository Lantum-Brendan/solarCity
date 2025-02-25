# Solar City

A modern full-stack web application for managing solar panel sales, installations, and educational services.

![Solar City Logo](public/logos--linux-tux.png)

## 🌟 Overview

Solar City is a comprehensive platform that connects customers with solar energy solutions. The platform manages product sales, installation services, and educational courses related to solar energy.

## ✨ Features

- **Products Management**
  - Browse solar panels and accessories
  - Detailed product specifications
  - Shopping cart functionality
  - Order tracking

- **Installation Services**
  - Book solar installation services
  - Get installation cost estimates
  - Schedule site surveys
  - Track installation progress

- **Educational Platform**
  - Online courses about solar energy
  - Course enrollment system
  - Progress tracking
  - Educational resources

- **User Management**
  - Role-based access control
  - Customer profiles
  - Admin dashboard
  - Order history

## 🛠️ Tech Stack

### Frontend
- React.js
- TailwindCSS
- React Router DOM
- Axios
- React Hot Toast
- Lucide React Icons
- Radix UI Components

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Swagger Documentation

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm (v7 or higher)
- MongoDB (v4.4 or higher)
- Git

### Installation

1. Clone the repository
```bash
git clone https://github.com/Lantum-Brendan/solarCity.git
cd solarCity
```

2. Install Backend Dependencies
```bash
cd solarcityBackend
npm install
```

3. Install Frontend Dependencies
```bash
cd ../solarcityClient
npm install
```

4. Set up environment variables

Backend (.env):
```env
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
NODE_ENV=development
```

Frontend (.env):
```env
REACT_APP_API_URL=http://localhost:5000/api
```

### Running the Application

1. Start the Backend Server
```bash
cd solarcityBackend
npm run dev
```

2. Start the Frontend Development Server
```bash
cd solarcityClient
npm start
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000
- API Documentation: http://localhost:5000/api-docs

## 📁 Project Structure

```
solarCity/
├── solarcityClient/          # Frontend React Application
│   ├── src/
│   │   ├── components/       # Reusable components
│   │   ├── context/         # Context providers
│   │   ├── pages/           # Page components
│   │   ├── services/        # API services
│   │   └── styles/          # Global styles
│   └── public/              # Static assets
│
└── solarcityBackend/        # Backend Node.js Application
    ├── config/              # Configuration files
    ├── controllers/         # Request handlers
    ├── middleware/          # Custom middleware
    ├── models/             # Database models
    ├── routes/             # API routes
    └── utils/              # Utility functions
```

## 🔒 Security

- JWT-based authentication
- Role-based access control
- Secure password hashing
- API rate limiting
- XSS protection
- CORS configuration

## 🤝 Support

For support, please email lantumbrendan170@gmail.com or open an issue in the repository.
