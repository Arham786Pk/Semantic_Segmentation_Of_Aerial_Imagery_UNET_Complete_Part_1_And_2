🚀 Part 2: Model Building & Training – Satellite Imagery Semantic Segmentation
Welcome to Part 2 of our workshop series on Satellite Imagery Semantic Segmentation.
In this phase, we move beyond data preparation and focus on building, training, and saving a deep learning model using the U-Net architecture.

📌 What’s Included in This Notebook
✅ U-Net Model Architecture
A Keras-based custom implementation of U-Net designed for semantic segmentation on satellite imagery. The model supports multi-class outputs with efficient skip connections and convolutional blocks.

✅ Custom Metric: Intersection over Union (IoU)
Implemented a Jaccard Index (IoU) function to evaluate how well the predicted segmentation maps match the ground truth.

✅ Loss Functions
We used a combination of:

Dice Loss: To focus on class imbalance

Categorical Focal Loss: To emphasize harder examples

✅ Model Compilation
The model was compiled with:

Optimizer: Adam

Loss: Dice Loss + Categorical Focal Loss

Metrics: Accuracy, IoU

✅ Training
Trained on 256×256 image patches from Part 1

Epochs: 30

Batch Size: 8

No data shuffling to maintain patch order

✅ Model Saving
The final model is saved as:
Semantic_Segmentation_Of_Aerial_Imagery_UNET.h5

🔗 Prerequisite
Make sure you’ve completed Part 1: Data Preparation before running this notebook.
