# Reservoir Behavior Prediction using ML

This project uses machine learning (Random Forest and XGBoost) to predict cumulative oil production (`Np`) from synthetic reservoir properties.

## Features Used
- Porosity (%)
- Permeability (mD)
- Initial Pressure (psi)
- Reservoir Depth (ft)
- Temperature (°F)
- Initial Saturations (Swi, Sgi)
- Completion Type (Cased/Open Hole)

## Models Used
- Random Forest Regressor (scikit-learn)
- XGBoost Regressor

## Folder Structure

```
reservoir-prediction/
├── notebooks/            # Jupyter notebooks
├── src/                  # Scripts for data & models
├── models/               # Trained models
├── data/                 # Input/output data
```

## Setup

```bash
git clone https://github.com/yourusername/reservoir-prediction.git
cd reservoir-prediction
pip install -r requirements.txt
```

## Run the Notebook

Open the notebook and run the cells:

```
notebooks/01_reservoir_modeling.ipynb
```

## License
MIT License
