# CIFAR-10 Image Classifier (PyTorch)

A convolutional neural network (CNN) built with PyTorch to classify images from the CIFAR-10 dataset into 10 categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## What this project does

- Loads and normalizes the CIFAR-10 dataset (60,000 32x32 color images)
- Defines a 3-block CNN (Conv → BatchNorm → ReLU → MaxPool) followed by a fully connected classifier
- Trains the model for 10 epochs using the Adam optimizer and cross-entropy loss
- Evaluates the model on the held-out test set and visualizes results with a confusion matrix
- Saves the trained model weights

## Results

- **Test accuracy:** ~78.97% after 10 epochs (fill in your actual number after running)
- Training/loss curves and a confusion matrix are included in the notebook

## How to run

1. Open `cifar10_cnn_classifier.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Go to `Runtime > Change runtime type` and select `GPU`
3. Run all cells top to bottom

## Tech stack

- Python
- PyTorch / torchvision
- Matplotlib, Seaborn, scikit-learn (for visualization and evaluation)

## What I'd improve with more time

- Data augmentation (random crop, horizontal flip) to reduce overfitting
- A deeper architecture or transfer learning from a pretrained model
- Learning rate scheduling and a proper validation split for hyperparameter tuning

---

This was built as a hands-on project to apply deep learning fundamentals (PyTorch, CNNs, model training/evaluation) beyond coursework.
