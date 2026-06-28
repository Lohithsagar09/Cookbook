# Cookbook

A modern React + Vite cookbook app for discovering recipes, saving favorites, and exploring cooking ideas.

## Features
- Browse featured recipe cards
- Search recipes
- Save favorites
- View recipe details
- Dark mode support
- PDF export for recipes

## Tech Stack
- React
- Vite
- Tailwind CSS
- React Router
- JSON Server

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/Lohithsagar09/Cookbook.git
   cd Cookbook
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Create a local environment file
   ```bash
   cp .env.example .env
   ```

4. Add your RapidAPI key to `.env`
   ```env
   VITE_TASTY_API_KEY=your_rapidapi_key_here
   ```

5. Start the development server
   ```bash
   npm run dev
   ```

## Available Scripts
- `npm run dev` – start the Vite dev server
- `npm run build` – build for production
- `npm run server` – start the local JSON server

## Notes
- The app uses the Tasty API through a Vite environment variable.
- Keep your API key in a local `.env` file and do not commit it to GitHub.
