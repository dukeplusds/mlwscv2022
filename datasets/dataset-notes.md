Overview of Datasets

For the 3 days of the MLWS-CV, we are providing participants with a virtual computational environment where the datasets are already loaded. We are using 3 primary data sources:

    MNIST (Modified National Institute of Standards and Technology), which contains images of handwritten digits.

MNIST is available at http://yann.lecun.com/exdb/mnist/, and we're using all 4 of the datasets listed at the top of the page, including both the training set and test set

    CIFAR-10, a set of images in 10 different classes. (CIFAR stands for Canadian Institute For Advanced Research)

We are using the “CIFAR-10 python version” from https://www.cs.toronto.edu/~kriz/cifar.html

    COCO (Common Objects in Context)

We are using 5 of the datasets from https://cocodataset.org/#download:

2017 Train images [118K/18GB] 2017 Val images [5K/1GB] 2017 Test images [41K/6GB] 2017 Train/Val annotations [241MB] 2017 Stuff Train/Val annotations [1.1GB]

Going directly to the source dataset is helpful because it lets you keep track of the origins/provenance; it's also more efficient because these datasets can be huge and computationally expensive to upload/download/store. That's why we include the links in the notebooks and GitHub repository here, not the datasets themselves.