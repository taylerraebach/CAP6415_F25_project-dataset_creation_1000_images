This project aims to address an issue found within the ImageNet dataset: lack of distinction between animal species.
In ImageNet-1k, a subset of the full ImageNet dataset, the classes are broad when refering to types of animals. 
For example, 62% of the “jay” class of images in ImageNet-1k are of the blue jay, even though there are 49 species
of jay found around the world [1]. 

To address this issue, 1000 images of ten breeds of duck (100 each) will be compiled and a ViT model will be trained and tested with this novel dataset.
The four breeds of duck that will be used in this project are Mallard, Muscovy, Blue Swedish Black East Indian, Hooded Merganser, Magpie, Orpington, Pekin, Welsh Harlequin, and Wood.
A ViT model is being used in this project due to ViT models being able to capture both local and global features, which is beneficial when minute differences are key [2], like when comparing inter-species breeds.
The ViT model used is a Keras model specifically built for image classification [3].

* [1] A. S. Luccioni and D. Rolnick, “Bugs in the Data: How ImageNet Misrepresents Biodiversity,” arXiv preprint arXiv:2208.11695, 2022.
* [2] J. He, J.-N. Chen, S. Liu, A. Kortylewski, C. Yang, Y. Bai and C. Wang, “TransFG: A Transformer Architecture for Fine‑Grained Recognition,” arXiv preprint arXiv:2103.07976, Mar. 2021.
* [3] Keras Team, “ViTImageClassifier model – KerasHub API,” Keras, [Online]. Available: https://keras.io/keras_hub/api/models/vit/vit_image_classifier/.
