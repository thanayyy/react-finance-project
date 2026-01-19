# React Finance Project

A modern React-based web application for data analytics and financial insights, designed to help businesses monitor and grow revenue across BTB (Business-to-Business), BTC (Business-to-Consumer), and SaaS (Software as a Service) platforms.

## Features

- **Hero Section**: Engaging landing page with typed animations highlighting key services.
- **Analytics Dashboard**: Centralized data management with visual components for monitoring analytics.
- **Cards Component**: Display financial data or metrics in an organized card layout.
- **Newsletter Signup**: User engagement feature for subscriptions.
- **Responsive Design**: Built with Tailwind CSS for mobile-first, adaptive layouts.
- **Fast Performance**: Powered by Vite for quick development and optimized builds.

## Tech Stack

- **Frontend**: React 19.2.0
- **Build Tool**: Vite 7.2.4
- **Styling**: Tailwind CSS 4.1.18
- **Icons**: React Icons 5.5.0
- **Animations**: React Typed 2.0.12
- **Linting**: ESLint with React-specific rules
- **TypeScript Support**: Available via dev dependencies (optional)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd react-finance-project
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

   The app will be available at `http://localhost:5173` (default Vite port).

## Usage

- Navigate through the sections: Navbar, Hero, Analytics, Newsletter, Cards, and Footer.
- Customize components in the `src/components/` directory to add real data or integrate APIs.
- Build for production:
  ```bash
  npm run build
  ```
  Preview the build:
  ```bash
  npm run preview
  ```

## Scripts

- `npm run dev`: Start the development server with hot module replacement.
- `npm run build`: Build the project for production.
- `npm run lint`: Run ESLint to check for code quality issues.
- `npm run preview`: Preview the production build locally.

## Project Structure

```
react-finance-project/
├── public/                 # Static assets
├── src/
│   ├── assets/             # Images and media
│   ├── components/         # Reusable React components
│   │   ├── Analytics.jsx
│   │   ├── Cards.jsx
│   │   ├── Footer.jsx
│   │   ├── Hero.jsx
│   │   ├── Navbar.jsx
│   │   └── Newsletter.jsx
│   ├── App.jsx             # Main app component
│   ├── index.css           # Global styles
│   └── main.jsx            # App entry point
├── eslint.config.js        # ESLint configuration
├── index.html              # HTML template
├── package.json            # Dependencies and scripts
├── vite.config.js          # Vite configuration
└── README.md               # This file
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure code follows the ESLint rules by running `npm run lint` before committing.

## License

This project is private and not licensed for public use.
