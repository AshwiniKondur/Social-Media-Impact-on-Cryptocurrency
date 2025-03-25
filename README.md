<div style="padding: 0; margin: 0; line-height: 1.2;">
    <h1 style="margin: 0;"><b><font color='blue'> Analysing Twitter data to determine if it impacts the Cyrptocurrency - Bitcoin and Dogecoin trends</font></b></h1>
      <p style="margin: 0;"><b> The predictive power of social media. Since social media is a fine place where people exchange thoughts, views, ideas and discuss them, to know how impactful these discussions really are and how it affects our day to day lives. Created several predictive and learning models such as regression, classification, time series forecasting, neural networks and LSTM (long short-term memory) trained on Tweets that are obtained from Twitter using the data extraction methods. We will be using the tweets related to two of the most popular crypto currency, DogeCoin and Bitcoin, and on the basis of the learning that model retains, predict the surge and depletion in the value of cryptocurrencies.</b><br>
        
![image](https://github.com/user-attachments/assets/bedd0c11-0879-48b1-ba7e-c60427addeca)


  ![image](https://github.com/user-attachments/assets/7044fd2e-da69-4fe1-924e-1d5a514718e4)                    ![image](https://github.com/user-attachments/assets/547a3c58-37b5-4129-a2fd-28984c43bfd2)
![image](https://github.com/user-attachments/assets/42de93c6-887b-47c0-9f6d-99b5bb2eb215)
![image](https://github.com/user-attachments/assets/dfabad85-2c0c-4de3-b956-efd9c550a86d)
![image](https://github.com/user-attachments/assets/fa8b213f-fc29-4d2f-8a41-55190d2f76cc)
![image](https://github.com/user-attachments/assets/3c535dba-3a38-4c5b-822e-df685f2ae0b3)
![image](https://github.com/user-attachments/assets/000dc1dc-2812-4ca7-9bdf-fdb61189edf5)
![image](https://github.com/user-attachments/assets/f13c66f1-562a-4886-89ce-c5b9bff67553)
<p style="margin: 0;"><b> 
Professional Issues and Learnings:</b><br>
<p style="margin: 0;"><b> Challenges are a part of the process. They act as an indicator to the effort that individuals put in to reach their goal & there were multiple challenges that I faced in this project. The amount of learning that I was able to derive was huge as this project taught me multiple concepts from various domains. I’ll try to list down a few of the many challenges I faced and
the learning I was able to derive.</b><br>
<p style="margin: 0;"><b>1. Selection of entities that are affected by social media - Since this work primarily revolves around understanding the power of social media, hence I wanted to select an entity that “must ” show some behaviour that is influenced by social media (atleast intuitively it must). The reason why I went ahead with cryptocurrencies is because of Dogecoin as it was quite popular was heavily influenced by Social media.</b><br>
<p style="margin: 0;"><b>2. Data extraction - Data extraction using the twitter api was challenging. There are several resources online for the same but very few of the solutions work well as there are some sort of limitations in each of the solution (either limiting the rate at which tweets can be downloaded or the number of tweets downloaded)</b><br>
<p style="margin: 0;"><b>3. Sentiment Analysis - This was a major time consuming challenge for me. I had to obtain the sentiment values for a tweet using the pretrained Cardiff NLP model, which was available on Hugging Face. The problem was its speed (it was very slow), which took a lot of time for execution.</b><br>
<p style="margin: 0;"><b>4. NLP - Understanding sentiment analysis required me to learn a lot about NLP which was not my core area of expertise. However, this has really helped me create even more interest in this field and I’ll be pursuing it actively in the future.</b><br>
<p style="margin: 0;"><b>5. Another minor challenge: extract the tweets and preprocess them. The Twitter API was a problem as I had applied for developer’s access but didn’t get that on time and otherwise we cannot get tweets from 7 days ago (and over there too there is a cap of 500 tweets per day). So I had to explore other options and that was a painstaking task.</b><br>
<p style="margin: 0;"><b>6. Deciding the set of experiments to be performed - Once I had the data, I was completely clueless in terms of how to proceed forward. The path was definitely not clear as I had to frame the problem and experiments that can do a value addition to the topic of this report, which is predictive power of media. At the same time I had to present the quantitative results as well. As it’s evident from the experiments, I’ve covered the majority of the solutions that exist for predictive modelling. Regression, Classification, Ensemble methods, Neural Networks, SARIMAX (time series modelling) and LSTM.</b><br>
<p style="margin: 0;"><b>7. Data exploration and analysis helped me a lot here as I was able to develop insights one after the other and that led me to the final step of designing and executing all the experiments successfully.</b><br>
<p style="margin: 0;"><b>8. Training neural networks is a time consuming and a tough job. I accidently did not normalize the prices resulting in a really huge training loss that was not decaying even after running multiple epochs. I was not able to figure it out for quite a long time. The problem was I used the prices without normalization and as a result, since bitcoin prices were really high (order of magnitude - thousands) hence the loss was also more. This shows how crucial the data preprocessing part is and one must take special care of this.</b><br>

  



