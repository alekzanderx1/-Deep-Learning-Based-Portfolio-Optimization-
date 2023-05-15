# Deep-Learning-Based-Portfolio-Optimization

The notebooks were created on Google Colab but it can be run locally on Jupyter as well. 

## Steps to reproduce

Prerequisite: 

An API KEY is required to download data from Nasdaq Data Link. Signup [here](https://data.nasdaq.com/) to create a free account and obtain the key.
This key needs to be replaced in the place of the string 'YOUR_API_KEY' in the `DataPrepration` notebook. 

On Google Colab
  1. Upload and Run `DataPrepration` notebook sequentially in Colab, ignore the Test section.
  2. Download the contents of `FinalDatasets` folder from the File tab. 
  3. Open and Upload  `LSTMandPorfolioOptimization` to Colab in a new tab.
  4. Create a folder `FinalDatasets` in the File tab and upload all the CSVs downloaded in Step 2.
  5. Run the Notebook cells sequentially.

On Local using Jupyter 
  1. Download all the files to the same directory.
  2. Install dependicies using `pip install -r requirements.txt`. 
     If you face issues later on due to dependencies, try `pip install -r requirements2.txt` 
  3. Run `DataPrepration` notebook sequentially in Jupyter.
  4. Run `LSTMandPorfolioOptimization` notebook sequentially in Jupyter. 
