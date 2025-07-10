QuickKart – Predicting Product Return Costs with Machine Learning
Returning a product might seem simple to a customer — but for an e-commerce company like QuickKart, it involves a complex mix of shipping fees, refurbishment work, and resale losses.

This project aims to predict the total cost of each return using machine learning. By doing so, QuickKart can make smarter decisions about return policies, save money, and improve customer satisfaction.

# What's the Problem?
Returns are expensive. Every time a customer sends something back, QuickKart deals with:

Shipping it back to a warehouse

Refurbishing or repairing the item

Losing resale value if the item can't be sold at full price

Knowing how much a return will cost before it happens can help QuickKart:

Set better return policies

Avoid high-cost returns

Streamline logistics

# What Did We Build?
We built a machine learning model that estimates total return cost based on product and return details.
# Features we used:
Product Type – Is it clothing, electronics, furniture, etc.?

Return Reason – Was it damaged? Wrong item? Size issue?

Original Price

Shipping Cost

Refurbishment Cost

Resale Value Loss %

Resale Value Loss (₹)

⚙️ Tools & Libraries:
Python

Pandas, NumPy

Scikit-learn
# How Well Does It Work?
We trained the model using Linear Regression, with an optional upgrade using Random Forest Regressor for better performance.

We used the following evaluation metrics:
MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score (How well the model fits)

MAPE (Mean Absolute Percentage Error)

The model performed surprisingly well, giving reliable cost estimates on the test set!

# Where’s the Data From?
We used a dataset hosted on Google Drive:
https://drive.google.com/file/d/1V_W59IZrTZklZPSFw6evY_T2J6uK2Dl0

It contains sample return records from various product categories.

# How to Try It Yourself
Open the .ipynb notebook in Google Colab or Jupyter

Run all the code cells

View the model results and predictions

# Run Locally?
Make sure to install these libraries:
pip install pandas scikit-learn numpy matplotlib
