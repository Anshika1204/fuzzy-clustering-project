# fuzzy-clustering-project
**Project Overview**  
This project applies Fuzzy C-Means (FCM) clustering on the famous Iris dataset to perform unsupervised classification of iris flowers into different species. Unlike hard clustering (e.g., K-Means), FCM allows each data point to belong to multiple clusters with varying membership degrees, making it a soft clustering technique.

📊 **Dataset**  
Name: Iris Dataset  
Features: Sepal length, Sepal width, Petal length, Petal width  
Classes: Setosa, Versicolor, Virginica (3 species)

🔧 **Algorithm Used**  
Fuzzy C-Means (FCM):  Assigns membership values between 0 and 1 for each point in each cluster.  
Optimizes cluster centers by minimizing an objective function based on distance and fuzziness.

🚀 **Steps Performed**  
Import and load the Iris dataset.  
Preprocess data and prepare it for clustering.  
Apply Fuzzy C-Means algorithm using scikit-fuzzy.  
Assign final clusters based on highest membership values.  
Visualize result
