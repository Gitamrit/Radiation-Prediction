**Guide** : `Dr. Srinivasa Rao Gangumalla` from `Department of Earth Sciences` at `IIT Bombay`
This project aims to predict radiation levels around uranium mines using a supervised learning model. The model helps protect residents in nearby areas by providing accurate radiation risk assessments based on existing survey data.

## Table of Contents
- [Motivation](#motivation)
- [Methodology](#methodology)
- [Data](#data)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [How to Run the Project](#how-to-run-the-project)
- [Contributing](#contributing)
- [License](#license)

## Motivation
Residents living near uranium mines are often unaware of the potential radiation risks due to the absence of localized surveys. This project addresses that gap by developing a model that predicts radiation levels using data from other accessible surveys (e.g., agricultural soil tests).

## Methodology
The project employs a supervised learning approach, leveraging multivariate statistical analysis and multiple linear regression models to predict the concentration of radioactive elements such as Thorium (Th), Uranium (U), and Potassium (K). These concentrations are then used to calculate the gamma dose rate, determining whether the radiation levels are within safe limits.

### Steps:
1. **Data Generation:** Synthetic data was generated using Python's Numpy library due to the unavailability of real-world data.
2. **Modeling:** Multiple linear regression models were created to predict the concentrations of Th, U, and K based on pH, organic matter, and soil texture.
3. **Prediction:** The model calculates the gamma dose rate using the predicted concentrations.
4. **Validation:** The predicted radiation levels are checked against standard safety limits to ensure the area is safe.

## Data
Due to the lack of real-world data, synthetic data was generated using the Numpy library. The generated data includes parameters such as:
- Latitude and Longitude
- Elevation and Depth
- pH, Organic Matter, and Soil Texture
- Concentration of Th, U, and K
- Gamma Dose Rate

## Results
The model successfully predicted that the gamma dose rate in the tested area is within safe limits, demonstrating its potential application for areas that are difficult to survey physically.

## Technologies Used
- **Programming Language:** Python
- **Libraries and Frameworks:**
  - **Data Manipulation:** Numpy, Pandas
  - **Machine Learning:** Scikit-learn
  - **Statistical Analysis:** Statsmodels
  - **Data Visualization:** Matplotlib, Seaborn
- **Development Environment:** Google Colab

## How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone https://github.com/IamMahfooz/Radiation-Prediction.git

