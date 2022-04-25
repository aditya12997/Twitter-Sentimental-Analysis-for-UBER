
# Twitter Sentimental Analysis for UBER


<img width="586" alt="Screenshot 2022-04-25 at 6 09 31 PM" src="https://user-images.githubusercontent.com/54794852/165129364-99ec8189-c9e5-4c14-a632-86c8d6324831.png">

This project is related to perform a Sentimental Analysis on the data extracted from the TWITTER API where we are performing a Sentimental Analysis about what the users think about the services that is being provided by UBER. This project can help us understand what kind of reviews are the service attracting and how can uber leverage this analysis to make instant changes. 



## Extracting your Twitter Keys from the developer account.

For those who are new to the API world, this project wont be possible without the use of API which can be access from Twitter.
Below I leave a link to understand how can one extract the keys to further perform actions.

Link - https://youtu.be/gLZE1L8UfqA

    
## Let the Data Speak for itself!!!

When we extract the data and play around with it we can further go and plot this data in a way where we can measure the sentiment. 
How do we measure the sentiment?
Well, in sentimental analysis there are 2 terms called

Polarity - Polarity is float which lies in the range of [-1,1] where 1 means positive statement and -1 means a negative statement.

Subjectivity - Subjective sentences generally refer to personal opinion, emotion or judgment whereas objective refers to factual information. Subjectivity is also a float which lies in the range of [0,1].

'''Credits - Analytics Vidhya portal'''

With the polarity score that we extracted we can set a threshold for the sentiment as one can see where it segregates the data into different types of Sentiment like Positive, Negative, Neutral.

Furthermore, once we have classified the sentiment based on it's score we can check the value counts for it to understand the ratio. 

We get 
Positive sentiment - 27.5%
Negative Sentiment - 22%
Neutral Sentiment - 50.5%

<img width="443" alt="Screenshot 2022-04-25 at 6 04 51 PM" src="https://user-images.githubusercontent.com/54794852/165128550-4ecdbbf0-4d01-413d-a375-61a21662eded.png">

Looking at the spread of the data points one can clearly say that the are scattered around and neither they have strong negative nor positive sentiment, but most of it is Neutral which indicates that UBER can actually implement strategies and improves its services by understanding the painpoints of the customers.

<img width="684" alt="Screenshot 2022-04-25 at 6 05 21 PM" src="https://user-images.githubusercontent.com/54794852/165128644-1dbad986-8d84-4f5f-9192-532f4137577f.png">


## Conclusion

With our analysis performed on the streamed data. We can hereby make suggestions on the quality of service provided by the drivers is not very pleasant.
Uber has a high neutral sentiment and this could be improved upon by reducing the waiting time, quality of the rides until the journey, payment issues and more.

Although we must keep in mind that, this analysis is performed on a limited data which was streamed in realtime. 
These responses could vary alot depending on many situations the customers and drivers find themselves in. 




