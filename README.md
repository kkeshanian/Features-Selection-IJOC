# Features-Selection-IJOC

This repository contains the datasets use in the for the paper entitled "Features Selection as a Nash-Bargaining Solution: Applications in Online Advertising and Information Systems"; see INFORMS Journal On Computing (IJOC). 

This repository contains 4 folders:
-	The “Online display Dataset” is used in Section 5 of the paper.  In this folder, we have included a statement on how the dataset can be obtained. 
-	The “Simulated Datasets” is used in Section 6.1 of the paper.  This folder contains 8 classes of datasets. Each class contains 12 datasets. So, in total there are 96 datasets. All datasets are generated randomly based on the procedure described in the paper. The difference between the classes is the standard deviation (reflected by the notation gamma) of the normal distribution that is used to generate the error for creating their datasets. Each dataset is a csv file. In each file, columns with label “x#”, where ‘#’ is basically a number (e.g., x1, x2, …),  are features (or independent variables). Also, the column with label “Y” is the response variable or the independent variable.   

-	The “Retail Dataset” is used in Section 6.2 of the paper.  It is basically the  "Sentiment Labelled Sentences dataset” containing online reviews posted on Amazon, IMDb, and Yelp. The raw dataset corresponding to “Retail Dataset”  can be found in the UCI machine learning repository. However, we have changed the raw data into the numeric format and extracted its features accordingly in order to be used in our paper. In our dataset corresponding to each website (Amazon or IMDb or Yelp), columns with label “x#”, where ‘#’ is basically a number (e.g., x1, x2, …),  are features (or independent variables). Also,  the column with label “Y” is the response variable or the independent variable.   
-	The “Appendix Dataset” is used in the Online Supplement of the paper.  In this folder, we have included a statement how the dataset can be obtained. 

