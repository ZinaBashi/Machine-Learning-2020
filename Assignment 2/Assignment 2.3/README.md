# Iteration 3

After reading into HOG, I experimented with the parameters, namely trying different combinations of pixels/cell and cells/block variations, as well as orientations (mostly kept between 9-12)
After trying to achieve the clearest processed image, I ran the two models and tweaked at the parameters. Mostly played with the number of hidden layers, and the max iteration to ensure generalizability with Aaron’s test set.
I also added a logarithmic correction function to increase contrast of the image

The best i could get on my personal test set is 8.8 on both the neural network and the perception
However, I fear the models are overfitted
