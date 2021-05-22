# kaggle_competition

This Repository contains solution for few kaggle competition in which i participated

# Shopee Price match Guarantee
https://www.kaggle.com/c/shopee-product-matching

Here we have to match two products based on their posted image and title of image. Implemented siamese network to predict distance between two image and title. 

Trained a base network for image.

![image](https://user-images.githubusercontent.com/29758488/117703668-8d3bcb80-b1e7-11eb-94ed-083615e8d25b.png)

Extracted the features for both image using same base network and then calculated the distance bewteen two images.

![image](https://user-images.githubusercontent.com/29758488/117704346-5d40f800-b1e8-11eb-8ad9-12b9d8b9fde5.png)

Base network for image title

![image](https://user-images.githubusercontent.com/29758488/117704968-18699100-b1e9-11eb-8b57-d2886141ced8.png)

Model to calculate distance between two titles

![image](https://user-images.githubusercontent.com/29758488/117705292-82823600-b1e9-11eb-9b9d-02a005d9a48a.png)
