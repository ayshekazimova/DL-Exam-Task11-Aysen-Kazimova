# Task 11 – SVHN Classification using CNN

**Student:** Kazımova Ayşən Əli  
**Task:** 11  
**Dataset:** SVHN (Street View House Numbers)  
**Random Seed:** 20240211  

---

## 📽️ Presentation Slide Link
👉 **Slide Presentation:**  
🔗 _(https://docs.google.com/presentation/d/1UmBMnNVEF9qkYgy8i8FH0Ywz7dpuPbcve-RCb9SPsM0/edit?usp=sharing)_

---

## 1. Introduction
This project focuses on digit classification using the SVHN (Street View House Numbers) dataset.
A Convolutional Neural Network (CNN) model was implemented and trained using two different
training strategies to evaluate the effect of data augmentation.

---

## 2. Dataset
SVHN is a real-world image dataset containing RGB images of digits (0–9) captured from
street view house numbers.

- Image size: 32 × 32
- Channels: RGB (3 channels)
- Classes: 10 (digits 0–9)

---

## 3. Model Architecture
The CNN architecture used in this project consists of:

- Two convolutional layers
- ReLU activation functions
- Max pooling layers
- Fully connected layers
- Dropout (0.5) to reduce overfitting

---

## 4. Training Strategy
Two different training versions were applied:

### Version 1 – No Augmentation
- Original SVHN images
- Only normalization applied

### Version 2 – With Data Augmentation
- Random rotation
- Random translation
- Normalization

To ensure reproducibility, a fixed random seed (**20240211**) was used.

---

## 5. Evaluation & Results
The following evaluations were performed:

- Training accuracy comparison between both versions
- Confusion matrix for the best-performing model
- Sample predictions from the test dataset

The augmented model demonstrated better generalization performance.

---

## 6. Generated Output Files
After executing the Colab notebook, the following files are generated:

- `training.png` – Training accuracy comparison  
- `confusion.png` – Confusion matrix of the best model  
- `predictions.png` – Sample predictions visualization  

---

## 7. Conclusion
Data augmentation significantly improves the robustness and performance of the CNN model
on the SVHN dataset. The results confirm that augmentation helps the model generalize better
to unseen data.

---

**Task 11 – SVHN successfully completed.**


