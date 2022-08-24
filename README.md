# Fault-detection-in-an-induction-motor

In this project, the aim is to develop an fault detection system that can detect the faults in an induction motor using machine learning techniques.
Deep neural networks along with ReLu and softmax activations are used to classify the input data into 6 classes i.e, Normal, Mechanical imbalance, Horizontal misalignment, Vertical misalignment and bearing faults such as underhang, overhang. 

the inputs for the  DNN model is the acceleration values i.e, Vibration recorded from the induction motor at  frontal and rear bearings.

Preprocessing.ipynb file consists for all the for loading the raw data, preprocessing and saving the processed data.

The model.ipynb file contains the code for loading the processed data, Data splitting, Training the model and testing the accuracy of the model.

dnn_full_w_oh.h5 refers to the saved weights of the neural network trained on data consisting overhanged condition. similarly dnn_full_wo_oh.h5 is trained using data without overhanging condition to find the bottlenecks of the data and improve performance.

The data is downloaded from the machinery fault data (MAFAULDA) source : http://www02.smt.ufrj.br/~offshore/mfs/

the histogram for the vibrations at frontal and rear bearings is shown in fig below

![19](https://user-images.githubusercontent.com/61615845/173837265-d688d54a-4de3-4cc1-9c76-c4206411a9ee.png)
![20](https://user-images.githubusercontent.com/61615845/173837310-e76a361e-4505-4a32-917e-5bbe819bf73e.png)
![21](https://user-images.githubusercontent.com/61615845/173837330-f0793e7e-4cdf-48e0-b084-fdc87ba0a97c.png)


the overall model accuracy for classification of the input data into each classes is shown in the fig below

![34](https://user-images.githubusercontent.com/61615845/173838137-37d01cf1-54c1-40b8-a601-4021fb47b9bf.png)


