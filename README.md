# Personalized Image Tagging

Personalized Image Tagging is a relevant hashtag predictor for images. Now, why Personalized Image Tagging? Because, whenever a user uploads a photo on the social media, the tags provided by the user, oftentimes have very little or no relation to the actual features  of an image. That is why multi-label image classification fails when applied to images uploaded on the social media. This project uses the [HARRISON](http://academictorrents.com/collection/harrison-a-benchmark-on-hashtag-recommendation-for-real-world-images-in-social-networks) dataset, which stands for HAshtag Recommendation for Real world Images in SOcial Networks. This is a very realistic dataset composed of 57,383 images from instagram and an average of 4.5 hashtags per image.

![Picture of a sunset](https://github.com/chaitubhure/HARRISON_tagprediction/blob/master/sunset.jpg)

Multi-label classification | User-based tags
-------------------------- | ---------------
sunset, beach, sea | sunset, beach, **vacation, holiday, romantic, bliss, vacationgoals**

### Technology and platfroms

This project makes use of the [Google Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb#recent=true) platform with a free access to GPU for the image processing tasks. It took 3 hours to train the complete model on Colab and the other technologies used in this project are as follows:

* [Tensorflow](https://www.tensorflow.org/) - Most popular, deep learning framework
* [Slim](https://www.tensorflow.org/api_docs/python/tf/contrib/slim) - High level representation of Tensorflow
* [Pandas](https://pandas.pydata.org/) - Python library for performing operations on data

### Running the code

After installing the above mentioned dependencies, run the following commands in the Google Colab environment.

```
!git clone https://github.com/chaitubhure/HARRISON_tagprediction.git
!cd HARRISON_tagprediction
!python3 preprocess.py
!python3 train.py
!python3 evaluate.py
```

### High level view of the model and working

![Overview of the model](https://github.com/chaitubhure/HARRISON_tagprediction/blob/master/Overview%20of%20the%20model.png)

### Authors

* **Chaitanya Bhure** [Chaitanya Bhure](https://github.com/chaitubhure)

### License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/chaitubhure/HARRISON_tagprediction/blob/master/LICENSE) file for details

## Acknowledgments

* The dataset
```
@misc{HARRISON16,
Author = {Minseok Park and Hanxiang Li and Junmo Kim},
Title = {HARRISON: A Benchmark on HAshtag Recommendation for Real-world Images in Social Networks},
Year = {2016},
Eprint = {arXiv:1605.05054},
}
```
