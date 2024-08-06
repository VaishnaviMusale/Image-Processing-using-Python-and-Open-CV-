  # Image-Processing-using-Python-and-Open-CV

As a proud member of our college's Official ROBOCON TEAM, "Team CiPHER," I contributed to an innovative project tailored specifically for the ROBOCON competition. Our challenge was to develop an object detection system capable of identifying and locating balls and seedlings of purple, red, and blue colors based on their shape and color.

To meet this challenge, we employed Python and Google Colab, harnessing the power of OpenCV and various machine learning libraries. This combination enabled us to accurately detect colors and shapes within images, thereby enhancing the computer vision capabilities of our system with deep learning techniques for robust and efficient real-time object detection.

Data Collection and Preparation
The initial phase involved collecting a comprehensive dataset of images featuring the target balls in different colors. Utilizing Roboflow, we meticulously labeled all images into three distinct classes: "Purple ball," "Red ball," and "Blue ball." To improve the model’s robustness and ensure it could detect objects under diverse conditions, we applied various augmentations to the dataset.

Model Training
With our augmented and labeled dataset, we proceeded to train our model using YOLO version 8, a state-of-the-art object detection algorithm known for its speed and accuracy. The training process was conducted on Roboflow, and upon completion, we extracted the trained model into a best.pt file, representing the optimal weights and parameters for object detection.

Prediction and Detection
For the prediction and detection phases, we chose Google Colab due to its user-friendly interface and powerful computational resources. We developed the detection code in Python, leveraging libraries such as ultralytics==8.0.196 to facilitate seamless model integration and execution. The result was a highly efficient detection system capable of real-time object identification and localization.
The performance of our system was evaluated through rigorous testing, achieving an impressive accuracy of approximately 92% and a precision of about 83.8%.

Conclusion
This project not only showcased our technical skills and teamwork but also provided valuable insights into the practical applications of deep learning and computer vision. By developing an advanced object detection system, we demonstrated the potential of leveraging cutting-edge technologies to solve complex challenges in real-world scenarios. The code for the detection system is available in the Colab file, serving as a testament to our innovative approach and dedication to excellence in the field of robotics and computer vision.

https://colab.research.google.com/drive/1y7bseeNPA541ckf8Ngy4FKJXfN_rqKSu#scrollTo=oos2RqUtBS7V
