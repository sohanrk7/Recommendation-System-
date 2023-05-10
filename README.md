# Recommendation System
This project aims at building an item to item recommedation system using H&M Fashion Dataset pulled from Kaggle, implementing the concepts of TF-IDF (Term Frequency and Invere Document Frequecy), and cosine similarity.

## Exploratory Data Analysis:


EDA is done to familiarize with the shape, contect and context of the data at hand.



<img width="397" alt="image" src="https://github.com/sohanrk7/Recommendation-System-/assets/133166918/9f620aea-0341-436c-b224-7ecdeda4fa39">


In the count of items section-wise, Ladieswear stands on top with the highest number
 



<img width="397" alt="image" src="https://github.com/sohanrk7/Recommendation-System-/assets/133166918/bd506a70-5244-4079-a75d-c94d6f36cc57">



Jersey fancy stands high in the item-wise count with above 2000 articles.




<img width="412" alt="image" src="https://github.com/sohanrk7/Recommendation-System-/assets/133166918/53b6febd-2d2b-452e-b4d7-b913d7edf33b">



The top 20 departments with the highest number of articles are represented using bar graphs.




<img width="412" alt="image" src="https://github.com/sohanrk7/Recommendation-System-/assets/133166918/598c5782-3735-4a9a-bbae-55d59ddc1156">



The pie chart represents that ladieswear is the group with the highest percentage of garments with around 37 percent whereas sportswear with the least with 3 percent
  



<img width="430" alt="image" src="https://github.com/sohanrk7/Recommendation-System-/assets/133166918/b48269d1-82d9-4e31-851f-6ddfcb25426b">



It is seen from the histogram that the young people with age from 20 to 30 are deemed to be the most common customers with age group 21 with the highest 6800 members.




<img width="471" alt="image" src="https://github.com/sohanrk7/Recommendation-System-/assets/133166918/34179b88-3f0e-4d54-803e-f1f926887ee0">



The bar graph represents the greatest number of transactions have come from Ladieswear and the least from children's accessories and swimwear.


A small guide to run the Jupyter notebook:
1.Import the provided data into the notebook.
The data can either be unzipped on your local machine and loaded directly into the py notebook or the zipped files can be loaded into the notebook and the following codes need to be run:

!unzip articles.csv.zip
!unzip customers.csv.zip
!unzip transactions_train.csv.zip 
In order to get the unzipped files into the notebook.

2.Run each and every block of code in a sequential manner.
3.We have provided a list  of customer_id values below for the user to check the recommendations given by our system.
4.Make sure to enter customer_id in the customers variable to obtain recommendations for the particular customer.


These are some sample customer ids for you to check the recommendations:
05ed96931b707698bc94aa53766d44686ae5ccbbc99dfbda8694ae811c54f28f

0aaa9683d5f45b85d0f9a81e2f4d4ef774fed43339fb75bab45673c6a581841a

08dc704fc579b154838922bc9b3a7e34a7da76ee7ed82c21969532b5972b3241

01a9a077a83eacc6fd946a60c4ca2aed16219fcd83d31e3110fa04630c42b96d

00402f4463c8dc1b3ee54abfdea280e96cd87320449eca8953eb06769a5c20d4

 
