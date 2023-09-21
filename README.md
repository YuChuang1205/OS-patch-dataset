# OS patch dataset   

### A brief introduction to the OS patch dataset
OS patch dataset is an optical and SAR image patch matching dataset with the patch size of 64 × 64 pixels based on the OS dataset [[paper](https://ieeexplore.ieee.org/document/9204802)] and SIFT keypoint extraction. The dataset contains a total of 123,676 pairs of cross-spectral image patches with equal numbers of positive and negative samples. training set : test set=4 : 1 (98,940 : 24,736).   


### Document interpretation  
1. "finally_train.txt" denotes the point pair information of the training set.  
2. "finally_test.txt" denotes the point pair information of the test set .  
3. Each line in txt denotes a sample pair.  
4. Take one line as an example. The meaning of the corresponding position in "train, 175, 313, 431, 313, 431, 1" is "Folder name from OS dataset"; "image serial number"; "The x-coordinate of the keypoint of the optical image"; "The y-coordinate of the keypoint of the optical image"; "The x-coordinate of the keypoint of the SAR image"; "The y-coordinate of the keypoint of the SAR image"; "The label of the image pair. 1 for matching, 0 for nonmatching".  


### Construction of the dataset  
1. Download OS dataset [[link](https://pan.baidu.com/s/14bqaJhMSZEy7EXcXVAc77w)] with the code "vriw".  
2. Build the corresponding dataset according to the point pair information in "finally_train.txt" and "finally_test.txt".  


### Other supplements
To view the experimental benchmark based on this data set, please view our paper "Efficient Feature Relation Learning Network for Cross-Spectral Image Patch Matching" [[link](https://ieeexplore.ieee.org/document/10164118)] published on *IEEE Transactions on Geoscience and Remote Sensing*. It is worth noting that the epochs of all methods in this experimental benchmark are set to 40.  




   


