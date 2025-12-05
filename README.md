# PCA Assignment Data (EAAI 2026)

This repository contains the dataset used for the **EAAI 2026 PCA Assignment**.  
It provides a lightweight, preprocessed subset of the *Animal Faces* dataset for use in teaching dimensionality reduction techniques such as **Principal Component Analysis (PCA)** and **autoencoders**.


## Repository Contents

```
├── animal_faces.pkl # Preprocessed image dataset for the assignment
├── README.md # This file
```


The file `animal_faces.pkl` includes grayscale, resized animal face images stored as NumPy arrays.  
These data are required for both the instructor and student versions of the PCA assignment.

## 

Clone or download the repository:

```bash
git clone https://github.com/kvarada/EAAI26-PCA-assignment-data.git
```

Then place `animal_faces.pkl` in the expected directories of the assignment repository:

```bash
solutions/data/animal_faces.pkl
student/data/animal_faces.pkl
```
