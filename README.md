# Stealing-Fuel-Detection-For-a-generator-The-Survivalnce-app-

Project Objective:
To enhance the security system using the modern AI systems and algorithms, which consistently and accurately detect the fuel stealing activities.
Practical Application:
Security or Protections from unusual theft activities of confidential and valuable stuffs in any industry is essential factor, Fuel Stealing is one of the parts of these security factors, so our project digitalized and enhance the security system.
Technologies:
Language/Environment: Python, Flask, NodeJS, React-native, SQL
Library: Pytorch, OpenCV. Socket.IO, RabbitMQ, Redis , 
Algorithms: Resnet18, YOLO-v2

 Abstract:
As with the advancements in the field of artificial intelligence and automation, the importance of precise Deep learning/computer vision has greatly increased. One of the most significant aspects of the computer vision is to detect the unusual activities accurately. There are numerous surveillance systems available related to our project, like "GSM based vehicle fuel theft detection system" but this project is based on sensor detection if someone try to steal the fuel from car/bike liquid level sensor detect this reduction of fuel and send SMS to owner, our project is also base on Fuel stealing detection but its features and attributes make it unique and specific than others related projects. The foremost motive to work on this project is security concern in our campus to keep track the stealing activity. In some areas, CCTV monitoring is available which is manually controlled to keep track unusual activities, but manually monitoring is not an optimized solution because it is extremely cost-effective, less efficient and not possible for 24 hours, so these complications persuades us to come up with high accurate, efficient, low cost and prolonged sprint solution. The proposed project is to detect the unusual activities using CNN and deep learning, this project is to enhance the security by smart monitoring. This smart system will detect the person who attempts any activity to steal the fuel, our system will capture the frame and notify the concerned staff. There will be one cameras near the generator which is responsible to detect stealing activities Rest of two cameras on main gate is responsible to detect the fuel vehicle entrance and exit, which send signal to the server that vehicle has enter, then server will deactivate the camera, when vehicle pass the exit gate camera send activate signal to server to enable the stealing detection camera. Following are the features of our project.
•	Fuel Stealing Detection
•	Camera Disruption
•	Refueling Schedule
•	Distributed System


------>Resnet18
        Download and install the Deep Learning Toolbox Model for ResNet-18 Network support package.

Type resnet18 at the command line.

resnet18


*Expalanation oF Resnet18
             ResNet-18 is a convolutional neural network that is trained on more than a million images from the ImageNet database . The network is 18 layers deep and can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals
             
------->Yolo -v2     
               
•	both Windows and Linux

•	both OpenCV 3.x and OpenCV 2.4.13

•	both cuDNN 5 and cuDNN 6

•	CUDA >= 7.5

•	also create SO-library on Linux and DLL-library on Windows
Installation of darknet in LINUX (GPU version):
•	Open new linux terminal in aws or google cloud which should have the following packages installed.
Note: Choose aws AMI:Deep Learning Base AMI (Ubuntu) Version 1.0 - ami-a1e534d9 which has built in packages..

o CUDA 8.0: https://developer.nvidia.com/cuda-downloads

  o Instructions to install CUDA: http://docs.nvidia.com/cuda/cuda-installation-guide-linux/index.html
o Install either of the opencv:

  o	OpenCV 3.x: https://www.pyimagesearch.com/2016/10/24/ubuntu-16-04-how-to-install-opencv/


  o	OpenCV 2.4.13: find the attachment opencv2.4_instructions.txt to install in linux.
o GPU CC >= 3.0 if you use cuDNN + CUDA:

o	Download cudnn by registering in nvidia: https://developer.nvidia.com/rdp/cudnn-download

o	Instructions to install cudnn: http://docs.nvidia.com/deeplearning/sdk/cudnn-install/index.html



*Expalanation oF Yolo -v2
                        The major concept of YOLO is to build a CNN network to predict a (7, 7, 30) tensor. It uses a CNN network to reduce the spatial dimension to 7×7 with 1024 output channels at each location. YOLO performs a linear regression using two fully connected layers to make 7×7×2 boundary box predictions (the middle picture below). To make a final prediction, we keep those with high box confidence scores (greater than 0.25) as our final predictions (the right picture).
                        
                       

It measures the confidence on both the classification and the localization (where an object is located).
We may mix up those scoring and probability terms easily. Here are the mathematical definitions for your future reference.
               
             

