# Kernel SVM Model
 ![Alt text](k.png?raw=true "kernel trick")

This uses rbf kernel in the classifier. This is the only difference compared to linear SVM. Refer to SVM section for more details.

 ```
# Training the Kernel SVM model on the Training set
from sklearn.svm import SVC
classifier = SVC(kernel = 'rbf', random_state = 0)
classifier.fit(X_train, y_train)
 ```

![Alt text](kres.png?raw=true "kernel result")