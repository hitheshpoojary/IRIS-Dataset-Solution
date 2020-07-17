<h1>PRINCIPAL COMPONENT ANALYSIS</h1>

* Principal component analysis (PCA) is a technique used for reducing the dimensionality of such datasets, increasing interpretability. At the same time minimizing information loss. It does so by creating new uncorrelated variables that successively maximize variance.
* PCA is mostly used as a tool in exploratory data analysis and for making predictive models. It is often used to visualize genetic distance and relatedness between populations. PCA is either done by singular value decomposition of a design matrix or by doing the following 2 steps:
**1.calculating the data covariance matrix of the original data.**

**2.performing eigenvalue decomposition on the covariance matrix.**

<h3>APPLICATION OF PCA:</h3>
>1. Quantitative finance->here,principal component analysis can be directly applied to the risk management of interest rate derivative portfolios
>2 .Neuroscience->A variant of principal components analysis is used in neuroscience to identify the specific properties of a stimulus that increase a neuron's probability of generating an action potential.

<h3>ADVANTAGES OF PCA:</h3>     
>1. Removes Correlated Features
>2. Improves Algorithm Performance 
>3. Reduces Overfitting
>4. Improves Visualization
<h3>DISADVANTAGES OF PCA:</h3>  
>1. Independent variables become less interpretable
>2. Data standardization is must before PCA 

<h1>IRIS_DATASET</H1>
![imagename](https://www.google.com/imgres?imgurl=https%3A%2F%2Fs3.amazonaws.com%2Fassets.datacamp.com%2Fblog_assets%2FMachine%2BLearning%2BR%2Firis-machinelearning.png&imgrefurl=http%3A%2F%2Fwww.lac.inpe.br%2F~rafael.santos%2FDocs%2FCAP394%2FWholeStory-Iris.html&tbnid=P-PGjABuYKeYpM&vet=12ahUKEwizr4KF69TqAhWlnksFHTJNAyAQMygBegUIARCyAQ..i&docid=DWcNzEt0Tz4F4M&w=1275&h=477&q=IRIS%20dataset%20info&ved=2ahUKEwizr4KF69TqAhWlnksFHTJNAyAQMygBegUIARCyAQ)
> > The Iris Dataset contains four features (length and width of sepals and petals) of 50 samples of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). These measures were used to create a linear discriminant model to classify the species. The dataset is often used in data mining, classification and clustering examples and to test algorithms.

![imagename](https://miro.medium.com/max/2186/1*duZ0MeNS6vfc35XtYr88Bg.png)
**The above graph is 2D graph of principal component 1 against principal component2**

 _In this project the accuracy of the model has been calculated using 4 technique:_
 >1. Random Forest classifier.
 >2. KNeighborsClassifier.
 >3. Support Vector Machine.
 >4. Logical Regression.
