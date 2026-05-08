# ✈️ SkyTracker India

> **Smart Flight Pricing Intelligence for Indian Domestic Flights**

🔗 **[Live Demo](https://punitpritam788.github.io/SkyTracker-India/)**

SkyTracker India is an intelligent flight pricing tracker that monitors airfare dynamics across India's 70+ airports spanning metros, capitals, and regional hubs. Track the complete 330-day booking lifecycle and make data-driven decisions with predictive analytics, real-time price curves, and AI-powered recommendations.

![GitHub](https://img.shields.io/badge/License-MIT-blue)
![HTML](https://img.shields.io/badge/Built%20with-HTML%20%7C%20CSS%20%7C%20JavaScript-orange)
![Status](https://img.shields.io/badge/Status-Active-success)
![Airports](https://img.shields.io/badge/Coverage-70%2B%20Airports-brightgreen)

---

## 🎯 Key Features

### 📊 **Price Lifecycle Tracking**
- Monitor complete 330-day booking window from flight listing to departure
- Real-time price history with visual tracking and tier-based dynamic pricing
- Track the entire booking lifecycle across 70+ Indian airports
- Historical data analysis from T-330 to T-0 days with lifecycle progress visualization

### 📈 **Price Lifecycle Curve**
- Interactive Chart.js powered price visualization with multiple zoom levels
- 7-day, 30-day, 90-day, and full 330-day trend analysis views
- Real-time curve with predictive forecasting overlay
- Dynamic pricing patterns based on booking window proximity

### 💡 **Smart Booking Score (0-100)**
- Dynamic deal rating based on current fare position, days remaining, and trajectory
- Grade system: A+ (Exceptional Deal) → D (Poor Timing)
- Contextual recommendations for optimal booking decisions
- Real-time savings calculation vs. departure-day forecast

### 📅 **Flex Date Finder (±3 Days)**
- Compare prices ±3 days around your preferred departure date
- Identify cheapest dates at a glance with "BEST" badge highlighting
- Single-click re-tracking for alternative dates
- Visual price grid with interactive date selection

### 🗓️ **Best Day to Fly Analysis**
- Average fare breakdown by weekday (Monday-Sunday)
- Identify peak and budget-friendly days for your route
- Seasonal demand patterns visualization
- Weekend vs. weekday pricing insights

### 💰 **Price Alert System**
- Set custom target fares and receive dates when fares match your target
- Multiple sort options: date-based or price-based filtering
- Visual indicators for past, current, and future price matches
- Real-time alert checking with smart match highlighting

### 🔥 **Route Demand Indicator**
- Real-time demand levels for tracked routes with percentage breakdowns
- Understand how demand drives fare escalation near departure
- Tier-based analysis differentiating metro, capital, and regional hubs
- Social proof widget showing travelers currently watching your route

### 🎨 **Advanced Analytics Dashboard**
- **Price Heatmap Calendar**: 28-day color-coded grid (green=cheap, red=expensive)
- **Route Comparison**: Compare your route against alternative destinations
- **Fare History Breakdown**: Seasonal patterns and baseline pricing analysis
- **Live Route Path**: Interactive Leaflet map showing flight corridor with origin/destination markers
- **Forecast Confidence**: Detailed confidence level breakdown for predictions
- **Connecting Flights (1-Stop)**: Alternative routes through major Indian hubs
- **Layover Hacks**: Hidden-city ticketing opportunities with layovers

### 🌐 **70+ Airport Coverage**
- **Tier 1 Metros**: Delhi, Mumbai, Bangalore, Hyderabad, Chennai, Kolkata
- **Tier 2 Regional Capitals**: Pune, Goa, Kochi, Jaipur, Lucknow, and more
- **Tier 3 Regional Hubs**: Coimbatore, Visakhapatnam, Port Blair, Leh, and 40+ others

### 🎨 **Modern UI/UX**
- Responsive dark/light theme toggle with auto time-based switching
- Mobile-optimized design with touch-friendly interactions
- Real-time clock display and theme persistence
- Smooth animations and hover effects
- Toast notifications for user feedback

### 🔌 **Optional API Integration**
- Connect live flight data via AviationStack API (optional)
- Fallback to advanced predictive simulation model
- Seamless switching between live and simulated data
- CORS-compatible setup for production deployments

---

## 🚀 Quick Start

### **Online Access**
Simply open `index.html` in any modern web browser. No installation required!

```bash
# Clone the repository
git clone https://github.com/Punitpritam788/SkyTracker-India.git

# Open in browser
cd SkyTracker-India
open index.html  # macOS
# or
start index.html  # Windows
# or
xdg-open index.html  # Linux
```

### **Browser Requirements**
- Modern browser with ES6 support (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Chart.js library (loaded from CDN)
- Leaflet map library (loaded from CDN)

---

## 🛠️ Tech Stack

- **Frontend**: Pure HTML5, CSS3, Vanilla JavaScript (no frameworks)
- **Charting**: Chart.js for interactive price curve visualization
- **Mapping**: Leaflet.js for route path display
- **Fonts**: Google Fonts (Outfit, Fira Code)
- **Data**: Seeded pseudo-random generation for realistic fare simulation
- **Optional API**: AviationStack for live flight data integration

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Copyright

© 2026 Punitpritam788. All rights reserved.
