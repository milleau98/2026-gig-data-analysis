# 2026-gig-data-analysis
MADS 699 Capstone III Project on Analyzing the Gig Economy

## Data Access Statement
See [DataAccessStatement.md](https://github.com/milleau98/2026-gig-data-analysis/edit/main/DataAccessStatement.md) for the data sources and packages used to access them

## Folder Structure
```
├───data
│   ├───final
│   ├───fred
│   ├───google_trends
│   └───yfinance
└───notebooks
    ├───data-analyses
    ├───dataset-generators
    ├───dataset-mergers
    └───feature-selection
```

## How to Run the Full Analysis
1. Once the repo is imported, run the following code to import all packages
```
pip install -r requirements.txt
```
2. Run these 3 notebooks
```
└───notebooks
    └───dataset-generators
        └───fred_dataset.ipynb
        └───google_trends.ipynb
        └───yfinance_dataset.ipynb
```
3. Then create the last dataset
```
└───notebooks
    └───dataset-generators
        └───final_dataset.ipynb
```
4. For the regression analysis, the correlation analysis should be run first to understand the feature selection (the features themselves were manually added into the regression notebook)
```
└───notebooks
    └───feature-selection
        └───correlation_analysis_for_regression.ipynb
```
5. Once the datasets have been created, all notebooks in the below folder can be executed
```
└───notebooks
    └───data-analyses
```

## License
[MIT License](https://github.com/milleau98/2026-gig-data-analysis/edit/main/License.md)