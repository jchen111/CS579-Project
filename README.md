

CS579 Social Network Analysis Project
=====================================

Nowadays, people’s reviews for automobile is not only based on its price and depreciation. The ownership cost is a key factor. One biggest automobile website Edmunds.com has came up with the idea of TCO, which means the True Cost to Own. It calculates the additional costs you may not have included when considering your next vehicle purchase, including: depreciation, interest on your loan, taxes and fees, insurance premiums, fuel costs, maintenance, and repairs.

In this project, we will first collect the review data from Edmunds via Edmunds API. Then trying to take advantage of several existing classification and regression models to complete the machine learning process. At last, we will compare the result we get from our test-set, and draw the conclusion on the connection between TCO price and customer reviews.



Member Contribution
====================
Jiaqi Chen  : collect data, logistic regression, textblob, report

Xingtan Hu  : collect data, Bernoulli / Gaussian Naive Bayes, report

Xiaoyang Lu : collect data, PPT

Files included in this assignment
==================================


***./Collect_data.ipynb***

Collecting TCO and Review data via Edmunds API.
You need to change the file path in the code.

***./data_collection_in_type/***

This folder including the initial data we collected. There is a predict_TCO_textblob.ipynb in this folder, which is the method we used in the beginning, textblob is another machine learning method.

***./edmunds_api_test.ipynb***

This is just for testing API function.

***./predict_TCO.ipnb***

This is the main code file. We have done machine learning to our data, Details in the report.

***./Presentation.pdf***

Project Presentation pdf, v3 edition

***./Proposal.pdf***

Project Proposal pdf

***./Report.pdf***

Project Report pdf

***./total_cars_review/***

This folder including the car reviews data.

***./total_cars_TCO/***

This folder including the car TCO data.

***./total_cars.txt***

This is the total cars list.


