#  NeuralArt — AI Neural Style Transfer

Transform ordinary photographs into artistic images using deep learning and **Adaptive Instance Normalization (AdaIN)**.

<p align="center">
  <img width="1353" height="620" alt="image" src="https://github.com/user-attachments/assets/3e972cd3-2e1b-4ab5-a22f-b825a11f2fd7" />
</p>

---

##  About the Project

**NeuralArt** is a deep learning web application that combines the content of one image with the artistic style of another using **Adaptive Instance Normalization (AdaIN)**.

The project uses a pretrained VGG encoder and a trained decoder to generate stylized images while preserving the content of the original photograph.

##  Style Transfer Example

<p align="center">
  <img width="100%" alt="NeuralArt Style Transfer Example" src="https://github.com/user-attachments/assets/bdc921aa-74c1-4521-8d68-fdefa851c594" />
</p>

##  Features

-  **Artistic Style Transfer** — Transform photographs using artistic styles.
-  **Image Upload** — Upload a content image and a style reference image.
-  **Deep Learning Model** — Generate stylized images using AdaIN and the trained decoder.
-  **Style Strength Control** — Adjust the influence of the selected artistic style.
-  **Web Interface** — Use the application through a Flask-based interface.

##  Tech Stack

- **Programming Language:** Python
- **Deep Learning Framework:** PyTorch
- **Style Transfer Method:** Adaptive Instance Normalization (AdaIN)
- **Encoder:** Pretrained VGG encoder
- **Decoder:** Trained decoder
- **Backend:** Flask
- **Frontend:** HTML and CSS

##  Model Architecture & Training

NeuralArt uses **Adaptive Instance Normalization (AdaIN)** to combine the content features of an image with the style features of a reference image.

- **Encoder:** Pretrained VGG encoder for extracting image features.
- **Decoder:** Trained to reconstruct stylized images from AdaIN-transformed features.
- **Content Dataset:** COCO2017.
- **Style Dataset:** Painter by Numbers.
- **Training Duration:** 260 epochs across two training stages.

The VGG encoder uses pretrained weights, while the decoder was trained for this project.

**Trained decoder weights:** `experiment/final_exp/decoder_final.pth`
