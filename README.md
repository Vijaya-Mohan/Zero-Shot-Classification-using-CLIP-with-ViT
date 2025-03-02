# 🦜 Zero-Shot Bird Classification using CLIP with Vision Transformer

## Overview
This project explores the use of Zero-Shot Learning for fine-grained bird species classification. It leverages CLIP (Contrastive Language-Image Pre-training) along with Vision Transformer (ViT) architectures to classify bird species without requiring a direct training dataset for each class. While performing the zero-shot using the CLIP model will associate with the descriptions that we are giving for the images contribute more. Instead of giving a text prompt for the images as its class name here I tried to use more detailed description for the two hundred distinctive classes which in turn increased the efficient in predictions.The approach is enhanced by incorporating detailed textual descriptions of bird species, boosting classification accuracy.

## Enhanced text descriptions, rather than simple class names, are employed to improve classification accuracy.

### Dataset Used Using the CUB-200-2011 Dataset:

The dataset used for training the model is the  CUB-200-2011 Dataset. https://www.vision.caltech.edu/datasets/cub_200_2011/ 
- Please cite it as follows:

- @techreport{WahCUB_200_2011,
- Title = ,
- Author = {Wah, C. and Branson, S. and Welinder, P. and Perona, P. and Belongie, S.},
- Year = {2011}
- Institution = {California Institute of Technology},
- Number = {CNS-TR-2011-001}
}

- Contains 11,788 images across 200 bird species.
- Includes fine-grained attributes such as feather color, beak shape, and habitat.
- Used as a benchmark dataset for zero-shot learning and fine-grained classification.
- Download directly from the website too : https://data.caltech.edu/records/65de6-vp158 

## 🚀 Research Highlights
### Enhanced Text Descriptions
- Instead of simple class names, detailed semantic descriptions of bird species are utilized, resulting in a **higher accuracy improvement**.

### ViT Model Comparisons
- **ViT-B/32**: Achieves **49% accuracy**.
- **ViT-B/16**: Achieves **56% accuracy**.
- **ViT-L/14**: Best performer, achieving **64% accuracy**
- By capturing intricate features such as feather textures and beak shapes.
- **ViT-L/14 Outperforms**: The larger ViT model demonstrated better generalization capabilities, surpassing other models in recognizing subtle and detailed bird features.

### Available Models
- **ViT-B/32**
- **ViT-B/16**
- **ViT-L/14 (Best performance)**

## 🌍 Why It Matters
- **Advances AI for Wildlife Conservation**: This work can aid in species identification and ecological research, supporting biodiversity conservation efforts.
- **Zero-Shot Learning**: Demonstrates how using rich textual descriptions of species can significantly improve classification models without the need for extensive labeled image data.
- **Bridges Computer Vision and Natural Sciences**: Provides a unique intersection of machine learning and biology, enhancing the potential of AI for scientific discovery.

## 🔮 Future Work
- **Improving Textual Descriptions**: Further experiments with prompt engineering to refine how textual descriptions can aid in classification.
- **Expanding Datasets**: Exploring other datasets beyond CUB-200 for broader species classification applications.
- **Addressing Ethical Concerns**: Exploring ways to handle dataset bias, fairness, and the responsible use of AI in conservation research.

## 🤝 Let's Connect!
If you're interested in AI for biodiversity, zero-shot learning, or vision transformers, feel free to **star this repository** and collaborate! Reach out via **GitHub or LinkedIn**.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

