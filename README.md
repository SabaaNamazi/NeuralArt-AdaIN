#  NeuralArt — AI Neural Style Transfer

Transform ordinary photographs into artistic images using deep learning and **Adaptive Instance Normalization (AdaIN)**.

<p align="center">
  <img width="100%" alt="NeuralArt Application Interface" src="https://github.com/user-attachments/assets/66c8d3a0-0770-42cc-8089-bf4bdc5d3e50" />
</p>

---

##  About the Project

**NeuralArt** is a deep learning web application that combines the content of one image with the artistic style of another using **Adaptive Instance Normalization (AdaIN)**.

The project uses a pretrained VGG encoder and a trained decoder to generate stylized images while preserving the content of the original photograph.

##  Example

The application allows users to provide a content image and a style reference image to create an artistic transformation.

<p align="center">
  <img width="100%" alt="NeuralArt Style Transfer Example" src="https://github.com/user-attachments/assets/bdc921aa-74c1-4521-8d68-fdefa851c594" />
</p>

##  Features

- 🎨 **Artistic Style Transfer** — Transform photographs using different artistic styles.
- 🖼️ **Image Upload** — Upload a content image and a style reference image.
- 🧠 **Deep Learning Model** — Generate stylized images using the AdaIN architecture and trained decoder.
- ⚙️ **Adjustable Style Strength** — Control the influence of the selected artistic style, as supported by the interface.
- 🌐 **Web Interface** — Interact with the application through a Flask-based interface.

##  Tech Stack

- **Language:** Python
- **Deep Learning:** PyTorch
- **Model:** Adaptive Instance Normalization (AdaIN), VGG encoder, trained decoder
- **Backend:** Flask
- **Frontend:** HTML, CSS

##  Model Training

Style Transfer Method: Adaptive Instance Normalization (AdaIN)

Encoder: Pretrained VGG encoder

Decoder: Custom decoder trained from scratch for this project

Content Dataset: COCO2017

Style Dataset: Painter by Numbers

Training: 260 epochs across two training stages
