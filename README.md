# Machine-Learning-Assingnment
This is a machine learning assignment task from Headless Technologies Limited .

To implement this assignment, I have followed below rules:
---
1.At first, I  try to understand how to pose detection can detect from an image, and what is undersampling and oversampling. So I read some papers in particular "DeepPose: Human Pose Estimation via Deep Neural Networks by Alexander Toshev, and Christian Szegedy ".

2.After understanding the theoretical concept, I try to combine my coding skills with the theoretical concept of this task.

3.Then I extract the body key points of all images and enumerate them with the given label CSV file which is provided as "unbalanced_keypoints.csv".

4.As the dataset is imbalanced, it might cause low generalization in training. So we need to use an approach of either undersampling or oversampling. I implement both methods.

5.using SMOTE for oversampling and RandomUnderSampler for undersampling which makes distinct CSV datasets "Under_Sampling_balanced_keypoints.csv" and "Over_Sampling_balanced_keypoints.csv"

6.At last, I visualize the result using the matplotlib library.


