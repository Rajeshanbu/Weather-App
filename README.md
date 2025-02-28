# Weather Web Application
A fully functional Weather Web App that provides real-time weather updates for any location worldwide. The app is built with React and Vite, integrates OpenWeatherMap API, and is deployed on Netlify for seamless user experience.

## Features
- User-friendly UI with React & Vite
- Real-time weather updates from OpenWeatherMap API
- Displays temperature, humidity, wind speed, and location details
- Responsive design for all devices
- Hosted on Netlify

## Tech Stack
- **Frontend**: React, Vite (Hosted on Netlify)
- **API**: OpenWeatherMap API

## Setup Instructions

### Clone the Repository
```sh
git clone https://github.com/your-github-username/weather-app.git
cd weather-app
```

### Frontend Setup & Deployment

1. **Configure Environment Variables**
   - Create a `.env` file in the project root and add:
   ```sh
   VITE_WEATHER_API_KEY=your-openweathermap-api-key
   ```

2. **Install Dependencies**
   ```sh
   npm install
   ```

3. **Run the App Locally**
   ```sh
   npm run dev
   ```
   The app will be accessible at `http://localhost:5173` (default Vite port).

4. **Build the Frontend**
   ```sh
   npm run build
   ```
   This generates a `dist/` folder with the production build.

5. **Deploy on Netlify**
   - Go to [Netlify](https://www.netlify.com/) and create a new site.
   - Drag and drop the `dist/` folder into Netlify’s deployment section.
   - After deployment, you will get a live URL for your weather app.

## App Link
- **Live Demo**: [Weather App](https://dazzling-tartufo-cacf4c.netlify.app/)

## Key Features:
- Step-by-step deployment guide for frontend setup.
- Uses OpenWeatherMap API for real-time weather data.
- Proper environment variable setup for API integration.
- Netlify deployment process explained clearly.

