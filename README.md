This project aims to address an issue found within the ImageNet dataset: a lack of distinction between animal species.
In ImageNet-1k, a subset of the full ImageNet dataset, the classes are broad when referring to types of animals. 
For example, 62% of the “jay” class of images in ImageNet-1k are of the blue jay, even though there are 49 species
of Jay found around the world [1]. 

To address this issue, 1000 images of ten breeds of duck (100 each) will be compiled, and an SOTA model will be trained and tested with this novel dataset.
The ten breeds of duck that will be used in this project are Mallard, Muscovy, Blue Swedish, Black East Indian, Hooded Merganser, Magpie, Orpington, Pekin, Welsh Harlequin, and Wood.
The EfficientNetB0 model is being used in this project due to this architecture being able to balance accuracy and efficiency. This model can also extract detailed and high-level features, making it ideal for subtle differences in the duck breeds [2].
The EfficientNetB0 model used is a Keras model specifically built for image classification [3].

* [1] A. S. Luccioni and D. Rolnick, “Bugs in the Data: How ImageNet Misrepresents Biodiversity,” arXiv preprint arXiv:2208.11695, 2022.
* [2] “EfficientNet Architecture,” GeeksforGeeks, Computer Vision section. [Online]. Available: https://www.geeksforgeeks.org/computer-vision/efficientnet-architecture/#.
* [3] TensorFlow, “tf.keras.applications.EfficientNetB0,” TensorFlow documentation. [Online]. Available:https://www.tensorflow.org/api_docs/python/tf/keras/applications/EfficientNetB0.

