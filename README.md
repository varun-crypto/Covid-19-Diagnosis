# Covid-19-Diagnosis Using CT - Images

A CNN model is designed and implemented to classify a CT image as COVID-19 positive or negative.

The influence of HyperParameters tested on CNN by training and validation the model with various values.

The Hyperparameters tested in this project are:
1) Number of Epochs and Layers

2) Input and Output Activation Function

3) Input Shape

4) Image Orientation

The dataset used in this project has been taken from https://github.com/UCSD-AI4H/COVID-CT

The COVID-CT-Dataset has 349 CT images containing clinical findings of COVID-19 from 216 patients

The final Accuracy achieved was 98.6%
 
 The graph of traning and accuracy values of initial model.
 
 ![image](https://user-images.githubusercontent.com/69026838/197541818-35295c35-fdde-4d98-87b1-15ccabd98d27.png)

The graph of traning and accuracy values of the model for optimal values of number of epochs and layers. (Optimal Value is 5 Layers and 50 Epochs)

![image](https://user-images.githubusercontent.com/69026838/197542484-ce7dfd06-47a9-4493-8e6f-88c9919a1b4f.png)

The graph of traning and accuracy values of the model for optimal values of activation function. (Optimal Value is (Relu, Sigmoid))

![image](https://user-images.githubusercontent.com/69026838/197542753-d4338df5-81aa-442d-8d0f-95ae9d081570.png)

The graph of traning and accuracy values of the model for optimal values of Input Shape. (Optimal Value is (250,250,3))

![image](https://user-images.githubusercontent.com/69026838/197542922-a3ee2c6e-febd-42b0-b97b-dc96f103668e.png)

The graph of traning and accuracy values of the model for optimal values of Image Orientation. (Optimal Value is 135°)

![image](https://user-images.githubusercontent.com/69026838/197543102-db5948c1-d7e3-4f10-892e-68d8cd4b2bf2.png)



