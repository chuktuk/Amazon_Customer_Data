# Amazon_Customer_Data
NLP and Recommendation Systems

This repo contains the data science project analyzing text data to predict positive or negative sentiment of video game reviews. The project begins with exploratory NLP analysis and moves to the sentiment analysis using Flair NLP.

The data used in this analysis is very large, and is not uploaded to this repo. It can be downloaded from https://nijianmo.github.io/amazon/index.html. The original plan was to use the books reviews, but this dataset proved too much for my local system. The decision was made to switch to the video games dataset with at least 5 reviews per game.

IPython Notebook Files located in this repo:<br>
1_Video_Games_Exploratory_NLP.ipynb   -   data wrangling and exploratory analysis of video games reviews.<br>
2_Video_Games_Flair_Model.ipynb  -  Google Colab notebook to handle Flair deep learning model for sentiment analysis.<br>
3_Final_Report_VG_NLP.ipynb  -  Summary report of the findings of the NLP analysis.<br>
TF_Keras_VG.ipynb  -  attempt to use a Keras model, that proved to be ineffective due to limited resources on my local system.<br>
zz__Experimental_Video_Game_Reviews_NLP.ipynb  -  file where different exploratory analyses were tried. I did not want to delete or lose any of this code, yet it wasn't 'pretty' enough for a final notebook.<br>
zz__1_ACD_Data_Wrangling.ipynb  -  initial wrangling project working with books data. This proved too large a dataset for my laptop alone.<br>
zz__1_Books_21Mil_Wrangling.ipynb  -  second attempt to work with a smaller version of the books data. This was still too large.<br>
zz__Colab_TF_Keras_VG.ipynb  -  attempt to try to use Keras/TF to train a model on Google Colab free version. Ultimately abandoned due to lack of resources on the free Colab version.<br>
zz__Test_Predict_VG.ipynb  -  experimental code to test the pre-trained Flair model.
