# Data Analysis : Online Retail Transnational Dataset
<br>
 <h2> Dataset description and source </h2>
 <hr>
The dataset used in this demonstration can be found in the UCI machine learning repository and it can be accessed via <a href = 'http://archive.ics.uci.edu/ml/datasets/Online+Retail'>this link</a>.
<br><br>
<blockquote>"This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers."</blockquote>
<br>

It contains 8 attributes which are fully described below:
- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.  
- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.  
- Description: Product (item) name. Nominal.  
- Quantity: The quantities of each product (item) per transaction. Numeric.  
- InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.  
- UnitPrice: Unit price. Numeric, Product price per unit in sterling.  
- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.  
- Country: Country name. Nominal, the name of the country where each customer resides.

<br>
 <h2> Flow of the project </h2>
<hr> 
In this demonstration, we are going to process and analyze a dataset for a non-store online retail. The complete details of each step is provided inside the notebooks. The summary of this project is as follows:

1. The first step is <a href='https://github.com/amir-hojjati/Data-Analysis-Online-Retail-Transactions/blob/master/Data-Preprocessing/Preprocessing-and-Cleaning.ipynb'>data cleaning and preprocessing</a> so we can feed good and cleaned data to the next levels.

2. The second step is <a href='https://github.com/amir-hojjati/Data-Analysis-Online-Retail-Transactions/blob/master/Data-Visualization/1-Visualization-and-Reports.ipynb'>EDA and data visualization</a> and we will inspect the cleaned data for useful information.
There will be also an <a href='https://github.com/amir-hojjati/Data-Analysis-Online-Retail-Transactions/blob/master/Data-Visualization/3-Dashboard-Sales.ipynb'>interactive dashboard</a> and a <a href='https://github.com/amir-hojjati/Data-Analysis-Online-Retail-Transactions/blob/master/Data-Visualization/2-Choropleth-Map.ipynb'>choropleth map</a> to get a better perspective.

3. In the last step we will use clustering for <a href='https://github.com/amir-hojjati/Data-Analysis-Online-Retail-Transactions/blob/master/Customer-Segmentation-and-Association-Rule-Learning/Customer-Segmentation-Clustering.ipynb'>customer segmentation</a> and to find customer groups with similar behaviors for further analysis and business strategy planning.
In this section we will also try to find the best <a href='https://github.com/amir-hojjati/Data-Analysis-Online-Retail-Transactions/blob/master/Customer-Segmentation-and-Association-Rule-Learning/Association-Rule-Mining.ipynb'>association rules</a> and to see which set of products were often bought together.

<br>
<h2> Implementation </h2>
<hr>
This project was done in python using jupyter notebook. The required libraries for complete implementation can be found in the <a href='https://github.com/amir-hojjati/Data-Analysis-Online-Retail-Transactions/blob/master/Requirements.txt'>requirements</a> file.

If there was any problem with opening the notebooks in github, it's possible to use <a href='https://nbviewer.jupyter.org/'>nbviewer</a> to open the notebooks and have them rendered by copying and pasting the notebook's url in the website.
