# Pipelines Project

![alt text](https://memegenerator.net/img/instances/81049728.jpg)

## This project is focused in this things:

**- Finding a dataset and cleaning it up!**

**- Enrich the set with external data or create another dataset as long as is related in order to analize both of them at the same time.**

**- Getting the data from an API or via webscraping.**

**- Create some reports and visualizations to understand the analysis and to get a valuable hypothesis!**

The selected dataset is about reviews on different 'Bluetooth Earphones' from the Amazon webpage (in india). In this dataset we actually find that there's two
of them. One stores all the reviews, stars of each review and the name of the product that is being reviewed.
The other dataset stores the product's name, an URL link to the web page of the named product, a reference id and also its price in Rupees (india's local currency).
After cleaning all the things that are not the objective of our interest and the things we want to prove, we also convert the indian local currency to our selected
currency, which is Euros, the currency that we'll be working with.

Once everything is ready and the datasets are prepared and clean, we proceed to use the Amazon API (Rainforest) to obtain prices, reviews and similar prices of 
'Wired Earphones'. This is intended to compare and obtain meaningful conclusions about this two sectors of the same market (the earphones market) which are opponents of each other in the terms of sales and possibilities.
When we've get all the necessary data from the API, we need to convert that into actual useful dataframes with pandas.

Finally, we will plot all the results to extract our verified conclusions and obtain the contrasted data of our interest which will be guided by our hypothesis.
