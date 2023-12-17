# Music genres classification
Music genres classification project using Neural Network VS Decision Tree

Data Source from Kaggle : https://www.kaggle.com/datasets/purumalgi/music-genre-classification?select=train.csv&fbclid=IwAR0lwsmRtbjj4gXjc0LGGLXkwbH6qSbDQU6UT4FoelW4OzUUlNx3JDIGp4E

Training set (80 Train : 20 Test) : 17,996 rows & 17 columns
Unseen set (No label) : 7,713 rows & 16 columns

Feature Columns : artist name, popularity, danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness,
liveness, valence, tempo, duration in milliseconds and time_signature

Non-Feature Column : Track name

Class Label (11 classes) : Rock, Indie, Pop, Metal, HipHop, Alt_Music, Blues, Acoustic/Folk, Instrumental, Country and Bollywood

Accuracy Score :
Neural Network : 76.175606 %
Decision Tree : 65.604335 %
