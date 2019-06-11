# Personalized Image Tagging

Personalized Image Tagging is a relevant hashtag predictor for images. Now, why Personalized Image Tagging? Because, whenever a user uploads a photo on the social media, the tags provided by the user, oftentimes have very little or no relation to the actual features  of an image. That is why multi-label image classification fails when applied to images uploaded on the social media. This project uses the HARRISON dataset, which stands for HAshtag Recommendation for Real world Images in SOcial Networks. This is a very realistic dataset composed of 57,383 images from instagram and an average of 4.5 hashtags per image.

![Picture of a sunset](https://github.com/chaitubhure/HARRISON_tagprediction/blob/master/sunset.jpg)

### Technology and platfroms

This project makes use of the [Google Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb#recent=true) platform with a free access to GPU for the image processing tasks. It took 3 hours to train the complete model on Colab and the other technologies used in this project are as follows:

* [Tensorflow](https://www.tensorflow.org/) - The most popular, deep learning framework
* [Slim](https://www.tensorflow.org/api_docs/python/tf/contrib/slim) - A high level representation of Tensorflow
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

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
