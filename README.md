# Store Sales-Time Series Forecasting
Use machine learning to predict grocery sales

## Dataset Description
Prediction sales for the thousands of product families sold at Favorita stores located in Ecuador. The training data includes dates, store and product information, whether that item was being promoted, as well as the sales numbers. Additional files include supplementary information that may be useful in building your models.

### train.csv
- The training data, comprising time series of features **store_nbr, family**, and **onpromotion** as well as the target sales.<br>
- **store_nbr** identifies the store at which the products are sold.<br>
- **family** identifies the type of product sold.<br>
- **sales** gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).<br>
- **onpromotion** gives the total number of items in a product family that were being promoted at a store at a given date.
