# Skin-disease-Prediction-Using-Deep-learning
"Deep learning project for skin disease classification using DermNet dataset. Implemented EfficientNetV2, ConvNeXt, and Vision Transformer with pre processing, augmentation, class weighting, and Grad-CAM for explainable AI in clinical decision support. Multiple experiments were carried out across different class subset configurations (4, 6, 8, and 12 classes) to comprehensively evaluate the effect of dataset complexity, class imbalance, and inter-class similarity on model performance. These experimental results influenced the decision to use a refined 6-class subset that achieved the optimum balance between clinical relevance, interpretability, and robustness."

# Features
- Data Preprocessing & augmentation for robust model training  
- Class imbalance handling using weighted loss
- Implemented EfficientNetV2B0, ConvNeXtTiny, and Vision Transformer (ViT).
- Performance evaluation using accuracy, precision, recall, F1-score, and confusion matrices  
- **Explainable AI** with Grad-CAM heatmaps
  
- # Dataset
- **DermNet** dataset (Kaggle) containing dermatological images across multiple skin disease categories.  
- Preprocessed to handle class imbalance, noise, and visual similarity.
  
# Results
- Highest accuracy: Vision Transformer (73%)
- Supports 6-class classification
  
