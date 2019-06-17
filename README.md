# Co-purchasing-Products-Prediction

E-commerce has been one of the products of the internet which has changed the way we do shopping. It has become important for the e-commerce site owners to build a good recommendation system for increasing their sale and providing rich user experience to customers. Predicting co-purchasing products based on previous order history of users can help online shopping websites to recommend relevant products to users. 
Here, the work has been done on Amazon Co-purchasing Products dataset hosted by SNAP group of Stanford. The dataset was originally made using by
crawling amazon website and thus collecting the information about 548,552 different products (Books, music CDs, DVDs and VHS video tapes).
The project has been divided into 2 modules:
1) To build recommendation system using graph theory concepts: The concepts of clustering coefficient and degree centrality are used along with ego network for recommendation system. 
Also, other measures are used to know the top n products for recommendation system.
2) To predict whether 2 products are co-purchasing product or not?: Dataset is generated with each row as pair of products and with help of other features like Category Similarity, Title Similarity and Salesrank , we are able to predict whether that pair of products are co-purchasing or not? (Yes or No) . 
Various Supervised Machine Learning algorithms are applied in order to predict whether given pair of products are co-purchasing or not? Highest accuracy of 97% is achieved in this task through logistic regression model.
For each product the following information is available:

i) Title 

ii) Salesrank

iii) List of similar products (that get co-purchased with the current product)

iv) Detailed product categorization

v) Product reviews: time, customer, rating, number of votes, number of people that found the
review helpful.

The dataset uploaded here is processed using Pre-Processing.ipynb file from original amazon-meta.txt file.
