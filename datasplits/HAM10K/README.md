This original HAM10K dataset consists of 10K training, 193 validation and 1.5K test images. This dataset is highly
imbalanced with just 115 training images in the smallest class and 6705 training images in the largest class. 
When experimenting with N training images per class, if a class does not have N images, we just use all the images
from that class.

train_full.txt - 10015 training images 

train_100img_max_per_class.txt - 700 training images

train_250img_max_per_class.txt - 1507 training images

train_500img_max_per_class.txt - 2584 training images

train_1000img_max_per_class.txt - 4098 training images

val.txt - 193 validation images 

test.txt - 1512 test images
