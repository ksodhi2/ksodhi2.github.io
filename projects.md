---
layout: default
title: Projects
permalink: /projects

---

[Resume](./assets/docs/resume.pdf){: .btn}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Experience](/experience.md){: .btn}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Projects](/projects.md){: .btn}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Awards](/awards.md){: .btn}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[LinkedIn](https://www.linkedin.com/in/ksodhi2){: .btn}

# Projects
## OCR++

OCR++ is a desktop application built with C++ and Cinder that transcribes handwritten text on images with an accuracy rate of 89%. Text is predicted using a k-nearest neighbors algorithm I developed using over 10,000 training images from the [EMNIST](https://www.kaggle.com/crawford/emnist) data set. I identified areas with text on the image using the [TextBoxes](https://github.com/MhLiao/TextBoxes) neural network, and then processed images and extracted individual characters using OpenCV. Lastly I created a simple UI using ImGui where users could select one of two options, either transcribe an image from a file (.jpg, .jpeg, .png) or use a webcam to transcribe the video stream live.

Tech Stack: C++, Cinder, OpenCV, ImGui, TextBoxes, Catch2 <br>
[GitHub](https://github.com/ksodhi2/OCR-Plus-Plus)

![UI](../assets/img/UI.jpg "OCR++ UI")
![Typed Image](../assets/img/typed.png "Typed Image Prediction")
![Handwritten Image](../assets/img/handwritten.jpg "Handwritten Image Prediction")

## Gen Ed Finder
Gen Ed finder is an android app which helps UIUC students find classes to take. Users can either find classes based on course attributes or they could search for a course they previously enjoyed to find similar classes. I used the Python machine learning library Scikit-learn to find similarities between classes. Then I created a REST API using Python and Flask to return the results of the similarity model to the app and deployed it on AWS.

Tech Stack: Java, Python, scikit-learn, Flask, AWS, Docker, Firebase <br>
[Android GitHub](https://github.com/ksodhi2/Gen-Ed-Finder) | [REST API GitHub](https://github.com/ksodhi2/GEN-ED-FINDER-REST-API)

![Home](../assets/img/geoffhome.png "Gen Ed Finder home screen")
![Search](../assets/img/geoffsearch.png "Gen Ed Finder Search")

## [Secure And Sure](https://secure-and-sure.netlify.com) [(Overview Video)](http://www.youtube.com/watch?v=1nKYYJoLMGo)
I collaborated with a team of 6 to design Secure&Sure, a web app which securely stores your identification documents for retrieval at any place and any time. We originally created this to serve America’s homeless population, by providing a secure online storage platform for those who lack a reliable physical space to keep their important documents. My primary role on the project was to parse IDs using Azure computer vision so users could easily enter their information on government assistance forms.

Tech Stack: React, Firebase, Microsoft Azure, JavaScript, Netlify <br>
[GitHub](https://github.com/ksodhi2/SecureAndSure)

![Home](../assets/img/securehome.png "Secure For Sure Home Screen")
![Add](../assets/img/secureadd.png "Secure For Sure Profile")

## Hindi Words and Phrases for Kids
This android app was designed to help my younger brother and other small kids learn basic hindi words. There are 8 different categories of words the user can navigate to. When they click on a word they can hear a native hindi speaker pronouncing it.

![Main](../assets/img/hindiapp.png "Hindi App home screen")
![Family](../assets/img/family.png "Hindi App family screen")
