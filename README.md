Chapter 1: INTRODUCTION
1.1 Aim
Aim of this project is to develop an face recognition based attendance tracing system 
using computer vision and machine learning concept
1.2 Project Description
Face is the representation of one’s identity. Hence, we have proposed an automated student 
attendance system based on face recognition. Face recognition system is very useful in life 
applications especially in security control systems. The airport protection system uses face 
recognition to identify suspects and FBI (Federal Bureau of Investigation) uses face 
recognition for criminal investigations. In our proposed approach, firstly, video framing is 
performed by activating the camera through a user friendly interface. The face ROI is detected 
and segmented from the video frame by using Viola-Jones algorithm. In the pre-processing 
stage, scaling of the size of images is performed if necessary in order to prevent loss of 
information. The median filtering is applied to remove noise followed by conversion of color
images to grayscale images. After that, contrast-limited adaptive histogram equalization 
(CLAHE) is implemented on images to enhance the contrast of images. In face recognition 
stage, enhanced local binary pattern (LBP) and principal component analysis (PCA) is applied 
correspondingly in order to extract the features from facial images. In our proposed approach, 
the enhanced local binary pattern out of perform the original LBP by reducing the illumination 
effect and increasing the recognition rate. Next, the features extracted from the test images are 
compared with the features extracted from the training images. The facial images are then 
classified and recognized based on the best result obtained from the combination of algorithm, 
enhanced LBP and PCA. Finally, the attendance of the recognized student will be marked and 
saved in the excel file. 
The student who is not registered will also be able to register on the spot and notification will 
be given if students sign in more than once. The average accuracy of recognition is 100 % for 
good quality images, 94.12 % of low-quality images and 95.76 % for Yale face database when 
two images per person are trained
1.3 About the project 
In the recent years, Image processing which deals with extracting useful information from a 
digital image plays a unique role in the advent of technological advancements. It focuses on 
two tasks
• Improvement of pictorial information for human interpretation
• Processing of image data for storage, transmission and representation for autonomous 
machine perception.
Also people have started to use image capturing devices never as before with the 
advent of smart phones and closed circuit television. Since the application of image processing 
is vast, extensive work and research have been carrying out in utilizing its potential to and to 
make new innovative applications. Facial recognition has been the earliest of the application 
derived from this technology, which is one of the most fool proof methods in human detection. 
Face is a typical multidimensional structure and needs good computational analysis for 
recognition. Biometrics methods have been used for the same purpose since a long time now. 
Although it is effective, it is still not completely reliable for purpose of detecting a person.
Face recognition can be applied for a wide variety of problems like image and film
processing, human-computer interaction, criminal identification etc. This has motivated 
researchers to develop computational models to identify the faces, which are relatively simple 
and easy to implement. The existing system represents some face space with higher 
dimensionality and it is not effective too. The important fact which is considered is that 
although these face images have high dimensionality, in reality they span very low 
dimensional space. So instead of considering whole face space with high dimensionality, it is 
better to consider only a subspace with lower dimensionality to represent this face space. The 
goal is to implement the system (model) for a particular face and distinguish it from a large 
number of stored faces with some real-time variations as well. The Eigen face approach uses 
Principal Component Analysis (PCA) algorithm for the recognition of the images. It gives us 
efficient way to find the lower dimensional space.
1.4 Problem statement
Attendances of every student are being maintained by every school, college and 
university. Empirical evidences have shown that there is a significant correlation between 
students ‘attendances and their academic performances. There was also a claim stated that the 
students who have poor attendance records will generally link to poor retention. Therefore, 
faculty has to maintain proper record for the attendance. The manual attendance record system 
is not efficient and requires more time to arrange record and to calculate the average 
attendance of each student. Hence there is a requirement of a system that will solve the 
problem of student record arrangement and student average attendance calculation. One 
alternative to make student attendance system automatic is provided by facial recognition
Chapter 2: OBJECTIVES OF THE PROJECT
REQUIREMENTS ANALYSIS
2.1 Functional requirements
Webcam
In this project input is the image hence we need a device like webcam to accept the input data 
through cam
Dataset
In this project to detect face present in the image we need dataset hence face features dataset 
such as haarcascade_frontalface.xml is used to detect face
Libraries
The proposed project is based on computer vision and machine learning concept therefore 
librararies such as numpy, opencv, pillow etc are used
Algorithms
To detect face present in image viola Jones method is used which refersharcascase classifier 
technique, to recognize the face LBPH (Local Binary Pattern Histogram ) is used
2.2 Non functional requirements
Correctness:
In this project care is taken by means of business rules to ensure only valid data is accepted 
using appropriate sensors
Reliability: 
The proposed project works well in all environments, its being tested for various scenarios 
Robustness: 
The code takes care to deal with unexpected cases by means of alerts
Maintainability: 
Project works fine with the given requirements; new requirements could be done with the 
assistance of developer.
Portability: This application works on all platforms irrespective of operating system and 
machine detailsHARDWARE & SOFTWARE REQUIREMENTS
2.3 Hardware requirements
 Processor: Intel® Core (TM) i5-6200u CPU @ 2.30GHz 2.40GHz.
 Installed RAM: 4.00GB. 
 System type: 64 bit operating system.
 Webcam
2.4 Software requirements
 Programming language : Python
 Front end : Opencv
 IDE : Pycharm
 Libraries : Opencv, numpy, pillow
2.5 Introduction to Python
Python is an interpreted, high-level and general-purpose programming language. 
Python's design philosophy emphasizes code readability with its notable use of significant 
indentation. Its language constructs and object-oriented approach aim to help programmers 
write clear, logical code for small and large-scale projects.
Python is dynamically-typed and garbage-collected. It supports multiple programming 
paradigms, including structured (particularly, procedural), object-oriented and functional 
programming. Python is often described as a "batteries included" language due to its 
comprehensive standard library.
Guido van Rossum began working on Python in the late 1980's, as a successor to the 
ABC programming language, and first released it in 1991 as Python 0.9.1. Python 2.0 was 
released in 2000 and introduced new features, such as list comprehensions and a garbage 
collection system using reference counting and was discontinued with version 2.7.18 in 2020.
Python 3.0 was released in 2008 and was a major revision of the language that is not 
completely backward-compatible and much Python 2 code does not run unmodified on Python 
3. The language's core philosophy is summarized in the document The Zen of Python (PEP 
20), which includes aphorisms such as
 Beautiful is better than ugly.
 Explicit is better than implicit.
 Simple is better than complex Complex is better than complicated.
 Readability counts.
Rather than having all of its functionality built into its core, Python was designed to be highly 
extensible. This compact modularity has made it particularly popular as a means of adding 
programmable interfaces to existing applications. Van Rossum's vision of a small core 
language with a large standard library and easily extensible interpreter stemmed from his 
frustrations with ABC, which espoused the opposite approach.
Key features of python
There are many features in Python, some of which are discussed below 
1. Easy to code:
Python is a high-level programming language. Python is very easy to learn the language as 
compared to other languages like C, C#, Javascript, Java, etc. It is very easy to code in python 
language and anybody can learn python basics in a few hours or days. It is also a developerfriendly language.
2. Free and Open Source:
Python language is freely available at the official website and you can download it from the 
given download link below click on the Download Python keyword.
Download Python
Since it is open-source, this means that source code is also available to the public. So you can 
download it as, use it as well as share it.
3. Object-Oriented Language:
One of the key features of python is Object-Oriented programming. Python supports objectoriented language and concepts of classes, objects encapsulation, etc.
4. GUI Programming Support:
Graphical User interfaces can be made using a module such as PyQt5, PyQt4, wxPython, or 
Tk in python.PyQt5 is the most popular option for creating graphical apps with Python.
5. High-Level Language:
Python is a high-level language. When we write programs in python, we do not need to 
remember the system architecture, nor do we need to manage the memory6. Extensible feature:
Python is a Extensible language. We can write us some Python code into C or C++ language 
and also we can compile that code in C/C++ language.
7. Python is Portable language:
Python language is also a portable language. For example, if we have python code for 
windows and if we want to run this code on other platforms such as Linux, Unix, and Mac 
then we do not need to change it, we can run this code on any platform.
8. Python is Integrated language:
Python is also an Integrated language because we can easily integrated python with other 
languages like c, c++, etc.
9. Interpreted Language:
Python is an Interpreted Language because Python code is executed line by line at a time. like 
other languages C, C++, Java, etc. there is no need to compile python code this makes it easier 
to debug our code. The source code of python is converted into an immediate form called byte
code.
10. Large Standard LibraryPython has a large standard library which provides a rich set of 
module and functions so you do not have to write your own code for every single thing. There 
are many libraries present in python for such as regular expressions, unit-testing, web 
browsers, etc.
11. Dynamically Typed Language:
Python is a dynamically-typed language. That means the type (for example- int, double, long, 
etc.) for a variable is decided at run time not in advance because of this feature we don’t need 
to specify the type of variable.
Attention geek! Strengthen your foundations with the Python Programming Foundation 
Course and learn the basics.
To begin with, your interview preparations Enhance your Data Structures concepts with the 
Python DS Course.
Control statements python
Decision making in python
Chapter 3: PROPOSED SYSTEM
 The proposed system aims to address the inefficiencies and limitations of traditional 
attendance tracking methods through the implementation of an automated face recognitionbased attendance system. By leveraging advanced techniques in image processing and 
machine learning, the system ensures accurate, secure, and time-efficient attendance 
management.
3.1 Key Features of the Proposed System
1. Automated Attendance Management
The system uses facial recognition as the biometric marker for attendance. Facial 
images are captured in real time, processed, and compared against a pre-registered 
database of student faces. Attendance is marked automatically without the need for 
manual intervention.
2. Face Detection and Recognition
 The Viola-Jones algorithm is employed for detecting facial regions in video 
frames captured through a webcam.
 For recognition, Enhanced Local Binary Pattern (LBP) and Principal 
Component Analysis (PCA) are utilized for extracting and matching facial 
features, ensuring high recognition accuracy even in challenging scenarios.
3. Preprocessing for Image Enhancement
Preprocessing steps include:
 Resizing images to a standard dimension of 250x250 pixels to ensure 
consistency.
 Median filtering to reduce noise and improve image clarity.
 Contrast-Limited Adaptive Histogram Equalization (CLAHE) for contrast 
enhancement, enabling better feature extraction.
4. Real-Time Notifications
 Notifications are triggered if a student attempts multiple sign-ins.
 Unregistered students can be added to the database on the spot.
5. Attendance Record Management
Attendance is saved in an Excel sheet for ease of access and analysis. The system
automates the organization of attendance records, providing summary reports as 
required.
6. High Accuracy and Robustness
 The system achieves a recognition accuracy of 100% for high-quality images 
and over 94% for low-quality datasets, ensuring reliability.
 Enhanced algorithms reduce the impact of illumination and resolution 
variations.
7. Scalability and Portability
The system is designed to work across platforms, regardless of the underlying 
operating system or device specifications.
3.2 System Workflow
1. Training Phase
 Facial images of students are captured, preprocessed, and stored in the training 
database.
 Feature extraction using enhanced LBP and PCA is performed, and the extracted 
data is saved in a template file for future recognition.
2. Recognition Phase
Face recognition based attendance system
Dept of CSE VTU CPGS Kalaburgi, 2024-2025 Page 16
 Real-time facial input is captured through a webcam.
 Preprocessing steps are applied to the input image.
 Extracted features are compared with the training database. If a match is found, 
attendance is marked and recorded in real time.
3. Error Handling and Feedback
 The system provides feedback if no match is found, allowing for immediate 
registration.
 Alerts are generated for invalid or duplicate attempts.
3.3 Objectives of the Proposed System
1. Automation: Replace manual attendance tracking with an automated system that 
significantly reduces errors and human effort.
2. Accuracy and Reliability: Ensure high levels of accuracy in identifying individuals 
and recording attendance, even under challenging conditions such as poor lighting or 
image quality.
3. Scalability and Portability: Develop a platform-independent solution that can be 
easily adapted to various environments, including classrooms, offices, and public 
facilities.
3.4 System Features
1. Real-Time Face Detection and Recognition
 Utilizes the Viola-Jones algorithm for detecting faces in real-time.
 Recognizes individuals using a combination of Enhanced Local Binary 
Pattern (LBP) and Principal Component Analysis (PCA) algorithms, 
providing robust performance across different lighting conditions and image 
resolutions.
2. Preprocessing for Enhanced Recognition
Preprocessing ensures consistent input quality by:
 Resizing images to a fixed resolution of 250x250 pixels.
 Applying median filtering to remove noise.
 Enhancing contrast through Contrast-Limited Adaptive Histogram 
Equalization (CLAHE) to improve feature visibility.
3. Feature Extraction and Matching
 Enhanced Local Binary Pattern (LBP) captures detailed facial texture 
information, reducing sensitivity to lighting variations.
 Principal Component Analysis (PCA) reduces data dimensionality, allowing 
efficient storage and faster matching.
 Features are extracted from input images and compared with pre-stored 
templates to identify individuals.
4. Efficient Data Management
 Attendance data is stored automatically in an Excel file.
 Duplicate entries are detected and flagged, ensuring data integrity.
 Provides options for on-the-spot registration of new users if an unrecognized 
face is detected.
5. Real-Time Feedback and Alerts
 The system notifies users about successful recognition, duplicate attempts, or 
the need for registration.
 Visual and textual prompts provide a seamless user experience.
Face recognition based attendance system
Dept of CSE VTU CPGS Kalaburgi, 2024-2025 Page 17
3.5 System Workflow
1. Training Phase
 Facial images of individuals are captured using a webcam and stored in a 
database.
 Preprocessing ensures all images are consistent in size and quality.
 Feature extraction is performed using Enhanced LBP and PCA algorithms, and 
the resulting feature vectors are saved in a training dataset.
2. Recognition Phase
 Real-time input is captured via webcam.
 Preprocessing is applied to ensure compatibility with the training dataset.
 Extracted features are compared with stored data using a matching algorithm.
 If a match is found, the system records the attendance automatically in an Excel 
sheet.
3. Error Handling and Adaptive Registration
 If no match is found, the system provides an option for on-the-spot registration.
 Duplicate sign-ins are flagged to avoid redundant entries.
3.6 Advantages of the Proposed System
1. Improved Accuracy
 High recognition accuracy (100% for high-quality images and 94% for lowquality images).
 Robust against variations in lighting, resolution, and facial expressions.
2. Time Efficiency
 Automates attendance recording, saving significant time compared to manual 
processes.
 Reduces administrative overhead in data entry and management.
3. Scalability
 Designed to handle large datasets, making it suitable for institutions with 
numerous users.
 Platform-independent and compatible with various hardware and software 
environments.
4. Enhanced Security
 Facial recognition ensures that only registered individuals can mark attendance, 
reducing fraud.
 Real-time alerts and notifications enhance system security.
5. Flexibility and Adaptability
 Easily configurable to accommodate new users or modify functionality based 
on specific requirements.
 Can be adapted for diverse use cases, including workplace attendance, access 
control, and event management.
The proposed system represents a paradigm shift in attendance management, integrating 
modern technologies to overcome the drawbacks of traditional systems. Its real-time 
capabilities, accuracy, and scalability make it a versatile and practical solution for institutions 
and organizations. By leveraging facial recognition technology, the system not only simplifies 
attendance tracking but also lays the groundwork for future advancements in automated 
identity verification and data management.
Chapter 6: TESTING
 The system execution is to find the errors that can be defined as testing. It can also be 
defined as the process that defines, isolates, subjects to rectification of defects, and so that the 
customer satisfaction is reached at last with the assurance of the system is free from defects. The 
important component of software testing is the quality assurance and it represents the SRS, 
designing, coding and implementation of the system proposed.
Levels of testing:
 Test Planning:
Test plan is the document that gives the information regarding the procedure that is to be 
followed in performing various tasting on the whole application.
This document involves scope and objectives of the testing, areas that are to be tested and areas 
that should not be tested, scheduling of resources available, the area that need to be automated 
and various tools that are used for testing.
 Test Development:
Test development involves development of test cases and their procedural preparation i.e. 
description of the developed test cases.
Types of testing:
Unit testing:
As the name itself says, the testing is made on small units of the system. A part of the 
system is considered as a unit and its testing is done. If as an example, login page considered; the 
user or the administrator can enter into their respective home pages only after giving the valid 
username and password. This part of validating a system, by considering Login as a unit can be 
said as a unit testing.
Integration testing:
This part of testing deals with the testing procedure. It involves, testing of various 
integrations of several units. It checks whether the system is functioning correctly when two or 
more units are integrated together. This part of testing gives information about order of 
arrangements of various units, integrating modules, systems, sub-systems and the entire system 
as a whole.
Face recognition based attendance system
Dept of CSE VTU CPGS Kalaburgi, 2024-2025 Page 29
System testing:
This testing technique deals with the process of testing the system as a whole. At the end of 
each project, all defects are removed and the interface errors are uncovered in order to achieve 
the good functioning of the whole system. This testing technique can be called as the final part of 
whole testing process.
Test cases:
Input Result conclusion
# Test case 1
Launch webcam using 
opencv
Camera got launched Opencv framework allows 
to access the system 
camera 
# Test case 2
Input training images and 
build the model
Model got build Using feature extraction 
technique, face features 
are extracted and stored in 
.yml file
# Test case3
Compare test image with 
model
Image got recognized Using LBPH algorithm 
test image is compared 
with model and face is 
recognized
Chapter 7: CONCLUSION
 In this system we have implemented an attendance system which can record students’ 
attendance. It saves time and effort, especially if it is a lecture with huge number of students. 
Automated Attendance System has been envisioned for the purpose of reducing the drawbacks in 
the traditional (manual) system. This attendance system demonstrates the use of image 
processing techniques in classroom. This system can not only merely help in the attendance 
system, but also improve the goodwill of an institution
