# Style-Transfer
This is the Pytorch implementation of Style Transfer based on VGG-19 model.  The convolutional layers are named by stack and their order in the stack. Conv_1_1 is the first convolutional layer that an image is passed through, in the first stack. Conv_2_1 is the first convolutional layer in the second stack. The deepest convolutional layer in the network is conv_5_4.

The style is extracted from conv1_1,conv2_1, conv3_1, conv4_1 and conv5_1.
The content features are extracted from conv4_2 ( 2nd Convolution layer of the 4th stack)
