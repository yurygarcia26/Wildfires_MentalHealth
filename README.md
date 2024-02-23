# Wildfires_MentalHealth
This repository contains the materials related to the article _"Wildfires and Social Media Discourse: Exploring Mental Health and Emotional Well-Being Through Twitter"_.


## Requirements

* [Anaconda](https://www.anaconda.com/products/distribution)
* [Python 3](https://www.python.org/downloads/)
* [Scikit-learn](https://scikit-learn.org/)
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Spacy](https://spacy.io/)
* [Tweepy](https://www.tweepy.org/)
* [Pycm](https://www.pycm.io/)
* [Optuna](https://optuna.org/)
* [Gensim](https://radimrehurek.com/gensim/)
* [LIWC2015](https://www.liwc.app/)


## Dataset

The Twitter Tubbs Fire dataset is available for download through the [IEEEDataPort platform](https://ieee-dataport.org/documents/twitter-tubbs-fire-dataset).

## Files

1. Collecting the initial dataset [here](https://github.com/yurygarcia26/Wildfires_MentalHealth/blob/main/1.CollectingTwitterTubbsFire.ipynb)
2. Preprocessing the dataset and filtering [here](https://github.com/yurygarcia26/Wildfires_MentalHealth/blob/main/2.DataProcessing.ipynb) and [here](https://github.com/yurygarcia26/Wildfires_MentalHealth/blob/main/3.FilterWildfireData.ipynb)
3. Sentiment Analysis [here](https://github.com/yurygarcia26/Wildfires_MentalHealth/blob/main/2.SentimentAnalysis.ipynb)
4. SA and LIWC visualizations [here](https://github.com/yurygarcia26/Wildfires_MentalHealth/blob/main/3.SA_Visualization.ipynb) and [here](https://github.com/yurygarcia26/Wildfires_MentalHealth/blob/main/3.LIWC_visualization.ipynb)
5. Word frequency and co-ocurrence [here](https://github.com/yurygarcia26/Wildfires_MentalHealth/blob/main/4.WordCloud_WordFrequency.ipynb) and [here](https://github.com/yurygarcia26/Wildfires_MentalHealth/blob/main/5.Co-occurenceWords.ipynb)
6. Distribution over time [here](https://github.com/yurygarcia26/Wildfires_MentalHealth/blob/main/6.TimeWithMostTweets.ipynb)
7. Topic modeling [here](https://github.com/yurygarcia26/Wildfires_MentalHealth/blob/main/7.LDA_During_Wildfire.ipynb)


## References

For more information, please read XXX:

If you use this data, please cite:
```
@MISC {dataset-twitter-tubbs-fire,
    author    = "García, Yury E. and Villa-Pérez, Miryam Elizabeth and Li, Kuang and Tai, Xiao Hui and Trejo, Luis A. and Daza–Torres, Maria L. and Montesinos-López, Cricelio and Nuño, Miriam",
    title     = "Twitter Tubbs Fire Dataset",
    month     = "feb",
    year      = "2024",
    doi       = "10.21227/ea4x-wp41",
    url       = "https://dx.doi.org/10.21227/ea4x-wp41",
    publisher = "IEEE Dataport"
}
```
