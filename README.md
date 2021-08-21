# Human-Face-Spoofing-Detection

Publication link - [Link](https://ieeexplore.ieee.org/document/9225495)

Human face and spoofing detection are of prime importance in many security verification and law enforcement applications. 
Recently, biometric identification has played a key role here. Face recognition is one such system widely used. However, such system has disadvantages.
Face spoofing is an attempt to deceive a face recognition system using a substitute for another’s person’s face – usually their photo, or a 3D mask.
In such system, it may happen that a person might easily log in to another person’s account by wearing a 3D mask that looks very original.
To prevent such attacks, a real human face detection system has to be in place.

![](https://github.com/sm823zw/Human-Face-Spoofing-Detection/blob/main/Images/Intro.png)

This [paper](https://ieeexplore.ieee.org/document/9225495) proposes a spoofing detection system using Convolutional Neural Networks (CNN). 
CNNs are well-equipped to extract vital features on its own from images without the need to manually select and extract features from them. 
The CNN classifier was implemented on a Raspberry Pi embedded system device for real-time detection. 
It should accurately predict whether or not a real human face is present in the frame of the recognizing/detecting camera.
The CNN model is very light-weight, easier and faster to load and run. It is ideally designed for real-time detection in embedded hardware. 

The CNN Architecture Used- 

![](https://github.com/sm823zw/Human-Face-Spoofing-Detection/blob/main/Images/CNN.jpg)

Performance on samples of HKBU-MARs Dataset

Face Samples -

![Face Samples](https://github.com/sm823zw/Human-Face-Spoofing-Detection/blob/main/Images/Face.png)

No Face Samples - 

![No Face Samples](https://github.com/sm823zw/Human-Face-Spoofing-Detection/blob/main/Images/NoFace.png)
