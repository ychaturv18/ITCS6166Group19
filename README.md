# ITCS6166Group19

# Group Members : 

Kanchan Chandnani (801293770)
Yashaswini Golla (801312123)
Tushar Endra Koka (801311868)
Yash Chaturvedi (801317460)


Project Details : 
 # Topic : Real-Time Object-Detection

A deep learning-based object identification model for mobile and embedded devices called MobileNetSSD. It is a variation of the MobileNet architecture, which is made to be compact and effective so that it may be used on gadgets with little processing power.

A set of tools and features for processing still photos and moving pictures are offered by the open-source computer vision library known as OpenCV. It offers a number of algorithms for tasks like image filtering, feature detection, object recognition, and more. It supports a wide range of platforms, including desktop and mobile devices. It is possible to process photos and videos using OpenCV and employ MobileNetSSD-like object detection techniques. Developers can produce software that can recognize and track items by merging the two.

This project uses OpenCV to perform real-time object detection using a laptop camera. The plan is to loop over each frame of the video stream, look for objects, and then box up each finding..


# Setting up Streamlit and Required Packages for Real-Time Video
To install the necessary packages we have used the following commands:

- $ pip install -U streamlit streamlit-webrtc opencv-python-headless

Streamlit : The streamlit main package.
streamlit-webrtc : A custom component of Streamlit which deals with real-time video and audio streams.
opencv-python-headless : OpenCV. We choose the headless version here because we will construct the UI with Streamlit.

To launch the streamlit, run the below command.

-$ streamlit run app.py

Alternatively, try the below command if you're getting an error streamlit is not recognized even after installing the necessary packages.
-$ python -m streamlit run app.py

After a while, the Streamlit server process will boot up. Then access http://localhost:8501 to see the page like below (or it will automatically open in the browser by default).

# Web RTC:
WebRTC (Web Real-Time Communication) is a set of APIs that allow web browsers and mobile applications to communicate in real time. It includes audio and video streaming protocols and codecs, as well as tools for building peer-to-peer communication networks. Developers create real-time video communication applications with enhanced capabilities such as real-time object tracking, gesture recognition, and more by combining WebRTC and object detection.


# Github Model Reference:
https://github.com/chuanqi305/MobileNet-SSD

# Architecture Intended : 

# Client Server Architecture

# Project Plan : 

Week 1-2:

Define the project's requirements and objectives.
Look into object detection and WebRTC libraries and frameworks (such as OpenCV and MobileNetSSD)
Configure the development environment and the project structure.
Using a basic template, implement the WebRTC video stream capture and display functionality.
Test the video capture and display functionality on a variety of devices and browsers.

Week 3-4:

Use the MobileNetSSD model and OpenCV to implement the object detection functionality.
Integrate the object detection functionality with the capture and display of WebRTC video streams.
Examine the object detection functionality on various devices and browsers.
Use WebRTC communication and data exchange functionality to share the object detection results.

Week 5-6:

Integrate with frontend and backend for user interface.
Refactor the code and improve performance.
Tune the model parameters and reduce the computational load to improve the performance of the object detection functionality.
Test the application on various devices and browsers and collect user feedback.

Week 7-8:

Create documentation and get the code ready for deployment.
Monitor the application's performance and usage.
Document the deployment process and, as needed, provide support, implement Project Report and PowerPoint Presentation for documenting project findings and conclusion.










