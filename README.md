# Glaucoma Detection Using ResNet-50

This project implements a deep learning pipeline to detect glaucoma from retinal fundus images using the ResNet-50 architecture.

## What We Did

- Used a **pretrained ResNet-50** model fine-tuned on retinal fundus images to classify whether glaucoma is present or not.
- Processed and prepared retinal fundus image data for model training and evaluation.
- Applied **Grad-CAM** (Gradient-weighted Class Activation Mapping) to generate heatmaps that visually explain the regions in the images most relevant to the model’s decision.
- Developed an automated **HTML report generator** that outputs patient-specific reports, including diagnosis, confidence scores, and Grad-CAM visualizations.
- Emphasized explainability and interpretability to support clinical decision-making alongside AI predictions.

This approach aims to assist ophthalmologists by providing accurate, interpretable glaucoma detection from fundus images.

