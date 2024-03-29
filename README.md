# Fake News Detector

This was a project for Stanford's CS230 "Deep Learning" course done in 2019. 

The project leverages linguistic features in the news articles and social context features such as user engagement with the news articles on Twitter (much thanks to Twitter's Firehose). We were able to achieve an accuracy of 84% and an F1 score of 90 with our best performing model - using transfer learning with BERT encodings for the linguistic features fed to a DNN that also takes the other features as inputs. Really, the features in the news article were sufficient to make a classification with high accuracy (>85%). The improvement in accuracy from incorporating the user tweets was marginal.

For the final course report see [here](https://drive.google.com/file/d/136gFWVrGg-P8-T5nCHtpQ40cHDeJfVZV/view?usp=sharing)
