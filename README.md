# AB_NYC_2019
- EDA(Data analysis & Visualization) & Deep Learning model on AB_NYC_2019 dataset.

# Task Performed -
1. Importing the packages and reading the dataset.
2. Cleaning the dataset.
3. EDA & Pre-processing.
4. Encoding the data.
5. Splitting and scaling the data.
6. Model Creation.
7. Plotting the loss graph.
8. Tuning accuracy by Early Stopping method.
9. Plotting the loss graph.
10. Showcasing the prediction.
11. Conclusion.
12. Results.
  
# Conclusion -
- There are total 48895 properties.
- The highest cost price of a property among all is of 10000$.
- The avergae price of all the listed property is of 152.720687$.
- There are total 3 types of properties Entire home/apt type, Private room type, Shared room type.
- Out of total 48895 properties 51.97% properties are entire apt type, 45.66% properties are of private room type while only 2.37% properties are available for sharing room type properties.
- The properties nearest to Fort Wadsworth and Woodrow are costly as compared to other properties.
- The number of properties decreases as the cost of properties increases.

# Results -
- Initially we had the training loss of 43305.48828125 and testing loss of 48783.6796875.
- After penalizing the error with the help of "Early Stop" method we got a training loss of 47196.41015625 and testing loss of 47670.33203125.
