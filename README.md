## Project Setup Instructions

1. Clone this repository: `git clone https://github.com/aparikh64/NRG_practicum.git`
2. Create and activate a virtual environment:
   - Conda: `conda env create -f environment.yml` (OR `conda env create -f environment_simple.yml`) and `conda activate aditya_parikh_NRG_practicum`
3. Run Jupyter Notebook with name 'run_code.ipynb'

## All files explained:
1. 'eda.ipynb' - Jupyter Notebook for some exploratory analysis
2. 'playground.ipynb' - Jupyter Notebook for some exploratory analysis
3. 'run_code.ipynb' - Main Jupyter Notebook to reproduce my results
4. 'test_pickle_file.ipynb' - Jupyter Notebook to validate that my probabilities pickle file will work properly
5. 'aditya_parikh_predictions.csv' - CSV version of my final predictions in case the pickle file has issues
6. 'ecoshare_sales_test.csv' - original test dataset provided by NRG
7. 'ecoshare_sales_test_ap.csv' - CSV file after opening original test dataset from NRG in Msft Excel and savings again as CSV, helps standardize some columns in the way Excel interprets them
8. 'ecoshare_sales_v3.xlsx' - original training dataset provided by NRG
9. 'ecoshare_sales_v3.csv' - originial training dataset provided by NRG after opening in Msft Excel and saving as CSV, helps standardize some columns in the way Excel interprets them
10. 'aditya_parikh_predictions.pkl' - Final predictions submission for NRG
11. 'environment.yml' - Environment export using from history command
12. 'environment_simple.yml' - Environment export using no builds command
