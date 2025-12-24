# Analyse and Predict GDP per Capita in Saudi Arabia 
This project aims to study GDP per Capitia in Saudi Arabia.

## Motivation
This project was undertaken to understand the key economic indicators that affect GDP per capita in Saudi Arabia. 
The goal is to analyze how factors such as inflation, Consumer price index(CPI),  and exports influence individual income levels.


## Libraries Used
- **pandas**: for data manipulation and analysis  
- **numpy**: for numerical operations  
- **matplotlib**: for data visualization  
- **seaborn**: for advanced plotting  
- **scikit-learn**: for machine learning models  


## Repository Structure
| File | Description |
|------|-------------|
| `ًWDI.CSV` | Dataset |
| `DSproject1.ipynb` | Jupyter Notebook with data analysis, preprocessing, and modeling |
| `README.md` | This file explaining the project |


## Summary of Results
- Linear regression was used as a baseline model to explore historical trends, providing insights rather than precise long-term forecasts. 
- Inflation appears to have a secondary influence compared to other indicators such as CPI and exports.
- Limitations include the model's inability to capture non-linear dynamics, structural changes, or unexpected external shocks.


## Acknowledgments

- Data source: [World Bank - World Development Indicators](https://databank.worldbank.org/source/world-development-indicators/preview/on#)  
- Documentation and references for data manipulation: [pandas.melt](https://pandas.pydata.org/docs/reference/api/pandas.melt.html) and [pandas.DataFrame.pivot](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.pivot.html)  
