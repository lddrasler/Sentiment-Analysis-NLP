## Sentiment Analysis COVID-19 Twitter posts

#### COVID-19


#MARCH #2020 #COVID19 #PANDEMIC #WORLDSTOPPED #SCARY #SAD #FAMILY #TOGETHER

March of 2020, the new coronavirus rapidly starts to spread throughout the world, and along with it, fear, and uncertainties. By that scary time, worldwide people started to share their viewpoints on social media even more often than usual. Twitter was one of the most common platforms for people to expose their feelings, opinions, and emotions. Thousands of tweet posts emerged at each second, analysis of these posts can show how the pandemic severely affected people’s lives.

### Natural Language processing

Natural language processing is a machine learning tool that allows computers to interact with humans using human language, understanding manual texting. 
Recently a variety of deep learning models have been applied to NLP to improve and accelerate text analytics. These models and methods are offering superior solutions to convert unstructured text into valuable data and insights.

### The project

Using Natural language processing I decided to apply models to understand what sentiment those tweet posts hold and how COVID-19 affected people’s lives.

![tensorboard](https://user-images.githubusercontent.com/84256873/159619135-85209024-4ea7-440f-ad45-cebbff16bb21.png)

### The data

The dataset used in this project was collected through Kaggle. It is free and you can find it here:

https://www.kaggle.com/ravikumarmn/covid-19-text-classification-using-bert-tpu/data

  * The dataset has about 45000 tweets, 
  * My training data has 3 classes: neutral, negative, positive. 
Based on my training data I will be able to predict which class the tweets posts on my test data would fit.

### The environment

I am working with Python programming language inside Jupyter notebook. inside this project I worked with the following tools:

     •	Pandas,
     •	NumPy,
     •	Seaborn,

  To prepare my data I used:

      •	Tokenizer,
      •	Vectorizer,
      •	GloVe,
  
  As my baseline model:
  
      •	Random Forest classifier, which I achieved a result of 60%
      •	Support vector machine, with a result of 62%, and,
      •	Logistic regression, with 61%.

  
  And I used a neural network with embedding as my final model:

      •	TensorFlow,
      •	Keras.



### Results

      • I achieved a final prediction accuracy of 0.818 for our test data,
          indicating predictions of 82 % on average.
