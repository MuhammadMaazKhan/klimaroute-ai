# 🌱 KlimaRoute AI — Hyperlocal Heat-Resilient Mobility Agent

KlimaRoute AI is an agentic microclimate navigation engine built for the FortyGuard Hackathon '26. Powered by FortyGuard hyperlocal thermal intelligence, it dynamically calculates shade and canopy corridors to protect gig-economy riders, cyclists, and vulnerable populations from extreme asphalt heat exposure.

## 🚀 Key Features
- **Hyperlocal Thermal Ingestion:** Maps surface and 2m ambient temperatures along travel segments via FortyGuard intelligence.
- **Dynamic Cool Corridors:** Snaps to shaded boulevards and urban canopies using OSRM street-graph routing.
- **Autonomous Advisory Agent:** Evaluates thermal strain penalties and provides real-time rerouting recommendations.
- **Interactive UI & Search:** Live geocoding and dual-path comparison across European & US metropolitan corridors.

## 🛠️ Project Structure
- `app_dynamic.py`: **Main Interactive Streamlit Dashboard** with live search, routing, and real-time AI advisory.
- `app.py`: Standalone Leaflet HTML generator script.

## 🚦 How to Run
```bash
# Install dependencies
pip install streamlit streamlit-folium folium requests

# Launch the interactive web app
streamlit run app_dynamic.py
