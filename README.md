# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# Airbnb Clone

Welcome to the Airbnb Clone project! This is a full-stack web application that replicates the core functionalities of the popular vacation rental platform, Airbnb. This README will guide you through the project setup, technologies used, and how to contribute.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and authorization (JWT, Bcrypt)
- Browse listings
- Search and filter listings
- View property details
- Book a property
- User dashboard with booking history
- Responsive design

## Technologies Used

### Frontend

- React
- Material-UI
- React Router
- Context API

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose

### Additional Tools

- Webpack
- Babel
- ESLint
- Prettier

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- MongoDB

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/airbnb-clone.git
   cd airbnb-clone
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory and add the following variables:

   ```plaintext
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

4. **Start the development server:**

   ```bash
   npm run dev
   ```

   [![Netlify Status](https://api.netlify.com/api/v1/badges/82dde0d3-ef19-47bb-9dd6-7b8628d29464/deploy-status)](https://app.netlify.com/sites/zingy-hotteok-afcff4/deploys)

```

## API Endpoints

### Authentication

- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login a user
- `GET /api/auth/logout` - Logout a user

### Bookings

- `POST /api/bookings` - Create a new booking
- `GET /api/bookings` - Get all bookings


## Contributing

We welcome contributions! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for your interest in the Airbnb Clone project! If you have any questions, feel free to open an issue or contact the project maintainers.

My Linkedin profile: https://www.linkedin.com/in/kishor-kumar-k-520788252?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app