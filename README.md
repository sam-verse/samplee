<div align="center">
  <h1>HappyFox Employee Org Chart</h1>
  
  [![Demo](https://img.shields.io/badge/View-Demo-2ea44f?style=for-the-badge&logo=vercel)](https://frontend-assignment-happyfox.vercel.app/)
  [![GitHub](https://img.shields.io/badge/View-Code-181717?style=for-the-badge&logo=github)](https://github.com/sam-verse/frontend-assignment-happyfox)
  
  <img src="https://github.com/sam-verse/frontend-assignment-happyfox/blob/main/src/public/image.png" alt="HappyFox Org Chart Screenshot" width="800" />
  
  *Interactive Organizational Chart*
</div>

A responsive web application for visualizing and managing organizational hierarchies. The interactive chart allows users to explore employee relationships, search team members, and manage organizational data with an intuitive interface. Built with modern web technologies for optimal performance and user experience.

## 🚀 Features

### Core Functionality
- Interactive organizational chart with drag-and-drop functionality
- Real-time search and filtering by team or name
- CRUD operations for employee management
- Responsive design with mobile-first approach

### Technical Highlights
- Type-safe development with TypeScript
- Smooth animations using Framer Motion
- State management with React Context
- Mock API implementation with MirageJS
- Optimized performance with React

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher) or yarn

## Installation

## Live Demo

Check out the live demo deployed on Vercel: [https://frontend-assignment-happyfox.vercel.app/](https://frontend-assignment-happyfox.vercel.app/)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/sam-verse/frontend-assignment-happyfox.git
   cd frontend-assignment-happyfox
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

## Available Scripts

In the project directory, you can run:

### `npm run dev` or `yarn dev`

Runs the app in development mode.
Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

The page will reload when you make changes.

### `npm test` or `yarn test`

Launches the test runner in interactive watch mode.

### `npm run build` or `yarn build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm run preview` or `yarn preview`

Serves the production build from the `build` folder.

## Project Structure

```
src/
  ├── components/       # Reusable UI components
  │   ├── EmployeeCard/  # Employee card component
  │   ├── OrgChart/      # Organizational chart component
  │   └── Sidebar/       # Sidebar navigation
  ├── store/            # State management
  ├── styles/           # Global styles
  └── utils/            # Utility functions
```

## 🛠️ Technical Implementation

### Frontend Stack
- **React 18** - Component-based UI development
- **Vite** - Fast development server and build tool
- **Framer Motion** - Smooth animations and transitions
- **Tailwind CSS** - Utility-first CSS framework
- **React DnD** - Drag and drop functionality
- **MirageJS** - Mock API server for development

### Key Implementation Details
- Responsive layout using CSS Grid and Flexbox
- Custom hooks for reusable logic
- Form validation and error handling
- Clean component architecture
- Comprehensive test coverage

## 🎯 Project Goals

This project was developed as part of the HappyFox frontend developer recruitment process to demonstrate:
- Proficiency in React and modern JavaScript/TypeScript
- Understanding of state management and component architecture
- Ability to create responsive and accessible UIs
- Knowledge of testing and performance optimization
- Clean and maintainable code practices

## 📝 Assignment Requirements

### Implemented Features
- [x] Interactive org chart visualization
- [x] Employee CRUD operations
- [x] Search and filter functionality
- [x] Responsive design for all screen sizes
- [x] Smooth animations and transitions
- [x] Drag and drop functionality
- [x] Form validation
- [x] Unit tests for critical components

## 🚀 Performance Optimizations

- **Optimized Event Handlers**: Debounced and throttled handlers for smooth interactions
- **Responsive Design**: Media queries and container queries for different screen sizes
- **Efficient State Management**: Uses Zustand for optimized state updates
- **Animation Optimization**: Uses Framer Motion for performant animations



## Acknowledgments

Special thanks to the HappyFox team for this opportunity. Built with:
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Framer Motion](https://www.framer.com/motion/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React DnD](https://react-dnd.github.io/react-dnd/about)
