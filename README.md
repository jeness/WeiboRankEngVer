# WeiboRank (English Version)
Weibo (a Microblog site popular in China) User Sentimental Influence Analysis Results

## Results site
1. [Collab Image](https://jeness.github.io/WeiboRankEngVer/CollabEngVer/)
2. [User Ranklist](https://jeness.github.io/WeiboRankEngVer/ranklistEngVer/)
+ Analysis text contents of Weibo and extract sentimental infomation with Python.
+ Define the weight of the followed and following link relationship with Python. 
+ Classify and rank sentimental influence of Weibo users among the SNS using PageRank iteration process.
+ Visulize sentimental analysis results of ranking and relationship network of users with Matplotlib and D3.js.
 
## Sentimental Analysis
Use Word2Vec to do the Word Embedding to represent words. 
Use Recurrent Neural Network(RNN)/LSTM (tutorial: [keras](https://keras.io/models/about-keras-models/)) to train the sentimental classification. <br>
### Steps:
1. get data and input data into matrix
2. Use [jieba](https://github.com/fxsjy/jieba) to cut the Chinese sentence into words
3. Word2Vec model set up, training, testing, fine-tune, training, testing, fine-tune...... until -> :)
4. Get the three types of sentiments: positive, negative and neutral of these sentences.<br>

### Network Structure
![network structure](https://github.com/jeness/WeiboRankEngVer/raw/master/pictures/network%20structure.png)
