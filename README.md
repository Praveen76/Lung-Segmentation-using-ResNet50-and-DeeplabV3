# Lung Segmentation using ResNet50 and DeepLabV3

## Introduction:

Semantic segmentation is a computer vision task aimed at dividing an image into distinct regions, with each region labeled according to its semantic category. The goal is to enable machines to comprehend the content of an image at the pixel level, assigning a label to each pixel based on the object or region it represents.

This technique finds extensive applications in various domains such as self-driving cars, medical image analysis, and robotics object recognition. Semantic segmentation provides a detailed understanding of image content, allowing for more precise and accurate applications.

### Dataset:

- The Chest X-Ray dataset comprises images and segmented masks from two different sources: Shenzhen and Montgomery datasets.
- The `CXR_png` folder contains Chest X-Rays, and the `masks` folder includes the segmented masks.
- There are 704 images, each mapped with its corresponding mask.

### Problem Statement:

Perform lung segmentation on the Chest X-Ray dataset using the DeepLabV3+ model.

### Learning Objectives:

Upon completing this project, you will achieve the following learning objectives:

1. **Understand, Prepare, and Visualize Dataset:**
    - Gain proficiency in understanding, preparing, and visualizing a dataset containing images and their corresponding masked images used for segmentation.

2. **Implement DeepLabV3+ Architecture:**
    - Learn to implement the DeepLabV3+ architecture for semantic segmentation tasks.

3. **Create Masked Image (Prediction):**
    - Develop skills to generate a masked image using the trained model for lung segmentation.

## Files Contained in the Project:

- **`Lungs_Segmentation_using_ResNet_and_DeepLabV3.ipynb`**: Jupyter notebook containing the project implementation and experimentation.

## Usage:

1. Clone the repository:

```bash
git clone https://github.com/Praveen76/Lung-Segmentation-using-ResNet50-and-DeeplabV3.git
cd Lung-Segmentation-using-ResNet50-and-DeeplabV3
```

2. Open and explore the Jupyter notebook `Lungs_Segmentation_using_ResNet_and_DeepLabV3.ipynb` to understand the project implementation.

3. Execute the code cells within the notebook to experiment with lung segmentation using ResNet50 and DeepLabV3.

4. Visualize the results and interpretations.

Feel free to contribute, report issues, or suggest improvements!

