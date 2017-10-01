# cnn_cifar10 (best to view as raw file)

A simple CNN implementation using theano and keras. 
Accuracy 78%

model summary:
''' input layer - 2D_conv layer with 32 feature map with a size of 3*3. 
                    Followed by dropout to 20%
        2nd layer - 2D_conv layer with 32 feature map with a size of 3*3. 
                    Followed by a max pooling layer of size 2*2
        3rd layer - 2D_conv layer with 64 feature map of size 3*3.
                    Follwed by dropout layer to 20%
        4th layer - 2D_conv layer with 64 feature map of size 3*3.
                    Follwed by a max pooling layer of size 2*2
        5th layer - 2D_conv layer with 128 feature map of size 3*3.
                    Followed by the same dropout layer set to same 20%
        6th layer - 2D_conv layer with 128 feature map of size 3*3.
                    Followed by a max pooing layer of size 2*2
        7th layer - Flatten layer to flatten all the feature and weights.
                    Follwed by dropout layer to 20%
        8th layer - A fully connected layer with 1024 features with relu activation
                    Followed by a dropout layer of 20%
        9th layer - Again a fully connected layer with 512 features with relu
                    Dropout of 20%
    output layer - Fully connected output layer with 10 units and a softmax acivation function'''

