# flight-delay-prediction
UT Austin MSBA Project

This project builds a large-scale, machine-learning–ready dataset for predicting U.S. domestic flight delays by integrating:

U.S. DOT / BTS On-Time Performance data (flight characteristics & delays)

NOAA Global Hourly (METAR/ISD) weather observations (airport-level weather conditions)

Our goal is to create a unified, clean dataset suitable for exploratory analysis, modeling, and concept-drift evaluation before and after COVID-19.

Project Goals:
1. Predict departure delays >15 minutes using ML models.

2. Integrate flight-level data with airport weather data.

3. Engineer interpretable features such as:
      - Time of day, day of week, seasonal indicators
      - Weather attributes (visibility, wind, temperature, precipitation)
      - Rolling airport congestion/delay metrics

4. Analyze concept drift: how delay patterns changed over time (pre- vs. post-COVID).
   
5. Produce a clean, reproducible dataset for team modeling work.
