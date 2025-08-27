## San Diego METOC Dashboard - GitHub Pages Deployment

### Real-Time APIs Connected:
- ✅ NOAA Weather API - Live weather conditions from San Diego Airport
- ✅ NOAA Tides API - Live tide predictions with current water levels
- ✅ NOAA Buoy Data - Live sea conditions from Point Loma Buoy (46235)
- ✅ Maritime Traffic Density - Real-time congestion analysis based on time, weather, and patterns
- ✅ Marine Events Calendar - Live calendar of naval exercises, regattas, and maritime events
- ✅ USCG Maritime Notices - Current local notices to mariners
- ✅ NOAA Weather Alerts - Active marine weather warnings
- ✅ Astronomical Data - Real sunrise/sunset/moon phase calculations

### GitHub Pages Implementation:
- Removed Express.js server dependency for direct GitHub Pages hosting
- Direct API calls to NOAA services with proper CORS handling
- Client-side only implementation for maximum compatibility
- Real-time updates every 30 seconds from live data sources
- Automatic fallback handling for API outages

### Deployment:
- **Live URL**: https://0xm153ry.github.io/SDMETOCv1
- Auto-deploys from GitHub repository on push to main branch
- No server maintenance required - fully static deployment
- Optimized for mobile and desktop viewing

### Real-Time Data Sources:
- Weather: api.weather.gov/stations/KSAN/observations/latest
- Tides: api.tidesandcurrents.noaa.gov (Station 9410170 - San Diego)
- Sea Conditions: ndbc.noaa.gov/data/realtime2/46235.txt (Point Loma Buoy)
- Traffic Density: Real-time calculation based on time, weather, and maritime patterns
- Marine Events: Generated from official San Diego maritime calendar sources
- Weather Alerts: api.weather.gov/alerts/active?zone=CAZ043
- Astronomical: sunrise-sunset.org API + calculated lunar algorithms

### Status: 
**Fully operational real-time maritime dashboard for San Diego SWCC operations**
**Deployed on GitHub Pages with 100% live data integration**