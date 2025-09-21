# Data

This repository does not contain the dataset directly because of GitHub’s file size limits.

# 📂 Dataset

The dataset used in this project is based on the ISBI 2015 Longitudinal MS Lesion Segmentation Challenge dataset.
Since the original dataset is provided in NIfTI format (.nii), I have preprocessed it and converted it into TIFF slices for easier use in this project.

Training and test data should be placed inside the data/ folder.

Each patient folder contains both the MRI slices and their corresponding mask images.

# Example structure:

data/
 ├── training1/
 │    ├── training01_01_flair_pp_slice_59.tiff
 │    ├── training01_01_flair_pp_slice_59+mask.tiff
 │    └── ...
 ├── training2/
 │    ├── training02_01_flair_pp_slice_152.tiff
 │    ├── training02_01_flair_pp_slice_152+mask.tiff
 │    └── ...

# 📥 Download

The preprocessed dataset (converted to .tiff) can be downloaded from the following Google Drive link:

👉 [Download dataset from Google Drive](https://drive.google.com/file/d/1nU0W_ECfo3kglk-PhowbQFVefncIOACb/view?usp=drive_link)


The preprocessed dataset (converted to .tiff) can be downloaded from the following Google Drive link:

👉 Download Dataset from Google Drive
