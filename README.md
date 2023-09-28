# NutriVision
NutriVision is Fruits and Vegetables classification project aimed to produce nutritive information about an input image of fruit or vegetable.

## Overview
This repository contains the code and resources for a deep learning project focused on fruit and vegetable classification. The project aims to accurately classify various types of fruits and vegetables from images using ResNet.

## Project Structure

- dataset
  - train
    - class1
      - image1.jpg
      - image2.jpg
      ...
    - class2
      - image1.jpg
      - image2.jpg
      ...
  ...
  - test
    - class1
      - image1.jpg
      - image2.jpg
      ...
    - class2
      - image1.jpg
      - image2.jpg
      ...
  ...
  - nutrition.csv
- classifier.ipynb
- model
  - best_model.h5
- test1.jpg
- test2.jpg
- test3.jpg
- test4.jpg


## Getting Started
1. Clone the repository: `git clone https://github.com/ABHISHEKSUBHASHSWAMI/NutriVision.git`
2. Set up a Python environment (preferably a virtual environment).
3. Explore the Jupyter notebook for step-by-step guidance on data preprocessing, model training, and evaluation.

## Dataset
The dataset used in this project consists of over 45,000 images encompassing 77 different classes of fruits and vegetables, carefully curated to ensure diversity in types, sizes, shapes, and colors.

[Download Dataset](https://www.kaggle.com/datasets/abhisheksubhashswami/fruits-and-vegetables)

## Model Architecture
We experimented with various CNN-based architectures, with a focus on ResNet101. Transfer learning was employed to leverage pre-trained weights, and the model was optimized for accuracy and efficiency.

## Evaluation
Model performance was evaluated using metrics such as accuracy, precision, recall, and F1-score. The model's predictions were compared with ground truth labels to assess its effectiveness.

## Future Improvements
- Implement additional advanced architectures and ensemble methods to further improve model performance.
- Explore real-time applications and deployment of the model for practical use cases.
- Conduct further research to enhance recognition accuracy, especially for challenging cases.

## Contributors
- [S ABHISHEK](https://gihub.com/ABHISHEKSUBHASHSWAMI)

Feel free to contribute, open issues, or provide feedback on this project. Happy coding!
