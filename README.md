# Earthquakes- QGIS

🌍 <B>Earthquakes - QGIS Project</B> 🔍

Welcome to a dynamic QGIS project that visualizes earthquake data with multiple layers sourced from <B>OPEN DATA</B>. This project is built using QGIS and leverages real-time data to showcase significant earthquake activity and related geographic layers.

![QGIS Version](https://img.shields.io/badge/QGIS-3.34.15-green?style=flat&logo=qgis)

💻 <B>A Bit About Me </B>  🌱
The foundation of this project was built on a love for programming that started back in the days of the Apple IIe and coding in ASM and BASIC. After two decades of being the "outbound guy" (getting the data over the phone), my passion for programming has reignited. Now, I’m turning that passion into something meaningful—combining the power of QGIS, open data and more.

🌐 Deployed on QGIS Cloud: 
[View Project](https://qgiscloud.com/mateo_rk_inc/EarthQuakes/)

![Earthquake Visualization](https://github.com/user-attachments/assets/29a4b7de-80ca-438d-bca3-2d009e8b86ac)

📖<B>How to Read:</B>
- Larger Pink Pixels: Represent major events between February 2-15, 2025.
- Smaller Red Pixels: Show all earthquake events during the past week.
- Larger Red Pixels: Indicate Moderate Earthquakes from the last week.
- Specific to California:
  -Congressional Districts: Outlined in black for better visibility.
  -Primary & Secondary Roads: Clearly marked with blue outlines for reference.


🌍 <b>Key Layers Included:</b>
This project integrates several powerful datasets to give you a comprehensive view of earthquake activity and the surrounding geography:

- Recent Earthquakes (Magnitude ≥ 6): A high-magnitude event visualization.
- Moderate Earthquakes (Magnitude 2.5 to 5.99): Focuses on more frequent but still significant events.
- Census District Boundaries: Geographic boundaries for better context on earthquake locations.
- Primary and Secondary Roads: Essential for understanding infrastructure within earthquake-affected regions.


🚀 <B>How to Get Started:</B>
- Clone this repository to your local machine.
- Open the project in QGIS.
- Import the layer files and data (see links beow) into your QGIS project.
  - [6M USGS](https://earthquake.usgs.gov/fdsnws/event/1/query.geojson?starttime=2025-02-08%2000:00:00&endtime=2025-02-15%2023:59:59&minmagnitude=6&orderby=time)
  - [Less than 6M](https://earthquake.usgs.gov/fdsnws/event/1/query.geojson?starttime=2025-02-08%2000:00:00&endtime=2025-02-15%2023:59:59&minmagnitude=2.5&maxmagnitude=5.999999&orderby=time)
  - [CENSUS CD119](https://www2.census.gov/geo/tiger/TIGER2024/CD/tl_2024_06_cd119.zip)
  - [CENSUS ROADS](https://www2.census.gov/geo/tiger/TIGER2024/PRISECROADS/tl_2024_06_prisecroads.zip)

Feel free to explore, experiment, and use this as a base for your own projects. 🌟


