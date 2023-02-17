# EpsilonAI_Final_Churn_Prediction
## this project is the final project of Data Science Diploma At EpsilonAI Institue
## EpsilonAI profiles :
- facebook : https://www.facebook.com/Epsilonaieg
- linkedin : https://www.linkedin.com/company/epsilonaieg/mycompany/
- website :  https://www.epsiloneg.com/
- Github : 

## Data Science Diploma : https://www.epsiloneg.com/course/cdsp/

## project Description 
one of the most popular problems nowadays that machine learning solves  is churn analysis and prediction so in this project we have focused on analysing data set that is about churned users and non churned users for internet service provider company.
- taking steps by starting to analyse the dataset starting from univariate analysis on each feature and then making some bi/mutlivariate analysis seeing the relation between features with each others and between features and target to know wether is there any key factors that afffect user loyalty and make him leave the company,
so by doing this analysis helps the decision makers to take the right decision that may keeps their client's loyalty,
as a final step starting to prepare the data for the modeling phase and lastly choosing the best model for predicting if the new customers will churn or not.
- using statistical methods to analyse and extracting information from the dataset like (features distributions, centeral tendancy, measure of despersion and many, boxplots and many other statistical techniques finishing with classical machine learning classification models and deploy it to web app for graphical using.
- tools that i have used are ( Pandas, Numpy, Matplotlib, re, warnings, plotly, seaborn, sklearn, category_encoders, flask, heroku, power bi)

## Buisness Understanding
- There is a big competition between Internet providers. If a providers want to increase its revenue they needs more subscriber but keep existing customer is more important than having new ones. So, providers want to know which customer should cancel his service. If the provider cancel the service, that is called churn.
- All industries suffer from voluntary churn -- the loss of customers to some other company. The survival of any business is based on its ability to retain customers. This is particularly true for phone, cable TV, satellite TV and wireless companies. How do you reduce churn? There are many ways: better products, better delivery methods, lower prices, building satisfactory customer relationships, better marketing and, above all, successful customer communications.
- Wireless companies today measure voluntary churn by a monthly figure, such as 1.9 percent or 2.1 percent. This is the average number of customers who quit their service per month. Annual churn rates for telecommunications companies average between 10 percent and 67 percent.
- Industry retention surveys have shown that while price and product are important, most people leave any service because of dissatisfaction with the way they are treated. They would not be looking around if they were happy with their current provider, its service and employees.
- Churn reduction in the telecom industry is a serious problem, but there are many things that can be done to reduce it, and, with a customer database, many ways of measuring your success.
## Data Explanation
- id: unique identifier
- is_tv_subscriber: customer has a tv subscription ?
- is_movie_package_subscriber?
- subscription_age : how many year has the customer use our service
- bill_avg : last 3 months bill avg
- reamining_contract : how many year remaining for customer contract. If null; customer didn't have a contract. The customer who has a contract time have to use their service until contract end.if they canceled their service before contract time end they pay a penalty fare. Two ways in which a customer could be using the services. One through a time-bound contract which costs less and another through a normal monthly subscription which obviously costs more. So, even if a person is not in a contract, he's still a user who's paying monthly fees.
- service_failure_count customer : call count to call center for service failure for last 3 months
- download_avg : last 3 months internet usage (GB)
- upload_avg last : 3 months upload avg (GB)
download_over_limit : most of customer has a download limit. if they reach this limit they have to pay for this. this column contain "limit over count" for last 9 months
- churn : this is the target column. if 1 customer canceled his service
## files Description
- first file (Data Analysis And machine learning project files) is resposible for the whole poject (data analysis and modeling with eployment)
- the all other files is the web app files (html, css,..etc)

## youtube videos
https://www.youtube.com/watch?v=E_rj_ckSLow&list=PLCGweKdBhoY7nJyRlSZ-AmFLmjfi15eoZ

