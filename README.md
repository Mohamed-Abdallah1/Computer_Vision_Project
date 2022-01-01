# Computer_Vision_Project


الاسم : محمد عبدالله سعيد احمد


الاسم محمد فكري ابوالوفا



Computer Vision


About the Project :
In this Python Project, I had used Deep Learning to accurately identify the gender and age of a person from a single image of a face. The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. And so, I made this a classification problem instead of making it one of regression.

Additional Python Libraries Required :
•	OpenCV
  			 pip install opencv-python
•	argparse
 			  pip install argparse

The contents of this Project :
For face detection, we have a .pb file- this is a protobuf file (protocol buffer); it holds the graph definition and the trained weights of the model. We can use this to run the trained model. And while a .pb file holds the protobuf in binary format, one with the .pbtxt extension holds it in text format. These are TensorFlow files. For age and gender, the .prototxt files describe the network configuration and the .caffemodel file defines the internal states of the parameters of the layers.

Usage :
•	Open your Command Prompt or Terminal and change directory to the folder where all the files are present.
•	Detecting Gender and Age of face in Image Use Command :
  python detect.py --image <image_name>

Note: The Image should be present in same folder where all the files are present
•	Detecting Gender and Age of face through webcam Use Command :
  python detect.py
•	Press Ctrl + C to stop the program execution.




Examples :
 
 
 
