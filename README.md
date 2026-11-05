# Handwritten Digit Recognition (MNIST)

Compares classical machine learning and neural networks for recognizing handwritten digits.

**Dataset:** MNIST (60,000 train / 10,000 test images, 28×28 grayscale)

## Results (test accuracy)
| Model | Accuracy |
|---|---|
| Logistic Regression | 92.6% |
| KNN | 97.1% |
| SVM | 97.9% |
| Neural network (ANN) | about 97.9% |
| CNN | about 99% training accuracy after 5 epochs |

## Approach
Load and normalize → train 5 model types → compare with classification reports and confusion matrices.

## Tech stack
Python · scikit-learn · TensorFlow / Keras · NumPy · Matplotlib

## Run it
```bash
pip install -r requirements.txt
jupyter notebook Handwritten_digit_recognition.ipynb
```

## Author
Faseeh · [LinkedIn](https://www.linkedin.com/in/faseeh-uddin-mohammed-a0455823b)
