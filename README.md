# TECHIN510_Lab5

## Overview
dynamic interface for investigating and representing data on Seattle's events, derived from a bespoke dataset created through web scraping. The tool delivers insights on the types of events, their venues, timings, and meteorological conditions, allowing for a comprehensive examination and filtration of the event scene in Seattle.

## Project Structure
scraper.py: Script for scraping event and weather data from Visit Seattle and weather APIs, storing the data in a PostgreSQL database hosted on Azure.
app.py: Streamlit application for data visualization and data filtering
db.py: Contains utility functions for database connection.

## How to run
Environment Setup: Ensure Python 3.8+ is installed.

> import streamlit as st, import pandas as pd, import pandas.io.sql as sqlio, import altair as alt, import folium, from streamlit_folium import st_folium, import plotly.express as px

## Reflection
During the development of the Seattle Events Interactive Data Visualization App, I have learned how to web scraping realtime data, data visualization through Streamlit,enhanced my skills in database management. This experience has sharpened my technical abilities and expanded my insight into presenting data in a way that is both accessible and captivating to a wide audience.
