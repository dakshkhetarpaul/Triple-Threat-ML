# Triple-Threat-ML
ML Repo for Class Project

Datasets:

Gold Price Regression:
 https://www.kaggle.com/datasets/franciscogcc/financial-data

Summary: The time-series dataset tracks financial and economic trends over time of gold. It spans from 2010 to 2024, showing how these factors interact over different economic cycles. Data points come in various time intervals: daily, monthly, and trimonthly, which offer a good look at financial patterns.

Motivation: Gold is interesting because it tends to hold its value when other investments struggle. This dataset was picked to see how gold prices might connect with other financial trends over time and to get a sense of what factors impact its stability.

Task Choice: Given the nature of the data and the goal to explore how different factors influence gold prices, regression would be a good task. It can help predict future prices based on historical values and other financial indicators.

Guava Fruit Disease Classification: https://www.kaggle.com/datasets/asadullahgalib/guava-disease-dataset

Summary: The data set is comprised of 3,784 preprocessed and augmented RGB images of guava fruits, uniformly resized to 512 by 512 in PNG format. The images have three distinct classifications: Anthracnose, Fruit Flies, and Healthy Fruits. The dataset originally included 473 annotated images collected from guava orchards in Rajshahi and Pabna, Bangladesh, during the fruit-ripening season in July which is the period in which guava fruits are most susceptible to diseases. They also had a plant pathologist validate the accuracy of the classifications, which help to ensure the reliability of the data set. 

Motivation: Guava is an important crop in South Asia, as it contributes significantly to regional economies and nutrition due to a high vitamin C and fiber content. Guava production is threatened by the diseases: Anthracnose and fruit flies as well as others which can severely impact yields and economic returns. By using this dataset we can attempt to develop an automated disease detection system that enhances guava productivity and sustainability. 

Task Choice: The primary machine learning task here is Image Classification. This task will involve training a supervised learning model to accurately categorize guava fruit images into one of the three classes: Anthracnose, Fruit Flies, or Healthy Fruits. Image classification is obvious here as it allows for the development of models that can discern subtle visual differences.

Phishing Email Detection: 
https://www.kaggle.com/datasets/subhajournal/phishingemails


Summary: Text dataset that is designed to aid in the development of machine learning models that can accurately predict and classify phishing attempts based on the textual content of emails. By leveraging the dataset we can enhance email security measures, protect personal and financial information, and attempt to mitigate phishing attacks. Has 18,601 email records. All annotated to indicate whether it is a phishing attempt or a safe email. 

Motivation: Phishing emails are terrible, finding a way to classify them through machine learning makes for both an interesting project and one with a good outcome. Automating the detection of phishing emails using machine learning offers an efficient solution to enhance cybersecurity services for companies, schools, and the common person. 

Task Choice: The primary machine learning task is Text Classification

This involves training a supervised learning model to accurately categorize emails as either “Phishing” or “Safe” based on their content. Text classification is well-suited for this dataset as it allows for the development of models that can interpret and analyze the language and structure / keywords used in phishing attempts. 



Spotify Dataset:
https://www.kaggle.com/datasets/abdulszz/spotify-most-streamed-songs

Summary: This dataset is tabular and contains comprehensive information on some of the most streamed songs on Spotify, enriched with additional insights from other popular streaming platforms like Apple Music, Deezer, and Shazam. It has 953 samples and 25 columns.

Motivation: Artists and producers can understand which musical elements are likely to resonate with audiences, guiding the creative process. Analyzing features that contribute to high stream counts can reveal shifts in musical tastes and trends over time.

Task choice : Regression can be used to predict the streams of an unreleased song based on its features like number of artists, danceability, acoustics, bpm etc.


