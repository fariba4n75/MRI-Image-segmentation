# Notebooks

This folder contains all the Jupyter notebooks used for training, testing, and evaluating the models in this project. 

### Included Models:
- **U-Net**
- **Attention U-Net**
- **Swin Transformer** (pretrained and non-pretrained)
- **Swin Transformer with BCE and Focal Loss**

Each notebook includes:
- Data loading and preprocessing
- Model architecture and training
- Model evaluation with Dice and IoU metrics
- Sample predictions

💡 **Important:**  
The notebooks are configured to load the dataset from Google Drive.  
Before running the notebooks, you must:
1. Upload the preprocessed dataset (TIFF slices) to your own Google Drive.
2. Update the notebook paths to point to your Drive folder.

This ensures that the notebooks run correctly with your dataset.
