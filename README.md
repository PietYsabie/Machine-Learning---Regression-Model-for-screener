# Machine-Learning---Regression-Model-for-screener
Use fundamental stock data from datafeed unclestock.com to apply a ML algorithm and estimate portfolio returns
Apply training data in a csv format such as:

UniqueID	fundamental_advice	fund_advice_nrscore	uncle_stock_score	growth_score	value_score	greenblatt_score	piotroski_score

1	3	3	0,65	0,72	0,56	0,5	7,45
2	5	5	0,78	0,68	0,65	0,3	7,67
3	4	4	0,69	0,56	0,6	0,54	8,44
4	3	3	0,66	0,68	0,53	0,21	7,61
5	4	4	0,74	0,57	0,64	1	9,44
6	3	3	0,63	0,66	0,54	0,49	8,46

Train the model, and it will estimate a expected return for a single stock or for a portfolio.

the code returns weight coefficients for each of the input data

and show the actual retuns versus the prediction:

