#OVERVİEW;
This project reads earthquake records from a .txt file, parses and filters essential columns (like latitude and longitude),
and visualizes them using the KeplerGl library. It is a lightweight and customizable tool ideal for geospatial data exploration in Python environments.
#FEATURES;
🧰 Features
📄 Reads .txt datasets with tab-separated values
🧹 Cleans and filters invalid or missing geographic entries
📍 Visualizes valid entries (Latitude, Longitude) on an interactive map
🎯 Allows customization (zoom level, map height, data layer name, etc.)
🧪 Built using open-source tools: Jupyter Notebook, Pandas, Numpy, KeplerGl
#DATASET FORMAT;
The input dataset must include at least the following columns:
Enlem (Latitude)
Boylam (Longitude)
Yer (Location)
Olus tarihi (Date)
Mw (Magnitude)
#GETTİNG STARTED;
1)CLONE THE REPOSİTORY;
git clone https://github.com/Fatihctky/earthquake-keplergl.git
cd earthquake-keplergl
2)SET UP THE ENVİRONMENT;
conda create -n kepler_env python=3.9
conda activate kepler_env
3)INSTALL REQUIREMENTS;
pip install pandas numpy keplergl
4)RUN THE NOTEBOOK;
jupyter notebook
###Open earthquake_map.ipynb and execute all cells to render the map.
