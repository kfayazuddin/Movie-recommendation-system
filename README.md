# Movie-recommendation-system
I have done this project under Microsoft Engage Program'22.
To build my web app ,i have done with the help of streamlit.

# NOTE:
After cloning above movie-recommendation-system file ,after importing pickle and dumping you will get two .pkl files i.e, movie_list.pkl and similarity.pkl.(at your saved folder location).

Copy this and where you will be using this app code paste the copied two .pkl files.

And to run the app file,use command:streamlit run filename.py, i.e streamlit run app.py

To get poster images ,i have used the tmdb link using API
# Simarity Score:
How does it decide which item is most similar to the item user likes? Here come the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
# How Cosine Similarity works?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

![70401457-a7530680-1a55-11ea-9158-97d4e8515ca4](https://user-images.githubusercontent.com/105848272/170863183-5dec16c0-078f-4128-8671-3618e670d3ff.png)

# Screenshorts of website
![mrs_2](https://user-images.githubusercontent.com/105848272/170863292-41348165-234e-43e8-9b61-212a7c09201b.png)
![mrs_3](https://user-images.githubusercontent.com/105848272/170863299-1a4dd317-8818-4bbd-8620-f2e4682f3b83.png)
![mrs_image1](https://user-images.githubusercontent.com/105848272/170863330-a75ce704-6ae3-4464-b261-00e7b1488f2a.png)






