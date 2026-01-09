SkyWatch Weather Dashboard
A beautiful, responsive weather dashboard that provides real-time weather data, forecasts, and interactive visualizations using the OpenWeatherMap API.

https://images.unsplash.com/photo-1592210454359-9043f067919b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80

Live Demo
View Live Site: https://wilfred123816.github.io/Weather-App/

Features
Real-time Weather Data - Current conditions, temperature, humidity, wind speed

5-Day Forecast - Daily weather predictions with high/low temperatures

Interactive Charts - Temperature trends using Chart.js

Air Quality Index - Real-time air pollution data

UV Index Tracking - Sun exposure safety information

Geo-location - Automatic location detection

City Search - Search any city worldwide

Recent Searches - Quick access to previously searched cities

Unit Toggle - Switch between °C and °F

Responsive Design - Works on mobile, tablet, and desktop

Weather Animations - Visual feedback for different weather conditions

Technologies Used
HTML5 - Semantic markup

CSS3 - Flexbox, Grid, CSS Variables, Animations

JavaScript (ES6+) - Async/await, Fetch API, LocalStorage

OpenWeatherMap API - Real-time weather data

Chart.js - Data visualization

Animate.css - CSS animations

Font Awesome - Icons

Google Fonts - Typography

Screenshots
<img width="1358" height="660" alt="image" src="https://github.com/user-attachments/assets/f2608c96-72ae-492e-826c-61bc960a0268" />
<img width="1356" height="678" alt="image" src="https://github.com/user-attachments/assets/4942684c-09eb-4ff7-9d00-95474665b479" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/dbccc62a-40c4-4053-ba7d-116b0f378a9e" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/e3782a18-6252-4da4-b91c-d026ef3167ed" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9cf3c196-3d83-4637-a54e-8251c7a4cdc4" />





Key Learnings
API integration and handling asynchronous data

Error handling and user feedback

Dynamic DOM manipulation

Chart creation and data visualization

LocalStorage for persistent data

Responsive design with CSS Grid

Mobile-first development approach

Weather condition-based UI theming

Setup Instructions
1. Get API Key
Go to OpenWeatherMap

Sign up for a free account

Verify your email

Navigate to API Keys

Copy your API key (starts with letters/numbers)

2. Configure API Key
Open script.js and replace the API key:

javascript
const API_KEY = 'YOUR_API_KEY_HERE'; // Replace with your key
3. Run Locally
bash
# Clone the repository
git clone https://wilfred123816.github.io/Weather-App/

# Navigate to project directory
cd weather-app

# Open in browser
open index.html
# or
start index.html

Design Features
Dynamic Backgrounds - Changes based on weather conditions

Weather Icons - Real weather icons from OpenWeatherMap

Temperature Charts - Interactive line charts for temperature trends

Progress Bars - Visual indicators for UV index and day length

Toast Notifications - Error handling and user feedback

Loading States - Smooth loading animations

Responsive Grid - Adapts to all screen sizes

Responsive Breakpoints
Mobile: 320px - 480px

Tablet: 481px - 768px

Desktop: 769px - 1200px

Large Desktop: 1201px+

Performance Optimizations
Lazy loading for weather map

Cached API responses

Optimized image assets

Minimized API calls

Efficient chart rendering

Known Issues & Limitations
Free OpenWeatherMap API has rate limits (60 calls/minute)

Air quality data might not be available for all locations

UV index is simulated (requires premium API for real data)

Weather map requires manual activation due to iframe limitation

Contributing
Contributions are welcome! Please follow these steps:
Fork the repository
Create a feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
OpenWeatherMap for providing the weather API

Chart.js for beautiful charts

Animate.css for animations

Font Awesome for icons

Unsplash for beautiful background images

Author
Wilfred Monyenye

GitHub: @Wilfred123816

Portfolio: https://github.com/Wilfred123816/wilfredmonyenye.github.io

LinkedIn: Wilfred Monyenye

Support
For support, please:

Check the OpenWeatherMap FAQ

Open an issue in this repository

Contact via email: mosimawilfred13@gmail.com

API Usage Example
javascript
// Example API call for current weather
const response = await fetch(
  `https://api.openweathermap.org/data/2.5/weather?q=London&units=metric&appid=${API_KEY}`
);
const data = await response.json();
Quick Start for Developers
bash
1. Clone and setup
git clone https://github.com/Wilfred123816/Weather-App
cd weather-app
2. Get API key from OpenWeatherMap
3. Update script.js with your API key
4. Open index.html in broswer
5. Optional: Use Live Server in VS Code
   Install Liver Serve extension
   Right-click index.html-"Open with Live Server"


Made wit

Last Updated: January 2024
