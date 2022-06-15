# Fault-detection-in-an-induction-motor

In this project, the aim is to develop an fault detection system that can detect the faults in an induction motor using machine learning techniques.
Deep neural networks along with ReLu and softmax activations are used to classify the input data into 6 classes i.e, Normal, Mechanical imbalance, Horizontal misalignment, Vertical misalignment and bearing faults such as underhang, overhang. 

the inputs for the  DNN model is the acceleration values i.e, Vibration recorded from the induction motor at  frontal and rear bearings.

The data is downloaded from the machinery fault data (MAFAULDA) source : http://www02.smt.ufrj.br/~offshore/mfs/

the histogram for the vibrations at frontal and rear bearings is shown in fig below

![19](https://user-images.githubusercontent.com/61615845/173837265-d688d54a-4de3-4cc1-9c76-c4206411a9ee.png)
![20](https://user-images.githubusercontent.com/61615845/173837310-e76a361e-4505-4a32-917e-5bbe819bf73e.png)
![21](https://user-images.githubusercontent.com/61615845/173837330-f0793e7e-4cdf-48e0-b084-fdc87ba0a97c.png)


the overall model accuracy for classification of the input data into each classes is shown in the fig below

![34](https://user-images.githubusercontent.com/61615845/173838137-37d01cf1-54c1-40b8-a601-4021fb47b9bf.png)


