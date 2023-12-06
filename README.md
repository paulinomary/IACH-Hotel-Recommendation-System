# Content

IACH-PROJ-DataAnalysis.ipynb:

- Provides a data preparation and analysis

IACH-PROJ-TagsModel.ipynb:

- Provides Feauture engineering and Modelling
- Recommendation System

## Content Based Recommender

Text is an effective and widely existing form of opinion expression and evaluation by users, as shown by the large number of online review comments over tourism sites, hotels, and services. As a direct expression of users’ needs and emotions, text-based tourism data mining has the potential to transform the tourism industry.

Content-based filtering is a common approach in recommendation system. The features of the items previously rated by users and the best-matching ones are recommended. In our case, we will be transforming implicit information of hotel attributes as featuers for this recommendation engine.

## Dataset

The dataset is the "515K Hotel Reviews Data in Europe" dataset on Kaggle (https:// [www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe](http://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe)). The dataset is a csv file, containing most text. The positive and negative reviews are already in columns. The reviews are all in English, collected from Booking.com from 2015 to 2017.

The dataset contains 515738 reviews for 1492 luxury hotels in Europe.

Further, landmarks information was collected using openAI, ChatGPT, to obtain the coordinates. Dataframe is created IACH-PROJ-Tagsmodel.ipynb

## Run

After running IACH-PROJ-DataAnalysis.ipynb

In IACH-PROJ-TagsModel.ipynb

- The last cell asks the user to choose a CITY and a LANDMARK (if the user doesn´t know so much about the city and its landmarks, writes NO) and the recommendation system will recommend: (during input there´s always write EXIT option)
  - 1. The ideal hotel
  - 2. The similars hotel
  - 3. An htlm file called 'folium_map.htlm' is created using folium and webbrowers libraries for a better user interaction and visualization of the recommended content.
