# Artistic-Neural-Style-Transfer


This project demonstrates the **Neural Style Transfer** technique, enabling the transformation of a **content image** by applying the **style** of another image to create a unique, artistic result.

## Project Overview
The model utilizes a pre-trained **VGG19 network** to extract feature representations from a content image and a style image. These features are then combined to produce a novel image that retains the content structure but adopts the style attributes.

## Features
- **Content and Style Merging**: Creates a blended image that captures content while adopting a distinct style.
- **Customizable Weighting**: Users can adjust the weights for content and style loss to achieve varied effects.
- **Layered Style Representation**: Leverages multiple VGG19 layers to capture complex style details.

## Requirements
- **Python 3.x**
- **TensorFlow**
- **Matplotlib**
- **Pillow**

Install dependencies using:
```bash
pip install tensorflow matplotlib pillow
