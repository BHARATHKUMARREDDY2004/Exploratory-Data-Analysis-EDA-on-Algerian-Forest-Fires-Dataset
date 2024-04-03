# Exploratory Data Analysis (EDA) on Algerian Forest Fires Dataset

This notebook contains the code for Exploratory Data Analysis (EDA) performed on the Algerian Forest Fires Dataset. The dataset includes weather data observations and FWI (Fire Weather Index) components, along with classes indicating whether a fire occurred or not.

## Dataset Information

The Algerian Forest Fires Dataset contains the following attributes:

- **Date**: Day, month ('June' to 'September'), year (2012)
- **Weather data observations**:
  - **Temp**: Temperature noon (maximum temperature) in Celsius degrees (22 to 42)
  - **RH**: Relative Humidity in % (21 to 90)
  - **Ws**: Wind speed in km/h (6 to 29)
  - **Rain**: Total day rainfall in mm (0 to 16.8)
- **FWI Components**:
  - **Fine Fuel Moisture Code (FFMC)**: Index from the FWI system (28.6 to 92.5)
  - **Duff Moisture Code (DMC)**: Index from the FWI system (1.1 to 65.9)
  - **Drought Code (DC)**: Index from the FWI system (7 to 220.4)
  - **Initial Spread Index (ISI)**: Index from the FWI system (0 to 18.5)
  - **Buildup Index (BUI)**: Index from the FWI system (1.1 to 68)
  - **Fire Weather Index (FWI)**: Index (0 to 31.1)
- **Classes**: Two classes, namely "Fire" and "Not Fire"


## Usage

You can explore the EDA findings by running the code cells in the `EDA & Feature Engineering for Algerian Dataset.ipynb` notebook.

## Acknowledgements

This dataset was obtained from the UCI Machine Learning Repository. For more details, refer to the [dataset link](https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset++).
