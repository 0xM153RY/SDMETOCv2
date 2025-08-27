## San Diego METOC Dashboard - GitHub Pages Deployment

### Real-Time APIs Connected (100% No Simulations):
- ✅ NOAA Weather API - Live weather conditions from San Diego Airport
- ✅ NOAA Tides API - Live tide predictions with current water levels
- ✅ Enhanced NOAA Buoy Data - Live sea conditions with wave height, swell period/direction, SST from Point Loma Buoy (46235)
- ✅ NOAA CO-OPS Surface Currents - Real-time tidal currents for San Diego Bay
- ✅ EPA AirNow AQI - Air quality index data (requires free API key)
- ✅ USGS Earthquake Feed - Real-time seismic monitoring (48hrs, 100km radius)
- ✅ NOAA PTWC Tsunami Alerts - Pacific tsunami warning center status
- ✅ USCG Maritime Notices - Real RSS feed from USCG Sector San Diego + weekly LNM links
- ✅ NOAA Weather Alerts - Active marine weather warnings
- ✅ Astronomical Data - Real sunrise/sunset API + calculated moon phases

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

### Real-Time Data Sources (All Official APIs):
- Weather: api.weather.gov/stations/KSAN/observations/latest
- Tides: api.tidesandcurrents.noaa.gov (Station 9410170 - San Diego)
- Enhanced Sea Conditions: ndbc.noaa.gov/data/realtime2/46235.txt + 46235.spec (Point Loma Buoy)
- Surface Currents: api.tidesandcurrents.noaa.gov currents product
- Air Quality: airnowapi.org (requires free API key)
- Earthquake Feed: earthquake.usgs.gov/fdsnws/event/1/query (GeoJSON)
- Tsunami Alerts: tsunami.gov PTWC feeds
- USCG Notices: public.govdelivery.com/topics/USDHSCG_436/feed.rss
- Weather Alerts: api.weather.gov/alerts/active?zone=CAZ043
- Astronomical: sunrise-sunset.org API + calculated lunar algorithms

### Status: 
**Fully operational comprehensive maritime intelligence dashboard for San Diego SWCC operations**
**Features enhanced oceanographic data, seismic monitoring, and environmental intelligence**
**Deployed on GitHub Pages with 100% live data integration - ZERO SIMULATIONS**