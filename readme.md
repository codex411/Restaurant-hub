# RestaurantHub - Angular Learning Project

A progressive Angular application demonstrating modern front-end development practices through a restaurant management interface.

## 📋 Overview

This repository contains a series of Angular assignments that progressively build a full-featured restaurant application. Each assignment module introduces new concepts and features, from basic components to advanced routing, services, and HTTP integration.

## 🚀 Quick Start

### Prerequisites

- **Node.js** (v8.x or higher)
- **npm** (v5.x or higher) or **yarn**
- **Angular CLI** (v1.4.9)

### Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd Front-End-JavaScript-Frameworks-Overview-Angular
   ```

2. Navigate to any assignment module:
   ```bash
   cd "Assignment 1/conFusion"
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to `http://localhost:4200/`

## 📁 Project Structure

```
├── Assignment 1/          # Basic components and Material Design
├── Assignment 2/          # Routing and navigation
├── Assignment 3/          # Forms and authentication
└── Assignment 4/          # HTTP services and REST API integration
```

Each assignment module is self-contained and includes:
- Complete Angular application
- Assignment instructions (PDF)
- Test configuration
- Development dependencies

## 🛠️ Development

### Available Scripts

- `npm start` - Start the development server
- `npm run build` - Build for production
- `npm test` - Run unit tests
- `npm run lint` - Run linting
- `npm run e2e` - Run end-to-end tests

### Building for Production

```bash
npm run build --prod
```

The build artifacts will be stored in the `dist/` directory.

## 🌐 REST API Server (Assignment 4)

Assignment 4 includes a JSON server for simulating REST API endpoints.

### Setup

1. Install json-server globally:
   ```bash
   npm install -g json-server
   ```

2. Navigate to the json-server directory:
   ```bash
   cd "Assignment 4/conFusion/json-server"
   ```

3. Start the server:
   ```bash
   json-server --watch db.json -d 2000
   ```

The server will:
- Run on `http://localhost:3000/`
- Introduce a 2-second delay to simulate network latency
- Serve static files from the `public/` directory

## 📚 Learning Resources

This project is part of the [Front-End JavaScript Frameworks: Angular](https://www.coursera.org/learn/angular) course on Coursera.

## 📝 Notes

- Each assignment builds upon the previous one
- Assignment instructions are available as PDF files in each module directory
- The project uses Angular 4.x with Material Design components
- All modules are configured for development and testing

## 🤝 Contributing

This repository is maintained for educational purposes. If you're taking the course, please complete assignments independently rather than copying from this repository.

## 📄 License

MIT License - See individual assignment directories for details.
