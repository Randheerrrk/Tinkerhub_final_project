# COVID-19 Pnuemonia Detection
The whole world is under the massive threat of the corona-virus. Each day thousands of new cases are reporting. Its found that the majority of COVID-19 patients suffer pneumonia. So I created a model that can predict COVID-19 related pneumonia using the chest X-Ray image. 
As I said this is an image-classification model. Since there is no large amount of X-ray scan related to COVID-19, I will be using the transfer learning Inception-V3 pre-trained model.

# Dataset
The CT scan images and X-ray images of COVID-19 patients can be downloaded from [this](https://github.com/ieee8023/covid-chestxray-dataset) repository. These are images from various sources. Also it contains both CT-scan images and X-ray images.

# Model
I'm planning to train the pre-trained Inception model with transfer learning. Inception is a huge scale image recognition system. It has one of the best feature representations, which helps it to classify up to 1000 object-based categories. It is a 48 layer network with an input size of 299x299. 
