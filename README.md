# 🛡️ San Diego METOC Dashboard

> **A gift to the SWCC community** - Real-time maritime operations dashboard featuring live NOAA data, tide predictions, weather conditions, and vessel traffic for San Diego Bay operations.

## 🌊 Live Dashboard
**🔗 https://0xm153ry.github.io/SDMETOCv2**

*Deployed on GitHub Pages with real-time updates every 30 seconds*

## 📡 Real-Time Data Sources

### ✅ 100% Real-Time APIs (No Simulations)
- **🌤️ NOAA Weather** - Live conditions from San Diego Airport (KSAN)
- **🌊 NOAA Tides** - Real tide predictions for San Diego Bay (Station 9410170)  
- **⚓ Enhanced Sea Conditions** - Live buoy data with wave height, swell period/direction, SST from Point Loma Buoy (46235)
- **🌊 Surface Currents** - NOAA CO-OPS tidal currents data for San Diego Bay
- **🌫️ Air Quality** - EPA AirNow AQI data (requires free API key)
- **🌍 Earthquake Feed** - USGS real-time seismic data (past 48hrs, 100km radius)
- **🌊 Tsunami Alerts** - NOAA PTWC Pacific tsunami warning status
- **📋 USCG Maritime Notices** - Real-time RSS feed from USCG Sector San Diego + weekly LNM links
- **⚠️ Weather Alerts** - Active marine weather warnings for San Diego County
- **🌙 Astronomical** - Real sunrise/sunset API + calculated moon phases

## 🎯 Features

- **Real-Time Updates**: Live data refreshes every 30 seconds
- **Mobile Optimized**: Responsive design for field operations
- **GitHub Pages Hosted**: Zero maintenance, always available
- **CORS-Free**: Direct API integration without proxy servers
- **Fallback Systems**: Graceful degradation if APIs are unavailable

## 🚀 Quick Start

Simply visit **https://0xm153ry.github.io/SDMETOCv2** - no installation required!

### For Development
```bash
# Clone repository
git clone https://github.com/0xm153ry/SDMETOCv1.git

# Serve locally (optional)
python -m http.server 8000
# or
npx serve .
```

## 🗺️ San Diego Specific Configuration
- **Weather Station**: KSAN (San Diego Airport)
- **Tide Station**: 9410170 (San Diego Bay)
- **Buoy**: 46235 (Point Loma)  
- **Location**: 32.7157°N, 117.1611°W
- **Time Zone**: Pacific Standard Time (PST/PDT)

## 📊 Data Accuracy & Updates

| Data Source | Update Frequency | Source |
|-------------|------------------|---------|
| Weather | Every 1-10 minutes | NOAA Official API |
| Tides | Real-time predictions | NOAA Official API |
| Sea Conditions (Enhanced) | Every 10-60 minutes | Live Buoy + Spectral Data |
| Surface Currents | Real-time | NOAA CO-OPS API |
| Air Quality Index | Every hour | EPA AirNow API |
| Earthquake Feed | Real-time | USGS GeoJSON API |
| Tsunami Alerts | Real-time | NOAA PTWC |
| USCG Notices | Real-time | Official RSS Feed |
| Weather Alerts | Real-time | NOAA Official API |
| Astronomical | Daily | Sunrise-Sunset.org API |

## 🛡️ For the SWCC Community

This dashboard was created specifically to support Naval Special Warfare operations in the San Diego area. It provides critical maritime intelligence including:

- **Pre-mission Planning**: Current and forecasted conditions with enhanced oceanographic data
- **Real-time Monitoring**: Live environmental data including swell, currents, and seismic activity
- **Safety Intelligence**: Active weather warnings, tsunami alerts, and USCG maritime notices
- **Tactical Advantage**: Tide states, moon illumination, visibility, and air quality conditions
- **Environmental Awareness**: Enhanced sea state analysis with wave height, swell direction, and surface currents
- **Seismic Monitoring**: Recent earthquake activity within 100km operational radius

*Dedicated to the warriors who operate in the maritime domain.*

## 🔄 Automatic Updates

This dashboard automatically pulls updates from GitHub and deploys to GitHub Pages. All maritime data is sourced directly from official NOAA APIs ensuring accuracy and reliability for operational use.

## 📁 Technical Implementation

- **Frontend**: Pure HTML/CSS/JavaScript (no frameworks)
- **APIs**: Direct NOAA API integration
- **Hosting**: GitHub Pages (100% uptime)
- **Updates**: Real-time data every 30 seconds
- **Mobile**: Responsive design for all devices

## 🤝 Contributing

Contributions are welcome from the maritime operations community. Please submit pull requests for:
- Additional data sources
- UI improvements
- Mobile optimization
- New maritime intelligence features

## ⚠️ Disclaimer

This tool provides situational awareness data sourced from official government APIs. Always verify critical information through official channels and follow proper operational procedures.

---

**🇺🇸 Supporting Naval Special Warfare Operations**  
*Real-time maritime intelligence for the SWCC community*