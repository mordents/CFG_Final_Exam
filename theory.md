### 1.1 In your own words, what does the role of a data scientist involve? (2 points)
A data scientist analyses and interprets data in order to draw evidence based conclusions about a problem/phenomenon

### 1.2 What is an outlier? Here we expect to see the following:
#### a. Definition
An outlier is a data point that doesn't seem to fit with the overall trend/pattern observed in your data
#### b. Examples
Most human beings sleep 8-10 hours on average however there will be some outliers to this for example people might suffer from insomnia
or other conditions which affect sleep (e.g. depression can result in very little or a lot of sleep)
Similarly, most women's shoe sizes in the UK are on the smaller side UK(4-6 ) but there will be some women with 
bigger feet (7-10)
#### c. Should outliers always be removed? Why?
Outliers should not always be removed unless you have a good reason for removing them
For example, while either 12 hours of sleep or 6 hours of sleep may represent natural variation, it is likely 
that someone sleeping 30 mins represents an error in measurements. 
To check whether an outlier is truly an outlier , you could check the probability that 
that value is  possible using statistical analysis  
#### d. What are other possible issues that you can find in a dataset? 4 points
You could have impossible values given your dataset - sticking with the sleep example, it wouldn't be possible to sleep less
than 0 or more than 24 hours. A lack of data may be another issue - if you do not have enough data, you often can't draw conclusions. 

### 1.3 Describe the concepts of data cleaning and data quality. Here we expect to see the following:
#### a. What is data cleaning?
Data cleaning is the process of making data suitable for later analysis. This involves dealing with (replacing or removing) any 
irrelevant data (duplicate values), standardising data (e.g. correcting misspellings in the data) and removing null values
#### b. Why is data cleaning important?
Data cleaning is important because you may come to erroneous/incomplete conclusions if data is not cleaned correctly. 
For example, if you had a dataset where people were asked their income and country and people answered with UK/United Kingdom/
England/Britain your data would be a lot harder to analyse if you didn't decide on a single label for these categories (i.e UK).
Further many ML algorithms don't work if there are null values present.
#### c. What type of mistakes do we expect to commonly see in datasets? 4 points
Data format may not be correct (e.g. something in caps when it should be lowercase), misspellings
missing values and duplicate values
#### 1.4 Discuss what is Unsupervised Learning - Clustering in Machine Learning using an example. Here we expect to see the following:
a. Definition.
Unsupervised learning is a type of machine learning (ML) algorithm 
which does not rely on labelled data. Instead, unsupervised learning infers a structure from
unlabelled data and then classifies items according to that structure
#### b. When is it used?
Unsupervised learning is used when you don't have any labelled data
#### c. What is a possible real-world application of unsupervised learning?
Unsupervised learning is used in customer suggestions on Amazon "Customers like you bought"
#### d. What are its main limitations? 7.5 points
1. It is difficult to gauge the  effectiveness of unsupervised learning given there are no pre-defined parameters /answers we aimed for in training.
There is no point of comparison.
2. Unsupervised learning needs human beings to validate input to see if it makes sense
3. It is less predictable than supervised learning and may not give you the desired groups
/outcomes
4. It usually takes longer to train as the model doesn't know what to aim for (no predefined outcome(s))
### 1.5 Discuss what is Supervised Learning - Classification in Machine Learning using an example. Here we expect to see the following:
#### a. Definition.
Supervised learning involves training a model on labelled data e.g. labelled pictures of apples and oranges
and then testing that model on unlabelled data to see whether images are correctly classified. We measure performance (by looking at measures such as accuracy and recall).
#### b. When is it used?
It is used in classification (e.g. detecting spam) and regression problems (e.g. predicting stock values)

#### c. What is a possible real-world application of supervised learning?
The task of sentiment analysis within natural language processing is an example of supervised learning. 
Sentences/text fragments are labelled as communicating a particular emotion and this data is used for training
The algorithm is then able to recognise these sentiments in the form of text. 

#### d. What data do we need for it? Is there any processing that needs to be done?
We need training data and target labels. The training data (feature vectors) is labelled and we want the algorithm to 
predict those labels on previously unseen data. Using these features, your model should be able to correctly 
classify data it is given. 