# Machine Learning
In this repository, I upload my Complete Machine Learning code which I have learned from different courses(Coursera, udemy, edx, udacity), different websites blogs, different tutorials from YouTube, books, and research papers. I have covered both Supervised and Unsupervised Machine Learning Algorithms with Practical Implementation.

#### Our Machine Learning Blog
###### Link: https://medium.com/machine-learning-researcher

#### Book that we  write on Machine Learning Topic Available on Amazon
###### Title: Hands-on Machine Learning with Scikit-Learn
###### Link: https://www.amazon.com/dp/1090626797

#### These are following Projects that I have done in Machine Learning
  
 ## <------------------------------Supervised Learning ---------------------------->

## Regression

### Project 1: Match Score Prediction using Linear Regression
In this project, I take a dataset of the Cricket Score from Cricinfo Website. The Dataset contains two attributes the first attribute is Overs which is called X and the Second attribute is Score which is called Y and the dataset contains 20 instances mean 20 overs dataset and I Use a Simple Linear Regression Algorithm to predict the Score of 20th overs using the Scikit Learn Library. Basically, I use 80% data for training and 20% for Testing Base on Testing I make a prediction of Score.
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/1.Supervised%20Learning/1.Regression/1.Linear%20Regression


### Project 2: Heart Rate of Rabbits Prediction using Decision Tree Regression
In this project, I take a dataset of Heart rate baroreflexes for rabbits from Reddit Website. The dataset contains measurements of mean arterial pressure (mmHg) and heart rate (b/min) for a baroreflex curve. A data frame with 18 observations on the following 2 variables.first attribute is 'pressure' a numeric vector containing measurements of arterial pressure. The second Attribute is 'rate' a numeric vector containing measurements of heart rate. I Use a Decision Tree Regression Algorithm to predict the Heart Rate of Rabbits using the Scikit Learn Library. Basically, I use 80% data for training and 20% for Testing Base on Testing I make a prediction of Heart Rate of Rabbits.
#### Source:
Ricketts, J. H., and Head, G. A. (1999) A five-parameter logistic equation for investigating asymmetry of curvature in baroreflex studies, Am. J. Physiol. (Regulatory Integrative Comp. Physiol. 46), 277, 441–454
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/1.Supervised%20Learning/1.Regression/2.Decision%20Tree%20Regression

### Project 3: Monthly Access Return Challenge Using the Random Forrest Regression
In this project, I take a dataset of Monthly Access from Github/R datasets. The dataset contains 60 rows and 3 columns. The excess return for the Acme Cleveland Corporation are recorded along with those for all stocks listed on the New York and American Stock Exchanges were recorded over a five year period. These excess returns are relative to the return on a risk-less investment such a U.S. Treasury bills. This data frame contains the following columns: 'month character string representing the month of the observation.' market's excess return of the market as a whole.' acme' The excess return for the Acme Cleveland Corporation. I Use a Random Forrest Regression Technique to predict acme using the Scikit Learn Library. Basically, I use 80% data for training and 20% for Testing Base on Testing I make a prediction of acme.
#### Source: 
Simonoff, J.S. and Tsai, C.-L. (1994) Use of modified profile likelihood for improved tests of the constancy of variance in regression. Applied Statistics, 43, 353–370.
#### Reference: 
Davison, A.C., and Hinkley, D.V. (1997) Bootstrap Methods and Their Application. Cambridge University Press
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/1.Supervised%20Learning/1.Regression/3.Random%20Forest%20Regression

### Project 4: Delay in AIDS Reporting prediction using Support Vector Machine Regression
In this project, I take a dataset of Delay in AIDS Reporting in England and Wales from Github/R datasets. The dataset contains The aids data frame has 570 rows and 6 columns. Although all cases of AIDS in England and Wales must be reported to the Communicable Disease Surveillance Centre, there is often a considerable delay between the time of diagnosis and the time that it is reported. In estimating the prevalence of AIDS, the account must be taken of the unknown number of cases that have been diagnosed but not reported. The data set here records the reported cases of AIDS diagnosed from July 1983 and until the end of 1992. The data are cross-classified by the date of diagnosis and the time delay in the reporting of the cases. This data frame contains the following columns: the year of the diagnosis.' quarter's quarter of the year in which diagnosis was made.' delay' The time delay (in months) between diagnosis and reporting. 0 means that the case was reported within one month. Longer delays are grouped in 3-month intervals and the value of delay is the midpoint of the interval (therefore a value of 2 indicates that reporting was delayed for between 1 and 3 months).'dud'An indicator of censoring. These are categories for which full information is not yet available and the number recorded is a lower bound only.' time'
The time interval of the diagnosis. That is the number of quarters from July 1983 until the end of the quarter in which these cases were diagnosed and 'y' The number of AIDS cases reported. I Use an SVM  Regression Technique to predict Aid using the Scikit Learn Library. Basically, I use 80% data for training and 20% for Testing Base on Testing I make a prediction of Aids Report.
#### Source: 
De Angelis, D. and Gilks, W.R. (1994) Estimating acquired immune deficiency syndrome accounting for reporting delay. Journal of the Royal Statistical Society, A, 157, 31–40.
#### Reference: 
Davison, A.C., and Hinkley, D.V. (1997) Bootstrap Methods and Their Application. Cambridge University Press.
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/1.Supervised%20Learning/1.Regression/4.Suppor%20Vector%20Regression

## Classification

### Project 5: Cancer Remission and Cell Activity Prediction using the Naive Bayes Classifier
In this project, I take a dataset of Cancer Remission and Cell Activity from Github/R datasets. The dataset contains the remission data frame has 27 rows and 3 columns. This data frame contains the following columns: "LI"A measure of cell activity."m"The number of patients in each group (all values are actually 1 here). and "r" The number of patients (out of m) who went into remission. I Use a Naive Bayes Classifiers Technique to predict The number of patients (out of m) who went into remission using the Scikit Learn Library. Basically, I use 80% data for training and 20% for Testing Base on Testing I make a prediction of the number of patients (out of m) who went into remission which gave the accuracy 83.33%.
#### Source:
Freeman, D.H. (1987) Applied Categorical Data Analysis. Marcel Dekker
#### Reference: 
Davison, A.C., and Hinkley, D.V. (1997) Bootstrap Methods and Their Application. Cambridge University Press.
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/1.Supervised%20Learning/2.Classification/1.Naive%20Bayes%20Classifier

### Project 6: Email Spam Filtering Using the Decision Tree Classifier
In this project, I take a dataset of  Email Spam Filtering from the UCI Repository. The data consist of 4601 email items, of which 1813 items were identified as spam. This data frame contains the following columns: "crl.tot": total length of words in capitals." dollar": number of occurrences of the \$ symbol."bang": number of occurrences of the! symbol." money": number of occurrences of the word ‘money’. "n000": number of occurrences of the string ‘000’."make": number of occurrences of the word ‘make’."yes no": outcome variable, a factor with levels n not spam, y spam. I Use a Decision Tree Classifiers Technique to predict outcomes variable, a factor with levels n not spam, y spam using the Scikit Learn Library. Basically, I use 80% data for training and 20% for Testing Base on Testing I make a prediction of the number of the outcome variable, a factor with levels n not spam, y spam which gave the accuracy 85.12%.
#### Source:
These data are available from the University of California at Irvine Repository of Machine Learning Databases and Domain Theories.
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/1.Supervised%20Learning/2.Classification/2.Decision%20Tree%20Classification



### Project 7: Social_Network_Ads Challenges Using the Random Forrest Classifier
In this project, I take a dataset of Social_Network_Ads from the UCI Repository. The dataset contains dataset 400 instances and 5 attributes which are User_ID, Gender, Age, Estimate_Salary and last is Purchased which Target attributes. On this basis of Salary and age users purchased social networks ads or not and our Challenges to make a prediction of our dataset. I Use a random Forrest Classifier Technique to predict social network ads using the Scikit Learn Library. Basically, I use 80% data for training and 20% for Testing Base on Testing I make a prediction of social networks ads which gave the accuracy 92.50%.
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/1.Supervised%20Learning/2.Classification/3.Random%20Forest%20Classification

### Project 8: Iris dataset prediction Using the k-Nearest Neighbors(kNN)
In this project, I take a dataset of Social_Network_Ads from the UCI Repository. This is perhaps the best-known database to be found in the pattern recognition literature. Fisher's paper is a classic in the field and is referenced frequently to this day. (See Duda & Hart, for example.) The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other. Predicted attribute: class of iris plant.Attribute Information:1. sepal length in cm 2. sepal width in cm 3. petal length in cm 4. petal width in cm 5. class: -- Iris Setosa -- Iris Versicolour -- Iris Virginica.I Use a k-Nearest Neighbors Technique to predict the class of iris plant using the Scikit Learn Library. Basically, I use 80% data for training and 20% for Testing Base on Testing I make a prediction of the class of iris plant which gave the accuracy 86.66%.
#### Reference: 
1.	Fisher, R.A. "The use of multiple measurements in taxonomic problems" Annual Eugenics, 7, Part II, 179-188 (1936); also in "Contributions to Mathematical Statistics" (John Wiley, NY, 1950). 
2.	Duda, R.O., & Hart, P.E. (1973) Pattern Classification and Scene Analysis. (Q327.D83) John Wiley & Sons. ISBN 0-471-22361-1. 
3.	Dasarathy, B.V. (1980) "Nosing Around the Neighborhood: A New System Structure and Classification Rule for Recognition in Partially Exposed Environments". IEEE Transactions on Pattern Analysis and Machine Intelligence, Vol. PAMI-2, No. 1, 67-71.
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/1.Supervised%20Learning/2.Classification/4.K-Nearest%20Neighbors



### Project 9: Breast Cancer Coimbra Dataset (UCI) prediction using Logistic Regression
In this project, I take a dataset of Breast Cancer Coimbra from the UCI Repository. There are 10 predictors, all quantitative, and a binary dependent variable, indicating the presence or absence of breast cancer. The predictors are anthropometric data and parameters which can be gathered in routine blood analysis. Prediction models based on these predictors, if accurate, can potentially be used as a biomarker of breast cancer.Attribute Information:Quantitative Attributes: Age (years),BMI (kg/m2) , Glucose (mg/dL) ,Insulin (µU/mL) , HOMA ,Leptin (ng/mL) ,Adiponectin (µg/mL) ,Resistin (ng/mL) ,MCP-1(pg/dL) , Labels: 1=Healthy controls ,2=Patients.I Use a Logistic Regression Technique to predict the classification attribute Labels: 1=Healthy controls, 2=Patients using the Scikit Learn Library. Basically, I use 80% data for training and 20% for Testing Base on Testing I make a prediction of classification attribute Labels: 1=Healthy controls, 2=Patients which gave the accuracy 62.50%.
#### Reference: 
1.	Hyperresistinemia and metabolic dysregulation: risky crosstalk in obese breast cancer. 
2.	Using Resistin, glucose, age, and BMI to predict the presence of breast cancer
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/1.Supervised%20Learning/2.Classification/5.Logistic%20Regression 

### Project 10: Blood Transfusion DataSet(UCI) prediction using SVM Classifier
In this project, I take a dataset of Blood Transfusion Service Center from UCI Repository. To demonstrate the RFMTC marketing model (a modified version of RFM), this study adopted the donor database of Blood Transfusion Service Center in Hsin-Chu City in Taiwan. The center passes its blood transfusion service bus to one university in Hsin-Chu City to gather blood donated about every three months. To build an FRMTC model, we selected 748 donors at random from the donor database. These 748 donor data, each one included R (Recency - months since last donation), F (Frequency - total number of donation), M (Monetary - total blood donated in c.c.), T (Time - months since first donation), and a binary variable representing whether he/she donated blood in March 2007 (1 stand for donating blood; 0 stands for not donating blood). I Use a Support Vector Machine Classifier approach to predict a class(1 stand for donating blood; 0 stands for not donating blood) using the Scikit Learn Library. Basically, I use 80% data for training and 20% for Testing Base on Testing I make a prediction of class(1 stand for donating blood; 0 stands for not donating blood)of which gave the accuracy 72.66%.
#### Reference: 
Yeh, I-Cheng, Yang, King-Jang, and Ting, Tao-Ming, "Knowledge discovery on RFM model using Bernoulli sequence," Expert Systems with Applications, 2008.
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/1.Supervised%20Learning/2.Classification/6.Support%20Vector%20Machine

## <------------------------------Unsupervised Learning ---------------------------->

## Association Rules

### Project 11: Recommendation System for Market Basket Optimisation using Apriori Algorithm
In this project, I take a dataset of Market Basket Optimisation from the Super data Science website. This dataset contains the information of different transaction of the item like (eggs, pizza, mint, green tea, milk, soup, etc) basically these dataset contains the information of 7500 instances of transaction. I use the Apriori Algorithm to make a basket of different items mean if you buy some item they also recommend also buy this item. I am not using any library. I am using apriori library which made other developers and in the final step define association rule and then print result.The result contain (RelationRecord(items=frozenset({'light cream', 'chicken'}), support=0.004532728969470737, ordered_statistics=[OrderedStatistic(items_base=frozenset({'light cream'}), items_add=frozenset({'chicken'}), confidence=0.29059829059829057, lift=4.84395061728395)]), RelationRecord(items=frozenset({'mushroom cream sauce', 'escalope'}), support=0.005732568990801226, ordered_statistics=[OrderedStatistic(items_base=frozenset({'mushroom cream sauce'}), items_add=frozenset({'escalope'}), confidence=0.3006993006993007, lift=3.790832696715049)]),RelationRecord(items=frozenset({'pasta', 'escalope'}), support=0.005865884548726837, ordered_statistics=[OrderedStatistic(items_base=frozenset({'pasta'}), items_add=frozenset({'escalope'}), confidence=0.3728813559322034, lift=4.700811850163794)])) etc
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/2.Unsupervised%20Learning/1.Association%20Rule/1.Apriori
 
### Project 12: Recommendation System for Market Analysis using FP-Growth Algorithm
In this project, I take a dataset of Market Basket Optimisation to generate himself. The data set contains the information of different transaction but this time data contains on character instead of the full name of items. For the implementation, I am not using any library to build a recommended system for Market Analysis. This time I am code from scratch using python language and make a rule for market analysis. And finally, conclude that The FP-growth algorithm is an efficient way of finding frequent patterns in a dataset. The FP-growth algorithm works with the Apriori principle but is much faster. The Apriori algorithm generates candidate itemsets and then scans the dataset to see if they’re frequent. FP-growth is faster because it goes over the dataset only twice. The dataset is stored in a structure called an FP-tree. After the FP-tree is built, you can find frequent itemsets by finding conditional bases for an item and building a conditional FP-tree. This process is repeated, conditioning on more items until the conditional FPtree has only one item.
 ##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/2.Unsupervised%20Learning/1.Association%20Rule/2.Eclat

## Clustering
### Project 13: Mall Customers dataset for making different Clusters on the basis of spending Score using k-Mean Cluster
In this project, I take a dataset of Mall Customers from Kaggle. This Dataset has complete the information about Mall Customer Spending Score. The Dataset contains five attributes and 200 instances. The first attribute is Customer ID which has every Customer has Unique Second is Gender which is of course male/female third attribute is age which is between 19 to 70 of different customers 4th attribute is Annual Income in k$ which have different customer have a different Income some have very low some have middle and some have very high income and last attribute Spending Score which he spends on Mall. I use K-Mean Cluster and use the Elbow method to choose the optimal number of clusters on the basis of this method I choose the 5 optimal number of clusters and then visualize the result.1st cluster is Sensible who is income is low and the spend score is also low.2nd Cluster is base on that customer whose income average and spends an average.2nd Cluster is Standard is base on that customer whose income average and spend average.3rd Cluster is base on a Careful customer who is income is high and spends low in the mall.A 4th customer is a careless person whose income is low and spends score is high.5th customer is Target. Basically, the Target attribute contains those customers whose income is high and spending score is also high in this way we can easily find our target cluster using the k_mean Cluster.
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/2.Unsupervised%20Learning/2.Clustering/1.K-Mean%20Cluster

### Project 14: Mall Customers dataset for making different Clusters on the basis of spending Score using Hierarchical Cluster
In this project, I take a dataset of Mall Customers from Kaggle. This Dataset has complete the information about Mall Customer Spending Score. The Dataset contains five attributes and 200 instances. The first attribute is Customer ID which has every Customer has Unique Second is Gender which is of course male/female third attribute is age which is between 19 to 70 of different customers 4th attribute is Annual Income in k$ which have different customer have a different Income some have very low some have middle and some have very high income and last attribute Spending Score which he spends on Mall. I use the Hierarchical Cluster and use the Dendrogram method to choose the optimal number of clusters on the basis of this method I choose the 5 optimal number of clusters and then visualize the result.1st cluster is Sensible who is income is low and the spend score is also low.2nd Cluster is base on those customers whose income average and spends an average.2nd Cluster is Standard is base on those customers whose income average and spend average.3rd Cluster is base on a Careful customer who is income is high and spends low in a mall.A 4th customer is a careless person whose income is low and the spends score is high.5th customer is Target. Basically, the Target attribute contains those customers whose income is high and spending score is also high in this way we can easily find our target cluster using the Hierarchical Cluster.
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/2.Unsupervised%20Learning/2.Clustering/2.Hierarchical%20Cluster

## Dimensionality Reduction 

### Project 15: Wine dataset from(UCI) using the Principle Component Analysis(PCA) technique
In this project, I take a dataset of Wine taken from UCI. These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines. Initial data set had around 30 variables, but for some reason Only have the 13-dimensional version. The attributes are:1) Alcohol 2) Malic acid 3) Ash 4) Alkalinity of ash 5) Magnesium 6) Total phenols 7) Flavanoids 8) Nonflavanoid phenols  9) Proanthocyanins 10)Color intensity 11)Hue 12)OD280/OD315 of diluted wines 13)Proline. All attributes are continuous: No statistics available, but suggest to standardize variables for certain uses (e.g. for use with classifiers which are NOT scaling invariant) NOTE: 1st attribute is a class identifier (1-3). I use the PCA technique for the Dimensionality Reduction of the wine dataset.
#### Source: 
Forina, M. et al, PARVUS - An Extendible Package for Data Exploration, Classification and Correlation. 
Institute of Pharmaceutical and Food Analysis and Technologies, Via Brigata Salerno, 16147 Genoa, Italy. 
#### Relevant Papers:
1.	S. Aeberhard, D. Coomans, and O. de Vel, Comparison of Classifiers in High Dimensional Settings, Tech. Rep. no. 92-02, (1992), Dept. of Computer Science and Dept. of Mathematics and Statistics, James Cook University of North Queensland. (Also submitted to Technometrics). The data was used with many others for comparing various classifiers. The classes are separable, though only RDA has achieved 100% correct classification. (RDA : 100%, QDA 99.4%, LDA 98.9%, 1NN 96.1% (z-transformed data)) (All results using the leave-one-out technique) 
2.	S. Aeberhard, D. Coomans, and O. de Vel, "THE CLASSIFICATION PERFORMANCE OF RDA" Tech. Rep. no. 92-01, (1992), Dept. of Computer Science and Dept. of Mathematics and Statistics, James Cook University of North Queensland. (Also submitted to Journal of Chemometrics). Here, the data was used to illustrate the superior performance of the use of a new appreciation function with RDA.
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/2.Unsupervised%20Learning/3.Dimensionality%20Reduction/1.Principal%20Component%20Analysis

### Project 16: Wine dataset from(UCI) using the Linear Discriminant Analysis(LDA) technique
In this project, I take a dataset of Wine taken from UCI. These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines. Initial data set had around 30 variables, but for some reason Only have the 13-dimensional version. The attributes are:1) Alcohol 2) Malic acid 3) Ash 4) Alkalinity of ash 5) Magnesium 6) Total phenols 7) Flavanoids 8) Nonflavanoid phenols 9) Proanthocyanins 10)Color intensity 11)Hue 12)OD280/OD315 of diluted wines 13)Proline. All attributes are continuous: No statistics available, but suggest to standardize variables for certain uses (e.g. for use with classifiers which are NOT scaled invariant) NOTE: 1st attribute is a class identifier (1-3). I use the LDA technique for Dimensionality Reduction of wine dataset.
#### Source: 
Forina, M. et al, PARVUS - An Extendible Package for Data Exploration, Classification and Correlation. 
Institute of Pharmaceutical and Food Analysis and Technologies, Via Brigata Salerno, 16147 Genoa, Italy. 
#### Relevant Papers:
1.	S. Aeberhard, D. Coomans, and O. de Vel, Comparison of Classifiers in High Dimensional Settings, Tech. Rep. no. 92-02, (1992), Dept. of Computer Science and Dept. of Mathematics and Statistics, James Cook University of North Queensland. (Also submitted to Technometrics). The data was used with many others for comparing various classifiers. The classes are separable, though only RDA has achieved 100% correct classification. (RDA : 100%, QDA 99.4%, LDA 98.9%, 1NN 96.1% (z-transformed data)) (All results using the leave-one-out technique) 
2.	S. Aeberhard, D. Coomans, and O. de Vel, "THE CLASSIFICATION PERFORMANCE OF RDA" Tech. Rep. no. 92-01, (1992), Dept. of Computer Science and Dept. of Mathematics and Statistics, James Cook University of North Queensland. (Also submitted to Journal of Chemometrics). Here, the data was used to illustrate the superior performance of the use of a new appreciation function with RDA.
##### Project Link: https://github.com/AmirAli5/Machine-Learning/tree/master/2.Unsupervised%20Learning/3.Dimensionality%20Reduction/2.Linear%20Discriminant%20Analysis
