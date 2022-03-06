# Segment-Images-Acquired-by-a-Small-UAV
Kaggle competition

For the purpose of the FDL course you will have to implement and solve a remote sensing problem using recent deep learning techniques. In particular, the main objective of this challenge is to segment images acquired by a small UAV (sUAV) at the area on Houston, Texas. These images were acquired in order to assess the damages on residential and public properties after Hurricane Harvey. In total there are 25 categories of segments (e.g. roof, trees, pools etc.).

The task is to design and implement a deep learning model in order to perform the automatic segmentation of such images. The model can be trained using the train images which contain pixel-wise annotations. Using the trained model, a prediction on the test images should be performed and submitted on the platform. Depending on the performance of the submitted file and the leaderboard you will be ranked accordingly using macro F1 score.

This competition is evaluated on the mean Dice coefficient. The Dice coefficient can be used to compare the pixel-wise agreement between a predicted segmentation and its corresponding ground truth. The formula is given by:

The final deeplabv3plus model predicts with 76 F1 Score, Ranks 8/38.
