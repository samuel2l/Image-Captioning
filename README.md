# Image Captioning with Deep Learning

## Project Description
This project implements an Image Captioning system using a Convolutional Neural Network (CNN) for feature extraction and a Recurrent Neural Network (RNN) for generating textual descriptions of images. The model is trained on the Flickr8k dataset, a standard dataset for image captioning tasks.

---

## Dataset
This project uses the Flickr8k dataset, which includes 8,000 images and corresponding captions. You can download the dataset and the captions file using the following links:

- [Flickr8k Dataset](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip)
- [Flickr8k Captions](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip)

---
## Implementation
- To implement simply install the required libraries and change the path when calling the load_captions_data function to the path to your downloaded Flickr8k_text/Flickr8k.token.txt

## Features
- Preprocessing of image data using CNNs.
- Tokenization and embedding of captions.
- Integration of CNN and RNN for caption generation.
- BLEU score evaluation.

---

## Results
The model generates captions for input images and achieves competitive performance evaluated using BLEU scores.

---

## Acknowledgments

- Taught by [Flickr8k Captions](https://x.com/A_K_Nain).



