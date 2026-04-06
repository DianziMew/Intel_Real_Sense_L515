
<div align = "center"> 
  
  # 🛰️ Intel® RealSense™ L515 LiDAR PyLive Toolkit

</div>
<p align="center">
<img src="https://img.shields.io/badge/Device-Intel%20RealSense%20L515-blue?style=for-the-badge&logo=intel" alt="Device">
<img src="https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Framework-PyRealSense2-red?style=for-the-badge" alt="Framework">
<img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License">
</p>

<p align="center">
<strong>一套专为 Intel® RealSense™ L515 固态激光雷达打造的实时采集开发工具</strong>

  本项目旨在为 Intel® RealSense™ L515 用户提供简洁、高效的 Python 接口封装。通过本项目，开发者可以快速实现毫米级精度的深度数据采集、实时点云渲染以及 RGB-D 自动对齐
<br />
  
</p>



























# demoIRS_1
![image](https://github.com/KejuLiu/IntelRealSense/blob/main/Intel10fps_1.gif)

# demoIRS_2
![image](https://github.com/KejuLiu/IntelRealSense/blob/main/Intel10fps_2.gif)

# demoIRS_3
![image](https://github.com/KejuLiu/IntelRealSense/blob/main/Intel10fps_3.gif)

***1.Create your env with Conda to configure usage scenarios, with STEP.2.***
![image](https://github.com/user-attachments/assets/6b6dd585-910e-4122-919f-ee0a4a27974a)

***2.Prepare your dependencies，main libraries and packages:***
pip install pyrealsense2==2.54.2.5684 (***Just Stable***)

pip install numpy

pip install opencv-python

pip install open3d

...

***3.Check the cam, most time, run this code named "CheckIRS.py", just check if the cam works.***
![image](https://github.com/user-attachments/assets/344ba50f-9f51-4af2-b48f-fd0418f52b5a)

***4.Check it!***

***5.With the Intel RealSense L515 cam checked, use your env.***

***6.If you wanna use this device for some machine learning or deep learning projects with GPU, just return STEP.2.***
![9b7208fd-5807-4667-bdfd-d628b7218685](https://github.com/user-attachments/assets/e7e3ad39-6b8d-42e4-8c96-fb24435d0f35)

***7.With this python check if your GPU env works.***
link:https://github.com/KejuLiu/check_Pytorch_scripts

***8.Know about your camera args, use this py if necessary.***
![image](https://github.com/user-attachments/assets/272904fa-dae9-4690-879a-db634fde7fc1)

***example.1.The depth args in size 640x480 and RGB args in size 1280x720:***

![image](https://github.com/user-attachments/assets/783cc8a8-acce-4d30-abe7-18125941bd68)

***example.2.The depth args in size 1024x768 and RGB args in size 1920x1080:***

![image](https://github.com/user-attachments/assets/1341ada8-976a-493c-b55b-f427389f5cb3)

















