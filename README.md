# Project Summary :- 
TED is dedicated to researching and sharing knowledge that matters through short talks and presentations. Our goal is to inform and educate global audiences in an accessible way.

TED = Technology Entertainment And Design

TED is an unprofitable organisation that post videos online in Free. TED is devoted to spreading powerful ideas on just about any topic. These datasets contain over 4,000+ TED talks including transcripts in many languages. It was basically started as a conference in 1984 that designed by Richard saul wurman but due to some reasons it was unsuccesful. After 6 years in 1990 ,it back with a bang. In TED, speaker share their views and ideas to the society in 18 minutes. As of 2015, TED and its sister TEDx chapters have published more than 2000 talks for free consumption by the masses and its speaker list boasts of the likes of Al Gore, Jimmy Wales, Shahrukh Khan, and Bill Gates.

Slogan Of TED :- IDEAS WORTH SPREADING

# Objective
The main objective is to build a predictive model, which could help in predicting the views of the videos uploaded on the TEDx website.

# Features:
   * talk_id: A unique identifier for each TED Talk video.
   * title: The title of the talk.
   * speaker_1: The primary speaker for the talk.
   * all_speakers: A list of all the speakers for the talk.
   * occupations: The occupations of the speakers.
   * about_speakers: Information about the speakers, such as their backgrounds and expertise.
   * recorded_date: The date the talk was recorded.
   * published_date: The date the talk was published on the TED Talks YouTube channel.
   * event: The name of the TED event where the talk was given.
   * native_lang: The language the talk was given in.
   * available_lang: The languages the talk is available in.
   * duration: The length of the video.(in sec.)
   * topics: The topics covered in the talk.
   * related talks: Other TED Talks that are related to this talk.
   * url: The URL of the video.
   * description: A brief description of the talk.
   * transcript: A transcript of the talk.

# Target Variable :
    views: The number of views the video has received.
    
# Algorithms used for ML model:-

   * Linear Regression
   * Ridge Regression(L2)
   * Lasso Regression(L1)
   * DecisionTreeRegressor
   * GradientBoostingRegressor
