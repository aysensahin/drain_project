# Automated blood volume estimation in surgical drains for clinical decision support
Context: [`Automated blood volume estimation in surgical drains for clinical decision support`](https://www.europeanreview.org/article/36375)

For our study, in which we aimed to efficiently separate the blood-filled section of the drain from the surrounding area of the image and calculate the blood volume, our technique uses semantic segmentation on mobile phone photos. After that, these outcomes are delivered to online and mobile applications for easy access. 

We trained a pretrained model with our own dataset. The dataset consists of 1004 photos of Jackson Pratt and Hemovac drains, which contains different volumes of blood. 

Model training notebook includes the semantic segmentation operations.

Additional details on the dataset are available [here](https://www.kaggle.com/datasets/ayenahin/liquid-volume-detection-from-drain-images).
