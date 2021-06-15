# Photozilla

   The advent of social media platforms has been a catalyst for the development of digital photography that engendered a boom in vision applications. With this motivation, we introduce a large-scale dataset termed **Photozilla**, which includes over **990k** images belonging to **10** different photographic styles. The dataset is then used to train **3** classification models to automatically classify the images into the relevant style which resulted in an accuracy of **96%**. With the rapid evolution of digital photography, we have seen new types of photography styles emerging at an exponential rate. On that account, we present a novel Siamese-based network that uses the trained classification models as the base architecture to adapt and classify unseen styles with only **25** training samples. We report an accuracy of over **68%** for identifying 10 other distinct types of photography styles.
   
   ### Link: [Photozilla Dataset](https://sutdapac-my.sharepoint.com/:f:/g/personal/trisha_singhal_sutd_edu_sg/EqS3NL3qwYNMglM8cQFOmnYB4zOqURLmOcqAisj7MKvG2Q?e=8rQfGj)
   
## Photozilla Classes


Photozilla dataset consists of a total of 20 classes. Out of that 10 classes have on average 100k images per class. These classes and images were used to train our image classification models. In order to evaluate our models capability to adapt to new photography styles we further augment our dataset with 10 additional classes. These additional classes have only 25 training samples per each class.
  
### Original 10 classes


1. [Aerial](https://en.wikipedia.org/wiki/Aerial_photography)
2. [Architecture](https://en.wikipedia.org/wiki/Architectural_photography)
3. [Event](https://en.wikipedia.org/wiki/Event_photography)
4. [Fashion](https://en.wikipedia.org/wiki/Fashion_photography)
5. [Food](https://en.wikipedia.org/wiki/Food_photography)
6. [Nature](https://en.wikipedia.org/wiki/Nature_photography)
7. [Sports](https://en.wikipedia.org/wiki/Sports_photography)
8. [Street](https://en.wikipedia.org/wiki/Street_photography)
9. [Wedding](https://en.wikipedia.org/wiki/Wedding_photography)
10. [Wildlife](https://en.wikipedia.org/wiki/Wildlife_photography)


### Additional 10 classes


1. [Abstract](https://en.wikipedia.org/wiki/Abstract_photography)
2. [Astrophotography](https://en.wikipedia.org/wiki/Astrophotography)
3. [Automotive]()
4. [Landscape](https://en.wikipedia.org/wiki/Landscape_photography)
5. [Lifestyle](https://en.wikipedia.org/wiki/Lifestyle_photography)
6. [Long Exposure](https://en.wikipedia.org/wiki/Long-exposure_photography)
7. [Panorama](https://en.wikipedia.org/wiki/Panoramic_photography)
8. [Portrait](https://en.wikipedia.org/wiki/Portrait_photography)
9. [Travel](https://en.wikipedia.org/wiki/Travel_photography)
10. [Underwater](https://en.wikipedia.org/wiki/Underwater_photography)


## Citation


If your publication uses the data, either in full or in part, you should cite the paper below:


```markdown
Singhal T, Liu J, Blessing LT, Lim KH. Photozilla: A Large-Scale Photography Dataset and Visual Embedding for 20 Photography Styles. In 2021 9th Women in Computer Vision (WiCV) workshop  in conjuction with Computer Vision and Pattern Recognition (CVPR 2021).

```
