# Bluebook for Bulldozers

**Predict the auction sale price for a piece of heavy equipment to create a "blue book" for bulldozers.**

The goal of the contest is to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration.  The data is sourced from auction result postings and includes information on usage and equipment configurations.

Fast Iron is creating a "blue book for bull dozers," for customers to value what their heavy equipment fleet is worth at auction.

## Evaluation

The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

Sample submission files can be downloaded from the data page. Submission files should be formatted as follows:

* Have a header: "SalesID,SalePrice"
* Contain two columns
  * SalesID: SalesID for the validation set in sorted order
  * SalePrice: Your predicted price of the sale
  
 It's a virtual environment, I've already install all the tools that needed for this project using conda. You can use easily this environment.
 
 **Note:** `predictions.csv` file is for submission in Kaggle. You will make this file inside `bulldozers.ipynb` notebook.
 
 ## GitHub's File Size Limit
 
 Because GitHub has file size limit of 100.0 Mb, you should unzip `TrainAndValid.zip` file first, before use `bulldozers.ipynb` Notebook.
 And inside the notebook you will make a csv file `train_tmp` for a new dataset (After Data Cleaning).
 
 **Note:** You can see all the steps in `bulldozers.ipynb` Notebook
 
 ### Tools:
 
 * Pandas: `conda install pandas`
 * NumPy: `conda install numpy`
 * Matplotlib: `conda install matplotlib`
 * Scikit-Learn: `conda install scikit-learn`
 * Seaborn: `conda install seaborn`
