## Task 1: Problem Identification

The dataset corresponds to an Image Classification problem.

Each image is labeled as one of four classes: normal, scratch, dent, or stain. The objective is to train a model that can correctly classify an input image into one of these categories based on visual features.

Unlike object detection or segmentation tasks, this problem does not involve identifying object locations or performing pixel-wise classification. Instead, each image is assigned a single label, making image classification the most suitable approach.


## Task 6: CNN Concept Explanation

### 1. What is Convolution?

Convolution is a process where a small filter (kernel) moves over an image to detect important features such as edges, textures, or patterns.  
It helps the model understand spatial information in images.

---

### 2. Why is Pooling used?

Pooling is used to reduce the size of feature maps.  
It helps in:
- Reducing computation
- Removing unnecessary details
- Preventing overfitting

Common type: Max Pooling (takes maximum value)

---

### 3. Why is ReLU commonly used in CNNs?

ReLU (Rectified Linear Unit) replaces negative values with zero.  

It is used because:
- It makes training faster
- It avoids vanishing gradient problem
- It introduces non-linearity

---

### 4. Why are CNNs better than regular feed-forward networks for images?

CNNs are better because:
- They capture spatial relationships in images
- They use fewer parameters (efficient)
- They automatically detect features (no manual feature extraction needed)

In contrast, regular neural networks treat images as flat data and lose spatial structure.
