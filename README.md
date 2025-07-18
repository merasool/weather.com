
# 🌤️ Air Quality Checker

A modern, responsive web application that provides real-time air quality data for any location using coordinates. Built with HTML, CSS, and JavaScript, this application fetches air quality information from the RapidAPI Air Quality API.

## 🌟 Features

- **Real-time Air Quality Data**: Get current air quality information for any location
- **Multiple Air Quality Parameters**: 
  - AQI (Air Quality Index)
  - CO (Carbon Monoxide)
  - NO2 (Nitrogen Dioxide)
  - O3 (Ozone)
  - PM2.5 (Fine Particulate Matter)
  - PM10 (Coarse Particulate Matter)
  - SO2 (Sulfur Dioxide)
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, intuitive interface with gradient backgrounds and smooth animations
- **Easy to Use**: Simply enter latitude and longitude coordinates to get instant results

## 🚀 Live Demo

Visit the live application: [https://merasool.github.io/weather.com/](https://merasool.github.io/weather.com/)

## 📋 Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection
- Valid latitude and longitude coordinates

## 🛠️ Installation & Setup

### Option 1: Clone the Repository
```bash
git clone https://github.com/merasool/weather.com.git
cd weather.com
```

### Option 2: Download ZIP
1. Click the "Code" button on this repository
2. Select "Download ZIP"
3. Extract the ZIP file to your desired location

### Running the Application
1. Open `index.html` in your web browser
2. Or serve it using a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```
3. Navigate to `http://localhost:8000` in your browser

## 📖 How to Use

1. **Enter Coordinates**: 
   - Input the latitude of your desired location
   - Input the longitude of your desired location
   
2. **Get Results**: 
   - Click the "check air quality" button
   - View the air quality data displayed below

3. **Understanding the Results**:
   - **AQI**: Overall Air Quality Index (0-500+)
   - **CO**: Carbon Monoxide levels
   - **NO2**: Nitrogen Dioxide levels
   - **O3**: Ozone levels
   - **PM2.5**: Fine particulate matter (≤2.5 micrometers)
   - **PM10**: Coarse particulate matter (≤10 micrometers)
   - **SO2**: Sulfur Dioxide levels

## 🔧 API Configuration

This application uses the RapidAPI Air Quality API. The API key is currently embedded in the code for demonstration purposes.

**Important**: For production use, you should:
1. Get your own API key from [RapidAPI](https://rapidapi.com/air-quality-api-air-quality-api-default/api/air-quality/)
2. Store the API key securely (environment variables, server-side, etc.)
3. Never expose API keys in client-side code

### API Endpoint
```
GET https://air-quality.p.rapidapi.com/history/airquality
```

### Required Parameters
- `lat`: Latitude coordinate
- `lon`: Longitude coordinate

## 🎨 Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling, animations, and responsive design
- **JavaScript (ES6+)**: Dynamic functionality and API integration
- **RapidAPI**: Air quality data service

## 📁 Project Structure

```
weather.com/
├── index.html          # Main HTML file
├── index.js           # JavaScript functionality
├── README.md          # Project documentation
└── .gitignore         # Git ignore file
```

## 🎯 Key Features Explained

### Responsive Design
- Flexbox layout for centering content
- Mobile-first approach
- Adaptive styling for different screen sizes

### Modern UI Elements
- Gradient background (sky blue to light blue)
- Semi-transparent containers with backdrop blur effect
- Smooth hover animations on buttons
- Clean typography with proper spacing

### Error Handling
- Form validation for coordinate inputs
- API error handling (can be enhanced further)
- Graceful display of results

## 🔮 Future Enhancements

- [ ] Add location search by city name
- [ ] Implement geolocation for automatic coordinate detection
- [ ] Add historical air quality data charts
- [ ] Include air quality alerts and recommendations
- [ ] Add multiple language support
- [ ] Implement caching for better performance
- [ ] Add unit tests
- [ ] Create a mobile app version

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👨‍💻 Author

**merasool**
- GitHub: [@merasool](https://github.com/merasool)
- Live Demo: [https://merasool.github.io/weather.com/](https://merasool.github.io/weather.com/)

## 🙏 Acknowledgments

- [RapidAPI](https://rapidapi.com/) for providing the Air Quality API
- [GitHub Pages](https://pages.github.com/) for hosting the live demo
- The open-source community for inspiration and resources


⭐ **Star this repository if you found it helpful!**
