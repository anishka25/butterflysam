# BUTTERFLY SEGMENT ANYTHING MODEL

- Colab Link [Click Here](https://colab.research.google.com/drive/1bvJy5g0IqvaNEu1Z3elG2ebDigw9VylG?usp=sharing)
- Dataset Used: [Butterfly Dataset](https://www.kaggle.com/datasets/veeralakrishna/butterfly-dataset) 
# Model
This repository explores the task of image segmentation using SAM by finetuning it on butterfly dataset.
- <b>SAM:</b>
  <br>
![image](https://github.com/anishka25/butterflysam/assets/115390390/12ca83e3-150e-491e-8e57-d1809245f558)

- <b>NTXENT Loss:</b>

![image](https://github.com/anishka25/butterflysam/assets/115390390/811e2371-adcb-432b-9a99-4ab2346e99a6)

Dice loss is a metric used in image segmentation models. It measures the similarity between the predicted and actual segmentation masks by calculating the intersection over the union (IoU) of the two masks. The Dice coefficient, derived from this loss, ranges from 0 (no overlap) to 1 (perfect overlap). This loss is particularly useful for tasks like object detection or medical image segmentation, where precise delineation of objects is crucial. It encourages the model to produce accurate, pixel-level segmentations by penalizing false positives and false negatives. Minimizing Dice loss leads to better segmentation results in tasks like identifying objects in images.

# Results
![image](https://github.com/anishka25/butterflysam/assets/115390390/dae7f29f-abf3-46d3-ba3b-98aa3bbaff2c)
![image](https://github.com/anishka25/butterflysam/assets/115390390/f510f96a-08dc-4e9b-93f7-0f6fe7dcc749)


