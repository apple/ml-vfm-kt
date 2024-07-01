The original ADE20K dataset consists of 20.2K training and 2K validation images. We split the original training set 
into two subsets with 19.2K and 1K images, and use them for training and validation, respectively, in our experiments.
We use the original 2K validation set as the test set in our experiments.

train_full.txt - 19210 training images

train_1200img.txt - 1200 training images

train_2401img.txt - 2401 training images

train_4802img.txt - 4802 training images

train_9605img.txt - 9605 training images

val.txt - 1000 validation images

test.txt - 2000 test images



We also expanded the above training datasets by retrieving similar images from the YFCC15M dataset. The corresponding 
retrieved image sets are provided below:

yfcc_retrieved_images_with_1200query.txt - 152400 images from YFCC15M retrieved using 1200 images from ADE20K as queries.

yfcc_retrieved_images_with_2401query.txt - 151263 images from YFCC15M retrieved using 2401 images from ADE20K as queries.

yfcc_retrieved_images_with_4802query.txt - 148862 images from YFCC15M retrieved using 4802 images from ADE20K as queries.

yfcc_retrieved_images_with_9605query.txt - 144075 images from YFCC15M retrieved using 9605 images from ADE20K as queries.

yfcc_retrieved_images_with_19210query.txt - 134470 images from YFCC15M retrieved using 19210 images from ADE20K as queries.
