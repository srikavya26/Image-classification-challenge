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

## PS: 
###  We do not claim ownership of these concepts,  which were adapted to classify images from the CIFAR-10.1 v6 dataset. Reported model accuracies  (e.g., ViT: 0.9825, EfficientNetV2-S: 0.9770, RepVGG-A2: 0.9750) may vary slightly across runs  due to randomization in stratified 5-fold cross-validation and MixUp’s random state. 
#### The models  used—RepVGG-A2 (BSD 3-Clause License, chenyaofo/pytorch-cifar-models), EfficientNetV2-S  (public license, PyTorch), and ViT-Base-Patch16-224 (Apache 2.0 License, Hugging Face)—are  sourced from public repositories, and we do not claim ownership or creation of them. • RepVGG-A2: Sourced from https://github.com/chenyaofo/pytorch-cifar-models with a  BSD 3-Clause License.  EfficientNetV2-S: Sourced from PyTorch ,ViT-Base-Patch16-224: Sourced from https://huggingface.co/nielsr/vit-base-patch16-224- in21k-finetuned-cifar10 with an Apache 2.0 License 
