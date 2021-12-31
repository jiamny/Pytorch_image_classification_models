# Train image classification models with pytorch

Train pytorch image classification models on the 102 category flower dataset.

![Alt text](./data/example.jpg?raw=true)

## Image data

[102 Category Flower Dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html). The prepared dataset contains images of 102 different flower species with lables could be downloaded from (https://s3.amazonaws.com/content.udacity-data.com/nd089/flower_data.tar.gz). The flower category names are saved in json file "flowers_cat_to_name.json" of data folder.


Data file structure:

- flowers: folder of image data.
	- train, valid, test: subfolders for training, validating, and testing respectively.
     	- 1, 2, ..., 102: 102 subfolders whose names indicate different flower categories.

## Links
- [pytorch image models](https://github.com/rwightman/pytorch-image-models)

- [pytorch-cifar10](https://github.com/kuangliu/pytorch-cifar)

- [pytorch-cifar100] (https://github.com/weiaicunzai/pytorch-cifar100/tree/master/models)


