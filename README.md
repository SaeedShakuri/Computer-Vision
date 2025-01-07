# Pytorch
Here, I share some of my notebooks, working with the PyTorch library on Computer Vision tasks. 
All the notebooks are in the context of Image Classification and Object Detection.
- **An image classification using a CNN and regularization terms (Dropout and batch normalization), using the MNIST dataset. (Pytorch_ImageClassification(CNN)_Regularization.ipynb)**
    - Data preprocessing steps
    - DataLoaders
    - Building the model
    - Evaluating the model
- **PyTorch Lightning (Pytorch_Lightning_(Image Classification - Transfer Learning).ipynb)**
    - Image classification using a CNN and Cats & Dogs dataset.
    - Fine-tuning a certain number of layers of an ImageNet pre-trained model (Transfer Learning).
- **Transfer Learning (Pytorch_Transfer_Learning.ipynb)**
    - Fine-tuning the whole network using an ImageNet pre-trained model with the Hymenoptera dataset (Ants & Bees).
    - Fine-tuning a certain number of layers using an ImageNet pre-trained model with the Hymenoptera dataset (Ants & Bees).
- **Extracting features of images using VGG16 and using Logistic Regression for the classification stage. (Pytorch_ImageClassification_Logistic_Regrission.ipynb)**
- **Traffic sign detection using Faster R-CNN and Transfer Learning procedure. (PyTorch_Object_Detection_Transfer_Learning_Traffic_Sign.ipynb)**
    - Download the dataset and transfer it to Drive.
    - Data preprocessing steps (Separation for training and test, resizing, augmentation, format changing)
    - Custom data loaders
    - Building the model (Faster R-CNN, Vision Transformer, FPN, Data imbalance)
    - Evaluating the model
