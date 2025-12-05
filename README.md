# F1 DNF Prediction

This project predicts the probability of a Formula 1 driver **not finishing (DNF)** a race using historical F1 data from 2015-2024.  

We use a **Random Forest Classifier** to model the likelihood of a DNF based on driver experience, constructor reliability, grid position, and other features.

## Dataset

The datasets used in this project are from **Kaggle**, covering historical Formula 1 races, drivers, constructors, qualifying results, and race outcomes.  

- **2015-2024 historical data:** [Formula 1 World Championship 1950–2024](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)  
- **2025 season results:** [Formula 1 Championships 1950–2025](https://www.kaggle.com/datasets/rockyt07/formula-1-championships-1950-2025)

> Note: Large CSV files are not included in this repository. You will need to download them from Kaggle and upload them to the notebook to run the analysis.


## Features Used

- Driver experience (number of past races)  
- Driver past DNF rate  
- Constructor reliability  
- Grid position  
- Driver-constructor experience  
- Categorical encodings for driver, constructor, circuit  

## How to Run

1. Open the notebook `F1_DNF_Prediction.ipynb` in Google Colab or Jupyter Notebook.  
2. Upload the required datasets (CSV files).  
3. Run all cells to train the model and see predictions for races.  

## Results

- The notebook predicts DNF probabilities for each driver per race.  
- Visualizations show **predicted vs actual DNFs** per race.  
- Feature importance is plotted to see which factors influence DNFs the most.

## Colab Notebook

You can view and run the project in Google Colab here:  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/your-notebook-link)


## License

This project is for educational purposes.

Aya
