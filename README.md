# Grapevine_Leaves_Classification

![pic2](https://github.com/proshir/Grapevine_Leaves_Classification/assets/19504971/9dadea6a-8c58-4b7f-b3bf-4b67bd33d3e1)

This project focuses on classifying grapevine leaves into five distinct classes using advanced techniques like transfer learning and autoencoders. By harnessing pre-trained models, we aim to enhance classification accuracy while exploring the effects of dimensionality reduction and data augmentation through image generation. Our evaluation method employs 10-fold cross-validation for robust results.

## Libraries and Frameworks Used

- PIL: Python Imaging Library for image manipulation
- pandas: Data manipulation and analysis
- numpy: Numerical computing
- tensorflow: Deep learning framework
- matplotlib: Data visualization
- scikit-learn: Machine learning
- keras: Deep learning
- seaborn: Statistical data visualization

## Key Sections

Data Preparation: This section involves loading the grapevine leaves dataset, organizing the data, and creating a structured dataframe for analysis.

Data Augmentation: We employ various transformations to augment the images, diversifying the training data and improving model generalization.

Autoencoder Implementation: We construct an autoencoder model with multiple layers to perform dimensionality reduction.

Model Training: The pre-trained models (VGG19, ResNet50, EfficientNetB3) are trained using transfer learning techniques on the grapevine leaves dataset.

Model Evaluation: The trained models undergo rigorous evaluation through 10-fold cross-validation, and accuracy is the primary metric.

Results Analysis: Performance analysis includes the use of confusion matrices and visualizations to gain insights into model behavior.

Image Generation & Testing: Additional data samples are generated for further model testing.

## Model Accuracy

VGG19: 69%
ResNet50: 69%
EfficientNetB3: 76%
EfficientNetB3 after image generation: 92%

These findings showcase the significant performance boost achieved by implementing image generation techniques with EfficientNetB3, resulting in an impressive accuracy rate of 92%.
