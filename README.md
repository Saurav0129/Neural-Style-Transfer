# 🎨 Neural Style Transfer 

This project implements Neural Style Transfer using a pre-trained **VGG19** model in TensorFlow/Keras. It blends the **content of one image** with the **style of another**, producing a visually stylized output that mimics artistic textures and patterns.

---

## 🧠 Features

- Uses pre-trained **VGG19** for feature extraction.
- Combines **content loss**, **style loss**, and **total variation loss** for optimization.
- Customizable parameters (iterations, loss weights, etc.).
- Displays **original**, **style**, and **stylized output** side-by-side.
- Efficient optimization using **SGD** with exponential decay.

---

## 📁 Input

- **Content Image**: The image whose structure/content will be preserved.
- **Style Image**: The image whose artistic style will be applied.

---

## 🖼️ Output

- A stylized image that merges the content and style.
- Output saved as:  

---


## 🖌️ Example

### Example-1 
![Example-1](./resources/Output/Generated%20Image-1.png)

### Example-2 
![Example-2](./resources/Output/Generated%20Image-2.png)

---

## 🚀 Getting Started

```python
Run_StyleTransfer(
  base_image_path="path/to/content.jpg",
  style_image_path="path/to/style.jpg",
  result_prefix="output",
  iterations=1000
)


