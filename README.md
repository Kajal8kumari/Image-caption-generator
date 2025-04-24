🖼️ Image Caption Generator using CNN & LSTM
This project implements an Image Caption Generator using deep learning techniques. It combines Convolutional Neural Networks (CNNs) for image feature extraction and Long Short-Term Memory (LSTM) networks for generating meaningful captions based on the extracted image features.

📌 Features
Extract image features using the Xception model (pre-trained on ImageNet)
Generate captions using an LSTM-based decoder
Trained on the Flickr8k dataset with 8000+ images and captions
Tokenizer and padding for handling textual input
Caption generation using greedy search
Visualization of image with generated captions

🧠 Model Architecture
Encoder: Xception CNN to extract image embeddings
Decoder: LSTM network trained on sequences of words to predict the next word
Combines image features with text embeddings to generate complete sentences

🛠️ Technologies Used
Python
TensorFlow / Keras
NumPy, Matplotlib

PIL (Python Imaging Library)

📂 Dataset
Flickr8k Dataset: A collection of 8000 images each with five different captions.

dataset:
[dataset(images)](https://drive.google.com/drive/folders/1WnOtltAkIOHzr02n2SSOZROU25s_01b5?usp=sharing)
[dataset(text)](https://drive.google.com/drive/folders/1Y8e_OwO8NF0V-xqUksr6KNrWH7xHztvK?usp=sharing)



AUTHOR :
KAJAL KUMARI : [Kajal8kumari](https://github.com/Kajal8kumari)

CO AUTHORS : [Contributors](https://github.com/Kajal8kumari/Image-caption-generator/blob/main/CONTRIBUTORS.md)

