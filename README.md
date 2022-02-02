
Computer Vision

The model has been trained in only three epochs to show its correct work and to get some result in the test sample.**

A water surface image segmentation model has been created.
It is used the U-Net architecture based on the Keras library.

The data was downloaded, then further information was processed and retrieved. After that, the methods of decoding and data encoding are implemented. A Data Generator class was created that contains the method of creating batches and the method of manipulationg the data.
The filtered data was divided into two samples:
* training
* validation.

Data aggregator created. Callbacks have been added to monitor the learning process. Then all the blocks were tested for the correctness of their work.

The final step is to load the model from a file and start training.

The Model was builded in file model.ipynb


For testing model you need to open notebook test_model.ipynb 
