# Zillow Data Analysis

This repository contains a Jupyter Notebook that analyzes real estate data from Zillow. The analysis includes data preprocessing, exploratory data analysis (EDA), and modeling to understand housing trends and predict property values.

## Project Overview

The notebook provides:

- Data Cleaning: Handling missing values and outliers.
- Exploratory Data Analysis: Visualizing distributions and relationships between variables.
- Modeling: Applying regression models to predict housing prices.
 
## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Installation
1. Clone Repository: git clone https://github.com/donmarcolaureano/Zillow.git
2. Navigate to the project directory: cd Zillow
3. Open the notebook: jupyter notebook Zillow.ipynb

## Analysis

### Home Values
<img width="909" alt="Screenshot 2025-05-26 at 10 23 53 AM" src="https://github.com/user-attachments/assets/f64471e5-fd94-4202-8a7d-707cd7f5ac0b" />

### Chicago 
<img width="904" alt="Screenshot 2025-05-26 at 10 18 56 AM" src="https://github.com/user-attachments/assets/b72f9832-b900-4ae3-b956-5551efeb9f8a" />

### New York
<img width="903" alt="Screenshot 2025-05-26 at 10 19 13 AM" src="https://github.com/user-attachments/assets/533f91e0-56f6-4630-9b5f-8f95fdc9652f" />

### Houston
<img width="909" alt="Screenshot 2025-05-26 at 10 19 28 AM" src="https://github.com/user-attachments/assets/2abf038b-511e-409c-9bba-64f7efab5ff7" />

## Predictive Forecasting

Using the New York data set, we used ARIMA & SARIMA models to analyze seasonal decomposition and predict future home prices

### Seasonal Decomposition
<img width="922" alt="Screenshot 2025-05-26 at 10 26 59 AM" src="https://github.com/user-attachments/assets/48e00d6d-d3e0-4f29-9192-06f961421cbc" />
The seasonal component is  1006.13 which is ~0.81% of the variation in time series.

<img width="646" alt="Screenshot 2025-05-26 at 10 28 33 AM" src="https://github.com/user-attachments/assets/2da447a7-c9d1-4df0-8443-f752c4af86bd" />

<img width="906" alt="Screenshot 2025-05-26 at 10 27 30 AM" src="https://github.com/user-attachments/assets/ed00d0ae-dd7d-40ce-b089-07b1e162e412" />

<img width="905" alt="Screenshot 2025-05-26 at 10 27 42 AM" src="https://github.com/user-attachments/assets/ce620a91-a194-4b5e-93b5-65fd5e106330" />

### Predictive Modeling
<img width="911" alt="Screenshot 2025-05-26 at 10 28 06 AM" src="https://github.com/user-attachments/assets/e6b65a33-1d71-4c31-8bcf-457675176cb3" />

<img width="472" alt="Screenshot 2025-05-26 at 10 29 23 AM" src="https://github.com/user-attachments/assets/b38c2ea9-a663-4cac-8a07-12e615c8a32f" />

<img width="894" alt="Screenshot 2025-05-26 at 10 29 32 AM" src="https://github.com/user-attachments/assets/f5c2643e-93b7-4356-b312-3f0499455828" />

<img width="879" alt="Screenshot 2025-05-26 at 10 29 43 AM" src="https://github.com/user-attachments/assets/cf87b0c8-0f1c-429d-a387-01162e544b1e" />

<img width="901" alt="Screenshot 2025-05-26 at 10 30 12 AM" src="https://github.com/user-attachments/assets/e33a67bf-a1f8-47ec-bdac-98e4f084bc1e" />

<img width="877" alt="Screenshot 2025-05-26 at 10 30 45 AM" src="https://github.com/user-attachments/assets/4d42df4b-032d-47d1-9fab-77b80650752e" />



## Usage

Run the notebook cells sequentially to perform the analysis. Ensure that the dataset is available in the specified path within the notebook.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.
