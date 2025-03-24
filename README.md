# Banknote Classification Model

This repository contains a machine learning model for classifying banknotes using image data.

## Folder Structure
```
├───testing-data
└───training-data
    ├───inr10
    └───inr100
```
- `training-data/inr10`: Contains training images for INR 10 banknotes.
- `training-data/inr100`: Contains training images for INR 100 banknotes.
- `testing-data`: Contains test images to evaluate the model.

## Requirements
Before running the notebook, install the necessary dependencies:
```sh
pip install tensorflow numpy pandas matplotlib opencv-python
```

## Running the Program
1. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
2. Load the `Test image banknote.ipynb` file.
3. Run each cell sequentially to:
   - Load training and testing data.
   - Train the model.
   - Evaluate the model on test data.
   - Predict the banknote denomination.

## Expected Output
The program should output classification results indicating whether the given banknote belongs to the INR 10 or INR 100 category.
