# CNN-BASICS--MNIST

 We're constructing a simple but effective CNN that uses 32 filters of size 3x3
-  added a 2nd CONV layer of 64 filters of the same size 3x2
-  then downsample our data to 2x2, here he apply a dropout where p is set to 0.25
-  then flatten our Max Pool output that is connected to a Dense/FC layer that has an output size of 128
-  How we apply a dropout where P is set to 0.5
-  Thus 128 output is connected to another FC/Dense layer that outputs to the 10 categorical units