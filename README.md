# **Name : Prisha Sawhney**
# **Roll Number : 102116052**
# **Group: 3CS10**
# **Task at Hand**
*We need to find which, among a given set of pre-trained text-classification models, has the best performance based on different evaluation metrics.*
*For this, we will use the method of TOPSIS - **T**echnique for **O**rder of **P**reference by **S**imilarity to **I**deal **S**olution*

# Models used
Here, 4 models based on text-classification are being imported:
1. distilbert/distilbert-base-uncased-finetuned-sst-2-english
2. lxyuan/distilbert-base-multilingual-cased-sentiments-student
3. cardiffnlp/twitter-roberta-base-sentiment-latest
4. siebert/sentiment-roberta-large-english

*We have created a sample dataset for the three different genres of the world, namely Education, Sports, Politics and Finance, in order to test the model for different metrics*

# Result
*Hence, we have the following result*

| Domain | Best Model | Model Name |
|-----------------|-----------------|-----------------|
| Education    | Model 2    | lxyuan/distilbert-base-multilingual-cased-sentiments-student    |
| Sports    | Model 4    | siebert/sentiment-roberta-large-english    |
| Politics    | Model 4    | siebert/sentiment-roberta-large-english    |
| Finance    | Model 4    | siebert/sentiment-roberta-large-english    |
