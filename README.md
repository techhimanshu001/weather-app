# 🌤️ Weather App

A modern, responsive weather application that provides real-time weather information for any city worldwide. Built with React and Vite, featuring a clean UI and seamless user experience.

## 🛠️ Tech Stack

- **Frontend Framework:** React 18
- **Build Tool:** Vite
- **Styling:** TailwindCSS
- **Icons:** Lucide React
- **State Management:** TanStack Query (React Query)
- **Weather API:** OpenWeatherMap API
- **Language:** JavaScript (ES6+)

## ✨ Features

- 🌍 **Global Weather Search** - Get current weather for any city worldwide
- 📍 **Auto Location Detection** - Automatically detects and shows weather for your current location
- 🔍 **Instant Search** - Quick city search with real-time results
- 📝 **Recent Searches** - Track and quickly access recently searched cities
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- 🎨 **Modern UI Design** - Beautiful gradient design with animated weather icons
- ⚡ **Fast Performance** - Optimized with Vite and TanStack Query for caching
- 🔄 **Smart Loading States** - Smooth loading animations and skeleton screens
- ❌ **Error Handling** - Graceful error handling with user-friendly messages
- 🌡️ **Comprehensive Data** - Temperature, humidity, wind speed, pressure, and visibility

## 🔧 Environment Variables

Create a `.env` file in the project root:

```env
VITE_WEATHER_API_KEY=your_openweathermap_api_key_here
VITE_API_BASE_URL=https://api.openweathermap.org/data/2.5
```

**Get your API key:**
1. Sign up at [OpenWeatherMap](https://openweathermap.org/api)
2. Navigate to API Keys section in your dashboard
3. Copy your API key and add it to the `.env` file

## 🚀 Deployment on Netlify via GitHub

### Step 1: Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/weather-app.git
git push -u origin main
```

### Step 2: Deploy on Netlify
1. Go to [Netlify](https://netlify.com) and sign in
2. Click **"New site from Git"**
3. Choose **GitHub** and authorize Netlify
4. Select your weather-app repository
5. Configure build settings:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
6. Add environment variables in Netlify:
   - Go to **Site settings** → **Environment variables**
   - Add `VITE_WEATHER_API_KEY` with your API key
   - Add `VITE_API_BASE_URL` with the API base URL
7. Click **Deploy site**

Your app will be live at `https://your-app-name.netlify.app`

## 📖 Usage

### Basic Usage
1. **Automatic Location**: On first visit, the app requests location permission and shows your local weather
2. **Search Cities**: Type any city name in the search bar and press Enter
3. **Quick Access**: Click on recent searches to quickly view weather for previously searched cities
4. **Detailed Info**: View comprehensive weather data including temperature, humidity, wind, and more

### Search Examples
- `London` - Search by city name
- `New York` - Major cities work great
- `Paris, FR` - Include country code for better accuracy
- `Tokyo, JP` - International cities supported

### Weather Information Displayed
- **Current Temperature** - Real-time temperature in Celsius
- **Feels Like** - Apparent temperature considering humidity and wind
- **Weather Condition** - Clear description with animated icons
- **Humidity Level** - Moisture percentage in the air
- **Wind Speed** - Current wind speed in meters per second
- **Visibility** - How far you can see in kilometers
- **Atmospheric Pressure** - Current pressure in hPa

### Mobile Experience
- Touch-friendly interface
- Optimized for all screen sizes
- Fast loading on mobile networks
- Swipe-friendly recent searches

## 🏗️ Local Development

### Prerequisites
- Node.js (version 18 or higher)
- npm or yarn package manager
- Git

### Installation Steps
```bash
# Clone the repository
git clone https://github.com/techhimanshu001/weather-app.git
cd weather-app

# Install dependencies
npm install

# Create environment file
cp .env.example .env
# Edit .env and add your API key

# Start development server
npm run dev
```

### Available Scripts
- `npm run dev` - Start development server at http://localhost:5173
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality

## 🔗 Live Demo

**Live App:** [https://Climate-React-App.netlify.app](https://klimatereactapp.netlify.app)

## 🎯 Future Enhancements

- [ ] 5-day weather forecast
- [ ] Hourly weather updates
- [ ] Weather maps integration
- [ ] Dark/Light theme toggle
- [ ] Temperature unit conversion (°C/°F)
- [ ] Weather history and trends

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

