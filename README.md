# Book_Recommendation_System

Introduction
---

Discovering the perfect book that aligns with our personal preferences can be challenging, especially for those who are not regular readers. In my capstone project, I have chosen to address this issue by building a book recommendation system. By developing this tool, I aim to predict and suggest books that individuals would enjoy reading, making the process of book selection easier and more personalized.

To address this challenge, my capstone utilize the Amazon Books Reviews dataset, available on Kaggle.com, which consists of two files: book details and user reviews. The book details file, constructed using the Google Books API, contains information on a vast collection of 212,404 unique books. On the other hand, the user reviews file contains feedback from over 3 million users, gathered from the Amazon review dataset spanning from May 1996 to July 2014.

To ensure a comprehensive recommendation experience, I employed three different approaches: a user-independent system, content-based recommendation, and collaborative system recommendation. The user-independent system offers recommendations based on overall book popularity, while content-based recommendation uses book features and user preferences to suggest similar titles. The collaborative system recommendation analyzes users' historical preferences and ratings to generate personalized recommendations. By combining these techniques, our aim is to enhance the book discovery process and provide users with tailored recommendations that match their unique tastes and interests.

In summary, my capstone project aims to create a powerful book recommendation system that enhances the book discovery process for users. By utilizing data processing, and various recommendation techniques, I strive to provide tailored book suggestions that align with individual preferences, ultimately enriching the reading experience and fostering a love for books.

---- 
Data Dictionary
---

# Books Details File
|Features|Description|
|:------------|  ---------------:|
|Title|Book Title|
|Descripe|decription of book|
|authors|Neme of book authors|
|image|url for book cover|
|previewLink|link to access this book on google Books|
|publisher|Name of the publisheer|
|publishedDate|the date of publish|
|infoLink|link to get more information about the book on google books|
|categories|genres of books|
|ratingsCount|averaging rating for book|


# Reviews File
|Features|Description|
|:------------|  ---------------:|
|id|The Id of Book|
|Title|Book Title|
|Price|The price of Book|
|User_id|Id of the user who rates the book|
|profileName|Name of the user who rates the book|
|review/helpfulness|helpfulness rating of the review, e.g. 2/3|
|review/score|rating from 0 to 5 for the book|
|review/time|time of given the review|
|review/summary|the summary of a text review|
|review/text|the full text of a review|


