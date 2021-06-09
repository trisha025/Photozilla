## Welcome to the Photozilla Dataset

   The advent of social media platforms has been a catalyst for the development of digital photography that engendered a boom in vision applications. With this motivation, we introduce a large-scale dataset termed **Photozilla**, which includes over **990k** images belonging to **10** different photographic styles. The dataset is then used to train **3** classification models to automatically classify the images into the relevant style which resulted in an accuracy of **96%**. With the rapid evolution of digital photography, we have seen new types of photography styles emerging at an exponential rate. On that account, we present a novel Siamese-based network that uses the trained classification models as the base architecture to adapt and classify unseen styles with only **25** training samples. We report an accuracy of over **68%** for identifying 10 other distinct types of photography styles.
### Photozilla Classes


```markdown

Photozilla dataset consists of a total of 20 classes. Out of that 10 classes have on average 100k images per class. These classes and images were used to train our image classification models. In order to evaluate our models capability to adapt to new photography styles we further augment our dataset with 10 additional classes. These additional classes have only 25 training samples per each class.

#  
## Original 10 classes
1. Nature
2. Potrait
3. Landscape
### Additional 10 classes
1. Architecture
2. Underwater


**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```


### Citation

If you find the code useful, please cite us:

```markdown
Singhal T, Liu J, Blessing LT, Lim KH. Photozilla: A Large-Scale Photography Dataset and Visual Embedding for 20 Photography Styles. In 2021 9th Women in Computer Vision (WiCV) workshop  in conjuction with Computer Vision and Pattern Recognition (CVPR 2021).

```
