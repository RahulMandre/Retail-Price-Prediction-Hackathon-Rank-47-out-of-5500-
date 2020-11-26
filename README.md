### Retail Price Prediction Hackathon 

***Rank of 47 out of ~5500 participants in the competition***

**Overview (taken from Analytics India Magazine which hosted the competition)**<br>

In this competition, we are challenging the MachineHack community to come up with an algorithm to predict the price of retail items belonging to different categories. Foretelling the Retail price can be a daunting task due to the huge datasets with a variety of attributes ranging from Text, Numbers(floats, integers), and DateTime. Also, outliers can be a big problem when dealing with unit prices.

**Dataset Description:**

* Train.csv - 284780 rows x 8 columns (Inlcudes UnitPrice Columns as Target)
* Test.csv - 122049 rows x 7 columns
 

**Attribute Description:**

* Invoice No - Invoice ID, encoded as Label
* StockCode - Unique code per stock, encoded as Label
* Description - The Description, encoded as Label
* Quantity - Quantity purchased
* InvoiceDate - Date of purchase
* UnitPrice - The target value, price of every product
* CustomerID - Unique Identifier for every Customer
* Country - Country of sales, encoded as Label
 

**Skills:**

* Multivariate Regression
* Big dataset, underfitting vs overfitting
* Optimizing RMSE to generalize well on unseen data

**Files**

* Python script (Jypyter notebook) of my final submission
