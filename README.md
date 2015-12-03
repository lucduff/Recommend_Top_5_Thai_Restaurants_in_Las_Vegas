# Recommend_Top_5_Thai_Restaurants_in_LAS

PURPOSE

The purpose of this project is to recommend from the Yelp datasets top 5 Thai restaurants in Las Vegas to a user who has reviewed at least one Phoenix restaurant using not only user ratings, but also sentiment scores computed from reviews with two lexicons.

PROJECT OUTLINE

1-  Delivering Working Data Files for the Project (Directory: Data-Files)

    In the Data-Files directory, we provide the working csv files for the project although we do not provide the code used in Python/R to develop them. We do not provide the original Yelp Academic data files either. For this project, we used exclusively the business and review files. We must also warn you that we launched the development of the working data file by using the word 'restaurant' as a filter in the 'categories' column. We acknowledged that Yelp identifies the 'categories' feature in its business dataset as 'localized category names'. We narrowed the working dataset not only to users who reviewed at least one restaurant in Phoenix for alignment purposes with the Yelp Restaurant lexicon, but also subsequently to Thai restaurants to satisfy R and RAM limitations.

2-  Scoring Sentiments in Reviews Using Python NLTK and TweetTokenizer (Directory: SentimentDetection)



3-  Recommending top 5 Thai restaurants in Las Vegas Using recommenderlab for R (Directory: Recommender-Models)

LICENSE

The MIT License (MIT)

Copyright (c) 2015 Luc Duff

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
