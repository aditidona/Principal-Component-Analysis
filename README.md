## Principal-Component-Analysis
Since running classification models on large image datasets may take hours to produce output. Principle Component Analysis reduces the dimensions of Feature matrix with minimal or sometimes negligible effect on the accuracy.
## Project: Image Detection 
  - Dataset: CIFAR-10
  - Initial size of the dataset : 60000 * 32 * 32 * 3 = 60000 * 3072
  - Deciding number of components (k) :
    - I set to include 98% of variance in dataset. Got k=444
    - Hence, the size of the dataset will be reduced from *3072 to *444 by using PCA
    - Hence training time was reduced from hours to minutes with minimal reduction in accuracy
  -### Accuracy Achieved:
    - SVM: 0.5275333333333333
    - KNN: 0.33253333333333335
    - Decision Tree: 0.2384
    - Random Forest: 0.39026666666666665
    - Logistic Regression: 0.4112
    - Linear Regression: 0.07028549626456548
