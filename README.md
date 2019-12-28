## 5291 Advanced Data Analysis Final Project
# A Study on CNN Classification: Detecting Skin Cancer
+ Team members: Luyue Chen, Guoyong Xu, Hanyu Gao, Yanzhu Chen, Zhaochen Li, Xuanhong Ye, Lulu Wang, Kanyan Chen

+ Project summary:

Human Against Machine with 10000 training images (HAM10000) is a large dataset which contains 10015 dermatoscopic images and it also provides information on the performance of human expert diagnosis. The target of our project is to train a model as accurate as possible to detect different kinds of skin cancer, given the dermatoscopic images. Another objective is to build a live web app to use our model.

The first part is about exploratory data analysis. Histogram and box plot will be used in this part to reflect the relationship between different variables. To make the results more convincing, Kolmogorov-Smirnov test and Pearson’s Chi-squared test will be conducted to support the conclusion.

The second part is about CNN model building. A fine tuned MobileNet CNN will be applied to classify skin lesions into seven classes.
MobileNet’s small size and speed makes it ideal for web deployment.

After 26 iterations, the model ended with the validation loss being about 0.0044 and accuracy at 100%，Meanwhile, training loss is 0.0062 and accuracy is also 100%. Thus, we decided to stop our training and then apply it to our test data, which results in the test accuracy of 100% and the loss of 0.004.

Link to web live app: https://drive.google.com/open?id=1FX6T-ZV5QDGD6RYBg3CzK_LTE3yAkRKb
