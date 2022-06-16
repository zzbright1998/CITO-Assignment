## Experiment 1 & 2

#### tstrain_V2

the main code for performing the reconstruction. 

#### fbp_c_V2

the code for generating reconstruction and projection of training data.

#### trainning_data

perform the data preparation for the **shift and sum**

#### Gauss

the phantom generator for the "three shape phantoms (rectangle, siemens star, gaussian blobs)"

#### Rec

Treat every set of weights (between input and hidden layer) as the FBP filter. Use the filter to reconstruct the image. However we attempted to use the method but failed. So in the experiment we reconstruct the image pixel by pixel.



#### how to run?

1. install the tomosipo environment (https://github.com/ahendriksen/tomosipo )
2. install the ts algorithm for SIRT (https://github.com/ahendriksen/ts_algorithms)
3. run the tstrain_V2 (you can modify the angles and hidden nodes numbers)





## Experiment 3

Folder **pynnfbp-1.2.2** is an example code from Astra Toolbox (http://dmpelt.github.io/pynnfbp/), we use it for performing the third experiment (investigate the generalization of algorithm).

The folder **phantom** in **pynnfbp-1.2.2**  provides the lung and brain image, which is for training the neural network.

#### how to use?

1. install the nnfbp
2. run the code ./examples/ASTRAExample.py

