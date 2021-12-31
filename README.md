# About
This is a quick way to download image data from DuckDuckGo using fastai. No APIs are required.

# Dataset
The dataset consists of images of three subgroups of **crocodilia** which are crocodile, alligator, and gharial. The images are downloaded from DuckDuckGo using fastai's `search_images_ddg` function. The repo has sample images from the output of the python code.

The code in src extracts the images. In addition to arranging the images in three separate category folders, there is a pandas dataframe containing the following columns:  
1. Image URL
2. Image name
3. Image type: gif, jpg, png, etc.
4. Crocodilia subgroup: crocodile, alligator, and gharial

<img src="/crocodilia.jpeg" style="height: 300px; width:400px;"/>. <br> [Source: Wikipedia](https://upload.wikimedia.org/wikipedia/commons/5/58/Crocodilia_montage.jpg) <br>

Here is the [link](https://www.kaggle.com/rrrohit/crocodile-gharial-classification-fastai) to the Kaggle Dataset posted by me. 


