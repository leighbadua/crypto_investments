# crypto_investments
A prototype crypto portfolio that will cluster cryptocurrencies by their performance in different time periods by using the KMeans algorithm - an unsupervised learning algorithm part of machine learning that identifies clusters and solves clustering business problems. Steps for this portfolio are divided into the following sections: 

+ Import the Data
+ Prepare the Data
+ Find the Best Value for k using the Original Data
+ Cluster Cryptocurrencies with K-means using the Original Data
+ Optimize Clusters with Principal Component Analysis (PCA)
+ Find the Best Value for k using the PCA Data
+ Cluster the Cryptocurrencies with K-means using the PCA Data
+ Visualize and Compare the Results

## Technologies
Click on the links below for documentation on each of the technologies used. This project uses the following libraries and dependencies:
+ [**Anaconda**](https://docs.anaconda.com/): an open source package and environment management system.
+ [**JupyterLab**](https://jupyterlab.readthedocs.io/en/stable/): an extensive environment using web-based user interface designed for data analysis. 
+ [**Pandas**](https://pandas.pydata.org/docs/getting_started/index.html): (included in Anaconda) a Python package data analysis toolkit.
+ [**hvPlot**](https://hvplot.holoviz.org/) incorporated into this project. 
+ [**scikitlearn**](https://scikit-learn.org/stable/install.html) an open source machine learning library that supports supervised and unsupervised learning. It also provides various tools for model fitting, data preprocessing, model selection, model evaluation, and many other utilities. 

## Installation Guide
Check to ensure that Jupyterlab is installed on your machine by entering the following into your environment using `conda list`. If any of these techologies are not installed into your environment, use the corresponding codes in your terminal: 

```
pip install -U scikit-learn
```

### Instructions to Use JupyterLab

To launch JupyterLab:
  1. Open terminal window, and type `conda activate dev`.
  2. Type `jupyter lab`. JupyterLab user interface should open in your browser. 
      a. Or copy and paste one of the URLs: "http://localhost:8888/lab?token=..." into web browser. 

To exit JupyterLab:
  1. On your web browser, use the Run button to shut down any running kernel sessions.
  2. On the menu bar, on the File menu, select Shut Down. 
  3. Okay to close tabs once a dialog box with "Server stopped" message indicates the server has stopped. 
  4. Navigate to terminal window, where you launched JupyterLab and type `conda deactivate`. This will return you to your `base` environment. 

## Usage

1. Clone the repository `https://github.com/leighbadua/crypto_investments.git`
2. Using your terminal, activate the environment and launch jupyter lab (instructions mentioned above).
3. crypto_investment portfolio in JupyterLab:

Image from notebook to import libraries and dependencies:
<img width="637" alt="image" src="https://user-images.githubusercontent.com/96001018/158056827-11f9a193-8ca2-4eba-81a9-4d546e0b6f37.png">

Observing the data found in DataFrame:
<img width="808" alt="image" src="https://user-images.githubusercontent.com/96001018/158056902-3ff17617-6783-4bf2-863d-91bd1bc52152.png">

Preview of data prepared using StandardScaler:
<img width="729" alt="image" src="https://user-images.githubusercontent.com/96001018/158056942-a52f9b08-9aa4-4e25-9c88-d8b0bf96c4cb.png">

Finding the best value for k from original market data:
<img width="701" alt="image" src="https://user-images.githubusercontent.com/96001018/158056983-e85a901f-5e0b-41d4-98b8-c355d75d3d19.png">

Cluster Cryptocurrencies with K-means using the Original Data:
<img width="782" alt="image" src="https://user-images.githubusercontent.com/96001018/158057059-72c6eb20-04eb-4ab6-a5fb-2f8cef5b6c6d.png">

Optimize Clusters with Principal Component Analysis (PCA) by reducing data down to three feature components:
<img width="652" alt="image" src="https://user-images.githubusercontent.com/96001018/158057099-3078ed64-0a1e-4ded-9392-906288717fe3.png">

Find the Best Value for k using the PCA Data:
<img width="763" alt="image" src="https://user-images.githubusercontent.com/96001018/158057199-2a5cdab6-a692-46cd-96db-b006a41902ff.png">

Cluster the Cryptocurrencies with K-means using the PCA Data:
<img width="707" alt="image" src="https://user-images.githubusercontent.com/96001018/158057222-8f2d2c34-d504-4ccc-a4bb-899d28191356.png">

Visualize and Compare the Results. Side by side comparison of the visualizations. Review the notebook for the analysis. 
<img width="985" alt="image" src="https://user-images.githubusercontent.com/96001018/158057263-9999a0e9-866c-4ad4-ac70-6a22aec4cdf1.png">
<img width="988" alt="image" src="https://user-images.githubusercontent.com/96001018/158057311-c0a7a747-f560-40c3-b111-9bdf6c99f491.png">


 ## Contributors
Leigh Anne Badua leighbadua@gmail.com 

## License
MIT


