# Yoga-App

A Yoga app for efficient Yoga with a built-in session timer.

## Table of Contents

- About
- Features
- Tech Stack
- Getting Started
  - Prerequisites
  - Install
  - Run
  - Build
- Configuration
- Available Scripts
- Contributing
- License
- Contact

## About

Yoga-App is a TypeScript + React application built with Vite that provides an easy way to practice yoga with timed sessions. It includes a session timer, responsive UI, and is designed to be extended with features like session presets and user progress tracking.

## Features

- Session timer for practice and intervals
- Responsive UI (mobile-first)
- Built with TypeScript and Vite for fast development
- Integrates with Firebase (optional)

## Tech Stack

- TypeScript
- React
- Vite
- Tailwind CSS
- Firebase
- Express (optional backend)
- Lucide icons

## Getting Started

### Prerequisites

- Node.js v18+ recommended
- npm (or yarn/pnpm)

### Install

1. Clone the repo

   git clone https://github.com/Vaish1004/Yoga-App.git
   cd Yoga-App

2. Install dependencies

   npm install

### Run (development)

Start the dev server (the project uses Vite on port 3000):

   npm run dev

Then open http://localhost:3000 in your browser.

### Build (production)

To build the app for production:

   npm run build

To preview the production build locally:

   npm run preview

## Configuration

If the project uses Firebase or other services, create a `.env` file in the project root and add any required environment variables (Firebase config keys, API keys, etc.).

Example (replace with your actual keys):

```
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
```

Note: Vite exposes variables prefixed with `VITE_` to the client-side code.

## Available Scripts

Taken from package.json:

- `npm run dev` — start dev server (vite --port=3000 --host=0.0.0.0)
- `npm run build` — build for production
- `npm run preview` — preview production build
- `npm run clean` — remove `dist` folder
- `npm run lint` — TypeScript type-check (no emit)

## Contributing

Contributions are welcome! Please open an issue to discuss changes or submit a pull request. Keep code in TypeScript and follow existing project structure.

## License

This project does not include a license file. If you want to make it open-source, consider adding a LICENSE (for example, MIT).

## Contact

Project maintained by @Vaish1004 — https://github.com/Vaish1004
