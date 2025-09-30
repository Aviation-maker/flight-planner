# Advanced Flight Planner (Streamlit App)

This is a web-based flight planning tool built with Streamlit. It allows users to plan flights between airports, select aircraft, and receive weather briefings and fuel estimates.

## Features

- Select departure, destination, and alternate airports (ICAO codes)
- Choose from common aircraft types with cruise speeds and fuel burn rates
- Calculates:
  - Great-circle distance
  - Wind-corrected ground speed
  - Estimated flight time
  - Fuel burn
  - ETOPS compliance
- Fetches METAR and TAF weather reports using AVWX API
- Generates a downloadable PDF flight plan

## Setup

1. Clone the repository or unzip the provided archive.
2. Install dependencies:
   pip install -r requirements.txt
3. Run the app:
   streamlit run flight_planner.py
