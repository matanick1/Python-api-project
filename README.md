## README for Weather Analysis and Vacation Planning Tools

### Description:
This repository contains tools for analyzing weather data across various cities and planning vacations based on weather preferences.

### Contents:

1. **api_keys.py**:
   - Contains API keys for accessing various services. Ensure you populate this file with your API keys before running the notebooks.

2. **WeatherPy.ipynb**:
   - **Purpose**: Analyze the relationship between weather variables and latitude.
   - **Main Features**:
     - Generate a list of cities using the `citipy` library.
     - Retrieve weather data from the OpenWeatherMap API.
     - Visualize relationships using scatter plots.
   
3. **VacationPy.ipynb**:
   - **Purpose**: Assist in vacation planning based on weather conditions.
   - **Main Features**:
     - Display cities on a map with points sized by humidity.
     - Filter cities based on preferred weather conditions.
     - Identify potential hotels in these cities using the Geoapify API.

### Usage:
1. Populate `api_keys.py` with your API keys.
2. Install necessary Python libraries and dependencies.
3. Run the Jupyter notebooks and follow the steps therein.
