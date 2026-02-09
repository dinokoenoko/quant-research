Credit Risk Modeling

In this project i built an end to end credit risk modelling pipeline using historical LendingClub loan data from 2007 to 2018. 
The objective was to predict probability of default (PD) for the accepted loans, and quantify needed parameters such as credit grade, interest rate, loan term, expected loss and debt to income ratio. And apply reject inference to estimate the risk of rejected loan applicants and compare the accepted and rejected loans. 

The dataset was LendingClub, Accepted loans was amount to ~2.26M (sampled to 452k, %20) and Rejected loans ~27.6M (sampled to 1.38M)

MOdel performances:
AUC	train: 0.686	test: 0.686
Gini	train: 0.373	 test: 0.371
KS	train: 0.273	test: 0.272 
no overfitting

probability of default statistics
Mean of PD:	53.6%
Median of PD:	50.9%
IQR:	46.5% – 57.0%

accepted vs rejected comparison:

Mean PD	of accepted : 16.98%	rejected: 53.59%
Median PD	of accepted: 14.81% rejected:	50.87%

Note: 0.0% of rejected loans appear to be low risk under the model. This shows conservativeness and effectiveness of the past acceptance policy.


