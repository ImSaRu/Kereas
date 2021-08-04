# Image segmentation with a U-Net-like architecture

source:　https://keras.io/examples/vision/oxford_pets_image_segmentation/

## prepare images
curl -O https://www.robots.ox.ac.uk/~vgg/data/pets/data/images.tar.gz
curl -O https://www.robots.ox.ac.uk/~vgg/data/pets/data/annotations.tar.gz
tar -xf images.tar.gz
tar -xf annotations.tar.gz
