<p align="center">
  <img src="https://github.com/Payal2805/FaceTrack/blob/main/Support%20Files/FaceTrack.png" alt="FaceTrack Logo">
</p>

<h3 align="center">AI-Powered Face Recognition Attendance System</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue">
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green">
  <img src="https://img.shields.io/badge/MySQL-Database-orange">
  <img src="https://img.shields.io/badge/License-MIT-yellow">
  <a href="https://github.com/Payal2805/FaceTrack/stargazers">
    <img src="https://badgen.net/github/stars/Payal2805/FaceTrack">
  </a>
</p>

---


# 🛡️ Project Introduction 

## Abstract

FaceTrack is an AI-powered Face Recognition Attendance System designed to automate attendance management using Computer Vision and Machine Learning technologies. The system utilizes OpenCV, Haar Cascade Classifier, and Local Binary Pattern Histogram (LBPH) algorithms to detect and recognize faces in real time, enabling automatic attendance recording without manual intervention.

Built with Python, Tkinter, and MySQL, FaceTrack provides a complete solution for student registration, face dataset generation, model training, attendance tracking, and report management through an intuitive graphical user interface. By replacing traditional attendance methods, the system improves efficiency, enhances accuracy, and eliminates proxy attendance.

FaceTrack demonstrates the practical application of Artificial Intelligence, Computer Vision, Database Management, and Desktop Application Development to create a secure, reliable, and scalable attendance management solution for educational institutions and organizations.

**Index Terms:** Face Recognition, Attendance Management, OpenCV, LBPH, Haar Cascade, Computer Vision, Machine Learning, Python, Tkinter, MySQL, Artificial Intelligence, Real-Time Recognition.

---


## 📅 Project Timeline


**Start Date:** June 2023

**End Date:** January 2024

**Total Time Required:** 8 Months

The project was developed as a complete Face Recognition Attendance Management System, covering student registration, dataset generation, face training, real-time recognition, attendance tracking, and database integration using Python, OpenCV, Tkinter, and MySQL.

---

### Maintainence Team Introduction

| Name                    | GitHub Profile                         | LinkedIn Profile                                               |
| ----------------------- | -------------------------------------- | -------------------------------------------------------------- |
| **Payal Jayant Jadhav** | [GitHub](https://github.com/Payal2805) | [LinkedIn](https://www.linkedin.com/in/payal-jadhav-859192272/) |

<div align="center">

  <img src="https://github.com/Payal2805/FaceTrack/blob/main/Support%20Files/About_Me_best.gif" alt="Introduction GIF" width="800" height="450">

</div>    

---

## 📖 Project Concept & Overview

Maintaining regular attendance is critical for tracking engagement and operational consistency within institutions, organizations, and businesses. Traditional attendance tracking methods—such as manual roll calls, paper-based registers, or card-swiping ID systems—are inherently inefficient, error-prone, and highly vulnerable to unauthorized manipulation. 

The **Face Recognition Attendance System (FRAS)** is a computer vision application designed to replace these outdated tracking systems. By processing real-time video frames and leveraging advanced machine learning classifiers, FRAS instantly detects and cross-references facial features to log student or employee attendance securely, seamlessly, and automatically into a centralized database.

<div align="center">

  <img src="https://raw.githubusercontent.com/Payal2805/FaceTrack/main/Support%20Files/Flow.png"
       alt="Introduction"
       width="800"
       height="300">

</div>

---

## 🌟 Features

- 🎯 Real-time face detection using Haar Cascade classifier  
- 🧠 Face recognition using LBPH (Local Binary Pattern Histogram)  
- 📷 Works with live webcam video stream  
- 👤 Ability to recognize multiple registered users  
- 🔒 Marks unknown faces when confidence is low  
- ⚡ Lightweight and fast processing suitable for low-end systems  
- 💾 Stores trained face data for future predictions  
- 📊 Displays recognition results with confidence scores  

---

## 🎯 Purpose

The main purpose of FaceTrack is to develop a **simple, efficient, and real-time face recognition system using classical computer vision techniques.**

It aims to:

- Automate identity verification using facial features  
- Demonstrate practical implementation of machine learning in vision systems  
- Provide a foundation for attendance systems and security applications  
- Reduce dependency on manual identification methods  

---

## 📌 Scope

The scope of FaceTrack extends to various real-world applications:

- 🏫 Attendance Systems – Automatic student/employee attendance marking  
- 🔐 Security Systems – Access control and surveillance monitoring  
- 🏢 Office Automation – Employee authentication systems  
- 📱 Smart Devices – Integration with IoT-based recognition systems  
- 🎓 Academic Use – Learning and research in computer vision and ML  

---

## 📌 Requirement Analysis

### 🔷 Haar Cascade Algorithm

Haar Cascade is a machine learning-based approach where a cascade function is trained using a large number of:

- Positive images (containing the object)
- Negative images (not containing the object)

The trained model is then used to detect objects in new images.

OpenCV provides pre-trained Haar Cascade classifiers for detecting:
- Faces  
- Eyes  
- Other facial features  

<p align="center">
  <img src="https://raw.githubusercontent.com/Payal2805/FaceTrack/main/Support%20Files/Haar.png"
       alt="Haar Features"
       width="500"
       height="300">
</p>

---

### 🔷 LBPH Algorithm

Local Binary Pattern (LBP) is a texture-based operator that:
- Labels pixels by thresholding their neighborhood  
- Converts results into binary patterns  
- Represents facial features using histograms  

LBPH is widely used for face recognition due to its simplicity and effectiveness.

<p align="center">
  <img src="https://raw.githubusercontent.com/Payal2805/FaceTrack/main/Support%20Files/LBPH.png"
       alt="LBPH Algorithm"
       width="600">
</p>

---

## ⚙️ Justification of Technology Selection

The selection of facial recognition technology for the FaceTrack system is justified for the following reasons:

- 🎯 **Accuracy:** Advanced algorithms provide reliable identification based on facial features  
- 🔐 **Security:** Biometric data is difficult to forge, ensuring strong authentication  
- ⚡ **Efficiency:** Enables real-time attendance and recognition with minimal delay  
- 👤 **User-Friendly:** Easy-to-use interfaces improve accessibility for users  
- 🔗 **Compatibility:** Easily integrates with existing hardware and software systems  
- 📈 **Scalability:** Suitable for both small-scale and large-scale deployments  
- 🚀 **Future-Proofing:** Can be upgraded with advanced AI and deep learning models

---

## 🧩 Module Division

### 🔷 OpenCV
Used for computer vision tasks like face detection and image processing in real-time applications.

### 🔷 NumPy
Provides support for numerical operations and efficient handling of image data using arrays.

### 🔷 Pandas
Used for managing and organizing dataset information in structured tabular form.

### 🔷 Tkinter
Python GUI library used to create the user interface for the FaceTrack system.

### 🔷 Time Module
Used for handling time-related functions such as delays and processing time measurement.

### 🔷 DateTime Module
Used for working with dates and timestamps for logging and tracking system events.

---

## 🚀 Future Enhancements

- 🔬 Integration of deep learning models (CNN, FaceNet) for higher accuracy  
- 📱 Mobile application development for portability  
- ☁️ Cloud-based storage for dataset and model management  
- 🏫 Automated attendance system integration  
- 🎥 Improved performance under varying lighting and face angles  
- 🔐 Enhanced security using multi-factor authentication

---

## 📌 Conclusion 🚀

FaceTrack is a lightweight and efficient real-time face detection and recognition system built using OpenCV, Haar Cascade, and LBPH algorithms. It successfully detects and recognizes faces in real time, demonstrating the practical use of computer vision techniques for identity verification.

The project provides a strong foundation for further development in AI-based security and attendance systems.

---
<div align="center">

### ⭐ If you found this repository useful, consider giving it a star!

FaceTrack - Face Recognition Attendance System

Made with ❤️ by PAYAL JADHAV

</div>

<p align="right">
  <a href="#top">
    <img src="https://img.shields.io/static/v1?label&message=back+to+top&color=87CEEB&style=flat&logo" alt="back to top" />
  </a></p>
