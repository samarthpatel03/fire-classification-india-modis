# fire-classification-india-modis

This project analyzes and visualizes fire incidents in India using MODIS satellite data from 2021, 2022, and 2023. The goal is to classify fire types and explore their distribution and confidence levels.

## Features

- Loads and combines MODIS fire data for three years
- Performs exploratory data analysis (EDA)
- Visualizes fire type distribution and confidence scores
- Provides summary statistics and checks for missing/duplicate data

## Project Structure

```
Edunet/
├── Data/
│   ├── modis_2021_India.csv
│   ├── modis_2022_India.csv
│   └── modis_2023_India.csv
├── Notebook/
│   └── Classification_Of _Fire_Type_in_India_Using_MODIS_Data.ipynb
├── requirements.txt
└── README.md
```

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn

Install dependencies with:

```
pip install -r requirements.txt
```

## Usage

1. Place the MODIS CSV files in the `Data` directory.
2. Open the notebook `Classification_Of _Fire_Type_in_India_Using_MODIS_Data.ipynb` in Jupyter or VS Code.
3. Run the cells to load data, perform EDA, and view visualizations.

## Visualizations

- **Fire Type Distribution:** Bar plot showing the count of each fire type.
- **Confidence Distribution:** Histogram of the confidence scores for detected fires.

## Notes

- Ensure the data files are named and placed correctly as per the paths in the notebook.
- Update file paths in the notebook if your directory structure is different.
