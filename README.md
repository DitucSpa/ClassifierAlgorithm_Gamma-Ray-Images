# ComputerVisionProject
In this project we have developed an algorithm that classifies gamma-ray images generated via software for a given set of astrophysics parameters. In particular, the algorithm was trained and tested with a dataset composed of three types of images: images without gamma-ray sources (class 0), with only one sources (class 1) and with two sources (class 2). For class 1 images, the algorithms outputs also the coordinates of the source, with a maximum error of 0.1°, with respect to the true coordinates, which are RA (right ascension) and DEC (declination) coordinate.
In these repository there are three notebooks:
- Generate_sources.ipynb, which generates the gamma-ray images;
- TuningHyperparameters_test.ipynb, which uses the generated dataset to tune the hyperparameters of the algorithm and evaluate its performance;
- Example.ipynb, which performs an example of the algorithm for 3 images.

You can also find the file 'data folder' (where the models are saved), 'models folder' (where the .xml code for generating image models are saved), 'images folder' (where the generated images are saved) and a 'coordinate.csv', which is a table where the coordinates (if an image has a single source) and classes for each type of image are saved.
