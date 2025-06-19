#  LSTM-Based MNIST Digit Classification



##  Overview

This notebook presents a deep learning assignment for building and evaluating LSTM-based models to classify handwritten digits from the MNIST dataset. The main objective is to treat each MNIST image (28×28 pixels) as a sequence of 28 time steps with 28 features and train a model using LSTM layers.

---

##  Assignment Instructions

### Task

* Train an LSTM model to classify MNIST digits.
* Input each image as a sequence of 28 rows (each row = one time step of 28 values).
* Train on 80% of the training set and validate on the remaining 20%.
* Use test data **only** after the model is fully trained.

### Model Requirements

* Use **32 LSTM units** with **15% recurrent dropout**.
* Use **Categorical Cross Entropy** as the loss function.
* Use **Adam** optimizer and **accuracy** as the metric.

### Additional Experiments

* Add a **second LSTM layer** before the Dense layer(s).
* Vary the number of LSTM units to **48**, **96**, and **256**, and analyze the accuracy curves.

---

##  Requirements

* Python ≥ 3.7
* TensorFlow ≥ 2.x
* NumPy
* Matplotlib
* scikit-learn

You can install dependencies using:

```bash
pip install -r requirements.txt
```

(You may export the exact environment using `pip freeze > requirements.txt`.)

---

##  How to Run

1. Open the notebook:

   ```
   Copy_of_dl_lab5_Reham_Elkasaby.ipynb
   ```
2. Run all cells in sequence using Jupyter Notebook or Google Colab.
3. Observe training and validation accuracy, loss curves, and final test evaluation.

---

##  Results

The notebook includes training curves and evaluation metrics for:

* Single-layer LSTM (32 units)
* Two-layer LSTM
* Varying LSTM sizes (48, 96, 256)

Accuracy trends and model behaviors are discussed within the notebook output cells.

---

##  Dataset

* The MNIST dataset is loaded directly via `tensorflow.keras.datasets`.
* No manual dataset download is required.

---

## 👩‍💻 Author

**Reham Elkasaby**
ITI AI-Pro – Intake 45

---

