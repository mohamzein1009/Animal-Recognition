In this project I try my hands at computer vision using CNNs and also pre-trained models to see whether I can build a CNN that can correctly categorise images of different animals. Some of the pre-trained models I will experiment with are VGG16, ResNet50 and ResNet152. The pre-trained models were supplemented using some Conv2D, MaxPool and Dense layers in order to create a fully functioning CNN.

From my testing, the VGG16 model resulted in the best accuracy and some of the other factors that affected accuracy were the resolutions the images were set to, with higher resolutions returning scores but it would also require longer runtimes but since the scores were relatively high I chose to stick to lower resoultions.

Data: https://www.kaggle.com/datasets/19fb7b4297de20a310201b935ec720cd98384623cea18e985ee403ab711b99ed
