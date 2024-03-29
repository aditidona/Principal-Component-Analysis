## Principal-Component-Analysis on CIFAR-10 dataset
- Since running classification models on large image datasets may take hours to produce output. Principle Component Analysis reduces the dimensions of Feature matrix with minimal or sometimes negligible effect on the accuracy.
- The images are labeled following a set of 10 categories:

|Class|Description|
|-----|-----------|
| `c0` | airplane |
| `c1` | automobile |
| `c2` | bird |
| `c3` | cat  |
| `c4` | deer |
| `c5` | dog |
| `c6` | frog |
| `c7` | horse |
| `c8` | ship |
| `c9` | truck |
## Project: Image Detection 
  - Dataset: CIFAR-10
  - Initial size of the dataset : 60000 * 32 * 32 * 3 = 60000 * 3072
  - Deciding number of components (k) :
    - I set to include 98% of variance in dataset. No. of components which constitute of 98% of variance was k = 444
    - Hence, the size of the dataset will be reduced from *3072 to *444 by using PCA
    - Hence training time was reduced from hours to minutes with minimal reduction in accuracy
  - ### Accuracy Achieved:
        - SVM: 0.5275333333333333
        - KNN: 0.33253333333333335
        - Decision Tree: 0.2384
        - Random Forest: 0.39026666666666665

## Screenshots
![text](k.PNG)
![text](result.PNG)

![text](test_results.PNG)


## FlowChart
![text](Methodology.png)
