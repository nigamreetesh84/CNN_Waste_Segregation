# **Waste Classification with CNN**

This project uses a Convolutional Neural Network (CNN) to classify waste into different categories using image data. The model is implemented in TensorFlow/Keras and trained on labeled image datasets.

---

##  **Waste Material Segregation for Improving Waste Management**

###  Problem Statement

Improper waste disposal leads to environmental degradation, increased landfill waste, and inefficient recycling. Manual sorting is labor-intensive, error-prone, and costly. This project aims to address these challenges by developing an **AI-powered waste classification system** to streamline segregation, reduce operational costs, and improve recycling rates.

###  Objective

The objective is to implement an efficient and scalable waste segregation system using CNNs that can:

* Accurately classify waste materials (e.g., cardboard, glass, paper, plastic).
* Enhance recycling efficiency and reduce landfill waste.
* Support sustainable practices by optimizing waste sorting.

### Key Business Benefits

* Automated waste sorting reduces labor and time.
* Improved recycling rates through precise classification.
* Scalable solution for smart waste management.

### Use Cases

* **Smart Recycling Bins**: Real-time waste identification and sorting.
* **Automated Waste Sorting Facilities**: Industrial-scale AI-driven segregation.
* **Waste Monitoring and Reporting**: Data-driven insights for sustainability.

---

## Files

* `CNN_Waste_Segregation_ReeteshNigam.ipynb`: Jupyter Notebook containing model definition, training, evaluation, and visualization steps.

---

## Model Architecture

### Model Summary

* CNN with multiple `Conv2D` + `MaxPooling2D` layers
* Regularization using `BatchNormalization` and `Dropout`
* Final classification layer with `softmax` activation

---

## Training Details

* **Optimizer**: Adam
* **Loss Function**: Categorical Crossentropy
* **Metrics**: Accuracy
* **Validation**: Includes split and visualizations of `val_loss` and `val_accuracy`

---

## Visualization

* Includes training and validation accuracy/loss plots
* Helps analyze model learning behavior across epochs

---

## Requirements

* Python 3.8+
* numpy version: 2.1.3
* pandas version: 2.2.3
* seaborn version: 0.13.2
* matplotlib version: 3.10.1
* PIL (Pillow) version: 11.2.1
* tensorflow version: 2.19.0
* keras version: 3.9.2
* sklearn version: 1.6.1

---

## Contact

Created by [Reetesh Nigam](https://github.com/nigamreetesh84)

