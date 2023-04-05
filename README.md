# Semantic-Segmentation
Trained a semantic segmentation network that assigns each pixel of an input image to one of the k object classes. 

## Dataset Used:-  
Dataset: [CityScapes Dataset](https://www.cityscapes-dataset.com/) <br>
Description: <br>
large-scale dataset that contains a diverse set of stereo video sequences recorded in street scenes from 50 different cities, with high quality pixel-level annotations of 5 000 frames in addition to a larger set of 20 000 weakly annotated frames.<br>

License:<br>
This Cityscapes Dataset is made freely available to academic and non-academic entities for non-commercial purposes such as academic research, teaching, scientific publications, or personal experimentation. Permission is granted to use the data given that you agree to our license terms.<br>
![Screenshot 2023-04-05 at 1 20 50 PM](https://user-images.githubusercontent.com/34732790/230169953-2a421f2e-6c13-4962-ab9b-773a10596d08.png)

## Model Architecture:- <br>
Encoder(VGG16 Network):<br>
![Screenshot 2023-04-05 at 1 23 24 PM](https://user-images.githubusercontent.com/34732790/230170431-35e4320b-5760-4c0c-a7a7-f451ee0fdf78.png)


Decoder:<br>
![Screenshot 2023-04-05 at 1 31 02 PM](https://user-images.githubusercontent.com/34732790/230172643-5720732f-4dfb-4ac1-8511-22896259634f.png)
