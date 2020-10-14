# The-Genre-Of-Million-Song-Prediction-Model-
## The Goal of This Project: 
Predicting the genre of songs based on the frequency of words in lyrics by using k-nearest neighbor algorithm 

# Coding Process
 # Exploring datasets
  * Split data into two datasets such as training and testing set for future classification and evaluation the classification by using pandas package 
  * Make sure that training_set and testing_set have a mix of the genres by using python 
  * Generate bar-chart by utilizing matplotlib.pyplot for datasets proportion visualization
  * Select one song in testing_set as an example to predict its genre based on the frequency of words in the lyrics in training_set songs
 # Feature Engineering:
   Festures : a collection of words in songs
   labels: Hip-hop and Country 
  * Compare songs with the frequency of words by using scatterplot 
  * Calculate distance between the selected song in testing dataset and all songs in training dataset to determine the genre of the selected song through NumPy,         Pandas  
 # Another way to look for genre
    * Find the mode meaning the most common value by defining Mode function with python
    * The max mode indicate the genre of the songs 
# Evaluation of Classification 
  * Evaluate the accuracy of the predictions with k = 15,16,7 using k-nearest neighbor algorithm
  * Created a Chart to show the accuracy rate for different choices of k value 
# Results 
  * The chart shows that when k equals to 7, the accurancy rate of the predictions is the highest. 
  * And, in this case K = 16 is overfitting because the accurancy rate is relatively low. 

