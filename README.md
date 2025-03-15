# Sentiment-analysis-of-user-engagement
This project is titled: "factors that drive engagement in social media - an analysis of the cognitive appraisal of video content"

This project aims to elucidate the factors that drive engagement with video-centric social media content, focusing on the cognitive appraisal and the impact of specific content characteristics of such content.


This project answers the following research questions:
1.	What are the emotional factors that drive user engagement with video content on social media platforms?
2.	Why some videos succeed and other fail in driving the engagement of social media users even if they are posted through the same entity? 
![image](https://github.com/user-attachments/assets/529d3d7a-04f0-4878-a91b-f4b50ac79d85)

The project design:
![image](https://github.com/user-attachments/assets/272b8589-0732-4e37-9758-a966c577ce45)
we have 2 data sources:
the first one comes from a dataset of pre selected videos from the patform tiktok. then through the customized machine learning models we wrote a python script that loops through the video frames and predicts the emotional reponse by giving it a score that is later interpreted into an emotion from a 6 basic emotions developed by Ekmen 1992. The output is a dataframe composed of the emotions and their frame count. 
the second data source was through actual participants which reponsded to a survey that collect the emotional response.
Through an ETL process with power query we transformed, normalized and modeled the data as follow.
<img width="488" alt="star schema" src="https://github.com/user-attachments/assets/c45eb7f2-b7a0-4713-aedf-88492395dc48" />

Then in a comparative analysis using reporting and dashboard visualization we can answer our research questions and infer some factors from the model predictions. 

![Capture d'écran 2025-03-15 122139](https://github.com/user-attachments/assets/38c7ebd7-9968-440d-8efc-4b43ec8412c6)

![Capture d'écran 2025-03-15 122206](https://github.com/user-attachments/assets/288bcf8b-73e6-4fc3-a05b-169089df23f1)

![Capture d'écran 2025-03-15 122302](https://github.com/user-attachments/assets/4fab8699-d58b-421b-862f-87706169fe06)





