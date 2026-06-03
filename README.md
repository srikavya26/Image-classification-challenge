## Image-classification-challenge

**Challenge Objective:**
***Classify images from the CIFAR-10.1 dataset, specifically, cifar10.1_v6_data.npy and
cifar10.1_v6_labels.npy, as accurately as possible using state-of-the-art image classification models
and creative preprocessing techniques.***
### The data can be accessed from the following link:
#### https://github.com/modestyachts/CIFAR-10.1/tree/master/datasets
## Tasks:
<html>
<ul>
Explore the dataset to understand its structure, class distribution, and characteristics.</ul>
<ol> Split the data: Use stratified 5-fold cross-validation to evaluate your models. That is, split the
dataset into 5 equal parts, and in each round, use 4 parts for training (80%) and 1 part for
testing (20%), ensuring class balance is preserved.</ol>
<ol> Apply 3 different image classification models, with at least one model from Hugging Face:
https://huggingface.co/models?pipeline_tag=image-classification&sort=trending
Participants are free to explore other options from PyTorch, TensorFlow or pre-trained models
from other sources.</ol>
<ol>You are encouraged to experiment with fine-tuning pre-trained models to adapt them to the
CIFAR-10.1_v6 dataset. Fine-tuning can involve adjusting hyperparameters, modifying
layers, or training specific parts of the model. Justify your fine-tuning approach in your
submission.</ol>
<ol>Apply different image augmentation techniques during training (e.g., random flipping,
Gaussian noise, rotations, etc.). Justify their choices in your submission.</ol>
<ol> Your goal is to maximise classification performance on the test sets. Report results using at
least accuracy and F1-score.</ol>
</html>
