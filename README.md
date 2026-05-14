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


## Task 7: Business Use Case Mapping

### Use Case: Manufacturing Industry (Quality Inspection)

This computer vision model can be used in manufacturing industries to automatically detect defects in products.

For example:
- Detect scratches, dents, or stains on metal surfaces
- Identify defective products during production
- Separate damaged items from normal ones

### Benefits:

- Reduces manual inspection effort
- Increases accuracy and consistency
- Saves time and cost
- Improves product quality

### Real-world Example:

In industries like automobile manufacturing or electronics, this model can be used to inspect product surfaces and ensure only high-quality items are delivered to customers.
