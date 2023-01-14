# Birds-450-species-image-classification

This project is an image classification project using a deep-learning network and using a transfer learning approach with MobileNetV2 architecture provided by Keras.  

The main approach during this project was to use gradual transfer learning where for each training of the 3 phases we defined, we fine-tuned the model by incrementally unfreezing a certain number of layers. The project has 2 versions with small variation in the network architecture with both having a test accuracy **>95%**.

The dataset comprise images of 450 bird species. 70,626 training images, 22500 test images(5 images per species) and 2250 validation images(5 images per species. This is a very high quality dataset where there is only one bird in each image and the bird typically takes up at least 50% of the pixels in the image. As a result even a moderately complex model will achieve training and test accuracies in the mid 90% range.

* You can find a link to the dataset used in ths project [here](https://www.kaggle.com/datasets/gpiosenka/100-bird-species) .  
* You can find a link to the code output, including history logs and model weights [here](https://drive.google.com/drive/folders/1gdLgZvIszPN666WwSr8uSkOTzgZF4Irm?usp=share_link) .
* [Kaggle version](https://github.com/mohamedamine99/Birds-450-species-image-classification/blob/main/bird-species-image-classification%20(3).ipynb)
* [Colab version](https://github.com/mohamedamine99/Birds-450-species-image-classification/blob/main/bird_species_image_classification%20Colab.ipynb)
