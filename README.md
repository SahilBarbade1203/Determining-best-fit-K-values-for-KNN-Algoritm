# Determining-best-fit-K-values-for-KNN-Algoritm

KNN-Nearest Best Fit K-Value

This project aims to find the best fit k value for the K-Nearest Neighbor (KNN) algorithm. KNN is a simple and popular machine learning algorithm used for classification and regression problems. The algorithm classifies an input by finding the k nearest data points and taking a majority vote of the classes of these points.
![image](https://user-images.githubusercontent.com/121399866/216979113-81250d7c-cdf4-4b42-ac0e-9a2be04211f4.png)

Installation

To install the required packages, run the following command:

Copy code
pip install -r requirements.txt
Usage

The project includes the following files:

knn.py: This script implements the KNN algorithm.
find_best_k.py: This script runs the KNN algorithm multiple times with different k values and finds the best fit k value.
data.csv: A sample data set used for demonstration purposes.
To find the best fit k value, run the following command:

css
Copy code
python find_best_k.py --data_path data.csv
This script outputs the best fit k value and plots the accuracy for each k value tested.

Contributions

Contributions are welcome. If you would like to contribute, please fork the repository and open a pull request with your changes.
