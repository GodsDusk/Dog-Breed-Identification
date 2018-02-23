# Kaggle Dog Breed Identification

This is a tensorflow and keras re-implementation of [DogBreed_gluon](https://github.com/ypwhs/DogBreed_gluon), a code for [Dog Breed Identification](https://www.kaggle.com/c/dog-breed-identification) competition. 

Thanks for the author [@ypwhs](https://github.com/ypwhs).

## Dependency (development environment)

- OS: Ubuntu 16.04
- Python: 2.7
- pip: tqdm, numpy, tensorflow(1.4), keras(2.0), pandas, h5py, sklearn 

## Preparation

- Place the [data files](https://www.kaggle.com/c/dog-breed-identification/data) and [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/) into root fold.  
- Download [tensorflow model zoo](https://github.com/tensorflow/models/tree/master/research/slim) fold into root fold.





```
Dog-Breed-Identification
|   README.md
|   get_features.py
|   pred.py
|   sample_submission.csv
|
|_______slim
| |     setup.py
| |     slim_walkthrough.ipynb
| |     ...
| |
| |____nets
| |     resnet_v1.py
| |     inception.py
| |     ...
| |
| |____preprocessing
| |     vgg_preprocessing.py
| |     inception_preprocessing.py
| |     ...
| |
| |...
|
|______Images
| |____ n02085620-Chihuahua
| |____ n02085782-Japanese_spaniel
|       ...
|
|______test


```

##Run

    python get_features.py
    python pred.py