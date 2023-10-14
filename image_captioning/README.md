# Image Captioning

This project aims to develop an image captioning model using neural networks. Our approach utilizes DenseNet for feature extraction, over the original CNN model employed in "Show and Tell" work. Through experimentation, we determined that DenseNet provided superior qualitative results compared to CNN and VGG architectures. Additionally, to enhance the model's performance, we introduced modifications to the original architecture. Specifically, we incorporated image feature embeddings into the LSTM output, followed by passing them through fully connected layers. This adaptation led to an improvement in the BLEU score, indicating a stronger correlation between the image and the generated captions


Dataset Flicker8k available at this link:

https://drive.google.com/drive/folders/1nIj_MDozaZZr8S8yOPxFpWb13nFYMlnx?usp=sharing

(Access: SJSU)
