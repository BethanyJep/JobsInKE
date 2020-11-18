# Jobs in Kenya
> Twitter Analysis on Jobs posted and their legitimacy

#### Data:
In this project, I analyzed job-related tweets. Data collected has the tweets, username and specific location. This data was collected in two ways:-
*    data from specific [hashtags and keywords](https://github.com/BethanyJep/JobsInKE/blob/main/Jobs%20in%20Ke%20Twitter%20Data%20Scraping.ipynb): '#ikokazi', 'Iko Kazi KE', '#ikokazike', '#IkoKaziKE', '#ikokaziKE',' #ajiraKE' '#PataKaziKE'
*    data from [specific accounts](https://github.com/BethanyJep/JobsInKE/blob/main/Influencers%20of%20Jobs%20in%20Ke.ipynb): 'ikokaziKE, ikokaziKenya, KaziQuest and AjiraKE'

#### Analysis and Visualization:
Using the data, I analyzed major keywords and patterns used, and did some [exploratory visualization](https://github.com/BethanyJep/JobsInKE/blob/main/Cleaning%20and%20visualizing%20jobs%20in%20ke.ipynb) and analysis.  I then created a model that predicts the whether the tweet extracted was a job posted or just some random tweet using a trending hashtag.  This model could be useful for one to filter out job postings, to only view relevant posts.

I visualized data using:
 * Word Clouds
 * Bar graph counter of top 20 words
 * Factorplot


### Modelling
The performance of the models are as follows:
*Naive Bayes Classifier Accuracy* - 73.32% *Random Forest Classifier Accuracy* - 97.65%
