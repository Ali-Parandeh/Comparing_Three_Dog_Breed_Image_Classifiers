# Comparing 3 pre-trained image classifiers
---

### Background Information
This python programme compares the performance of 3 pre-trained image classifiers (machine learning models) in classifying images of dogs and their breeds plus other animals.

Three pre-trained classifiers were compared in classifying 40 images of dogs and other animals. These classfiers were trained on the following artificial neural networks:
- [**Alexnet**](https://en.wikipedia.org/wiki/AlexNet)
- [**Resnet**](https://en.wikipedia.org/wiki/Residual_neural_network)
- [**VGG**](https://neurohive.io/en/popular-networks/vgg16/)

---

### Performance Test One - Classifying 40 images of dogs with variety of breeds and other animals

The overall count of the images used for performance tests include: 
- **Number of images:** 40
- **Number of dog images:**  30
- **Number of 'Not-a' dog images:** 10

These classifiers performed at various levels of **accuracy** and **speed** which are reported at the results section below. 

With machine learning models there always a trade-off between these two variables. Other variables that may come into play include:

- **Interoperability**: How flexible is the classifer when we apply to other applications.
- **Interpretability**: How easiy is to understand how the classifier performing.

### Results - Performance Test One

Using the 40 pet images, **VGG had the highest accuracy** - **100%** in classifying the dog vs non-dog images and **93.3%** in percentage of correct dog breed classification. 

The VGG model managed to classify all 40 images to **87.5%** accuracy. 

Other classifiers, Alexnet and Resnet managed to classify all images by **75%** and **82.5%** respectively. Therefore, Alexnet is worse than Resnet in than classifying dogs and dog breeds but better than Resnet at classifying non-dogs. 

**VGG is 10 times slower than both Alexnet and Resnet classifiers but the most accurate classifier.**

---

### Performance Test TWO - Classifying 4 images randomly selected from google image search. 

Pictures selected inlcude: 
- A dog
- An animal (lizard)
- an object. 
- The dog picture was flipped over to act as the 4th picture for this test.

The overall count of the images used for performance tests include: 
- **Number of images:** 4
- **Number of dog images:**  2
- **Number of 'Not-a' dog images:** 2

### Results - Performance Test Two

Both VGG and Alexnet did a great job at identifying the dogs vs non-dog images plus identifying the correct breeds. Alexnet was 10 times faster than VGG. If accurancy is important, VGG is the best classifier. However, if time is also important then Alexnet is the most efficient classifier. The worst classifier is Resnet because it did not manage to classify the lizard (non-dog) image. It appears that none of the classifiers are trained to classify non-animal non-dog images (i.e. coffee cup).
