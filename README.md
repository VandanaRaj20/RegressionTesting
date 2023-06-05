# RegressionTesting

In the below code, we first load the test data into a numpy array using the load_test_data() function. We then perform Principle Component Analysis(PCA) to reduce the dimensionality of the test data and use KMeans clustering to group the test cases into 10 clusters.

We then select the most representative test cases from each cluster using the pairwise_distances_argmin_min() function and run the reduced test cases using the run_reduced_test_cases() function.

By using machine learning to select the most representative test cases, we can effectively reduce the number of tests while still maintaining adequate test coverage. This technique can be especially useful when dealing with a large number of test cases, as it allows for more efficient testing without sacrificing accuracy.
