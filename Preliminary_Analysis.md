# Project Title:               NLP: Yelp Sentiment Analysis


<p style="color:green;font-size:18px;">Group Members:<br> Ushna Arshid<br> Rabindra Yadav</p> 

### Work Done Until Now:
 <p style="color:black;font-size:15px;">We have accessd yelp review_data from the yelp website and 
   uploaded the data to github. So, basically the data has been accessed remotely from the github. We have created the dataframe as yelp_df and successfully loaded the data using pandas library.After loading the data we did data pre-processing. Here in this part we removed punctuations using string.punctuation function. We also lower-case the words and finally we removed all the stop words since they are not important for the analysis. After doing pre-processing we filtered the dataset. Here we are just using one star and five star. we are using one star for a negative review and five star for the positive review. We have assigned text from the review set to the x-variable and stars is assigned to a y-variable. Now we have used MLPClassifier to train the model. There were other options to train the model but for now we just used MLPClassifier.After training the model with the dataset we have used a confusion matrix to plot positive and negative reviews. We have created a function (conf_matrix) with parameters: y_predict, title = 'Confusion_Matrix'.After running the function we got the confusion matrix result. We found 861 positive reviews and 178 negative reviews.The accuracy of the model was found to be 93.86% which showed that our model was a good fit. <br></p>  
   
   
### Challenges that we faced:
<p style="color:black;font-size:15px;"> I thin the first challenge was how finalize about how to access the data.The dataset that we downloaded was a big file >3gb. So we could have used the data locally but since it was a big file we were having trouble in collabrating. So, as a solution we decided to use the chunk of the data by uploading to the github and accessing remotely. Another challenges we faced was determining the libraries but I think after doing some research we were fine.<br> </p>

### Future Work:
<p style="color:black;font-size:15px;"> For the final Analysis we are planning to use a bubble plotting for all the reviews, this will help us to do in depth analysis. we have also decided to to use city and state along with the positive and negative reviews. So we have to another dataset from yelp which will give us information about the city and state of the reviews. Using business dataset (which will contain City and State information) we will be able to append city and States with the reviews. We are still planning to use some other features too. Coming week we will be collaborating to add different features and hopefully we will be able to do the final analysis.</p>

### Members Contribution:
<p style="color:black;font-size:15px;"> Since we are only two member in the group, we are working closely and we haven't decided to work on different sections. But for the final analysis part we will take some specific areas ans we will work accordingly. For the project we are communicating on the regular basis so on that part we are good.</p>











```python

```
