# Intrusion-Detection-Mechanism-for-Large-Scale-Networks-using-CNN-LSTM

The security issues in web application increasing rapidly. Attackers using web application gather the confidential data due to which users suffer from financial as well as identity loss. The hackers on the web applications mainly do denial of service attack and distributed denial of attacks. Intrusion detection is the task of detecting, preventing, and possibly reacting to  attacks and intrusions in network-based computer systems.
The goal of this proposed model is intrusion detection using the CNN-LSTM (hybrid model).
Convolutional Neural Network’s has the ability to extract spatial features and the Long Short-Term Memory Network’s ability to extract temporal features to create a hybrid intrusion detection system model. Based on the multiclass classification the 
model is trained using KDD Cup’99 dataset. The confusion matrix determines the system’s effectiveness, which includes evaluation criteria such as accuracy, precision, detection rate, F1-score, and false alarm rate (FAR).

# CNN-LSTM (hybrid model)
![image](https://user-images.githubusercontent.com/75250067/213447299-a7eebb11-8e68-4f5a-928c-6372740d5fa1.png)
Each piece of data in these datasets contains 42 features, 38 of which are numerical features, three of which are symbolic features, and one of which is a label.

<h3>The Data Preprocessing involves 3 steps</h3>

1. Numerical and one hot coding: 
The main features that require numerical and one-hot processing are the protocol_type, service, and flag features in these datasets. Protocol_type has three attributes, namely the transmission control protocol (TCP), user datagram protocol (UDP), and Internet control message protocol (ICMP). After numerical and one-hot processing, they can respectively be represented by the 1×3 dimensions vectors (0,0,1),(0,1,0), and (1,0,0).

3. Normalization
4. Transforming the Standardized data into Image format
