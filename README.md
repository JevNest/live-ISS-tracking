# 🌍 Real-Time ISS Tracking Dashboard

A real-time interactive dashboard built with **Python (Dash, Plotly, Pandas)** that tracks the **International Space Station (ISS)** using live data from the [Open Notify ISS API](http://api.open-notify.org/iss-now.json).

## Features
- Fetches the **current position of the ISS** every few seconds using the public API.  
- Displays the ISS trail (last N positions) on a world map.  
- Highlights the current ISS location with a marker.  
- Automatic refresh using `dcc.Interval`.  
- Built with **Dash (Plotly)** for real-time visualization.  

## Project Structure
- `app.py` → Main Dash application.  
- Uses:
  - `requests` → Fetch API data  
  - `pandas` → Manage ISS trail history  
  - `plotly` → Interactive map visualization  
  - `dash` → Build live dashboard  

## Tech Stack
- Python  
- Plotly (Dash, Graph Objects)  
- Pandas  
- Requests  
- Open Notify ISS API  

## How to Run
1. Clone this repo:  
   ```bash
   git clone https://github.com/JevNest/iss-tracking-dashboard.git
   cd iss-tracking-dashboard
2. Install dependencies:
   '''bash
  !pip install Dash
  !pip install pandas
  !pip install datetime
  !pip install pytz
 3. Run the Script:
 4. 
