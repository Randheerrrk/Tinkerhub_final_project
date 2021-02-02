# COVID-19 Pnuemonia Detection
The whole world is under the massive threat of the corona-virus. Each day thousands of new cases are reporting. Its found that the majority of COVID-19 patients suffer pneumonia. So I created a model that can predict COVID-19 related pneumonia using the chest X-Ray image. 
As I said this is an image-classification model. Since there is no large amount of X-ray scan related to COVID-19, I will be using the transfer learning Inception-V3 pre-trained model.

# Dataset
The CT scan images and X-ray images of COVID-19 patients can be downloaded from [this](https://github.com/ieee8023/covid-chestxray-dataset) repository. These are images from various sources. Also it contains both CT-scan images and X-ray images. The [chest-xray-pneumonia](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) from Kaggle is also used.

# Model
We used VGG16 pretrained model with a custom fully connected layers at the end of the network.
