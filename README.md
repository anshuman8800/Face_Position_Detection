# Face_Position_Detection

Problem
Predict the class level(i.e. Left side, right side or in-front) of the face
We had given the coordinates of various face’s part of the face   (like eyes, nose, mouth etc) and by this, we have to predict the face direction either it is on left side or right side or infront.


Literature Survey
Paper Sources : https://ieeexplore.ieee.org/search/searchresult.jsp?newsearch=true&queryText=face%20detection%20using%20ml%20algorithm


Dataset Analysis
A reduced feature set for driver head pose estimation.
606 samples of 640×480 pixels each.
A set of labels assigning each image into 3 possible gaze direction classes are given. 
Class 1 : The first class is the looking-right class and contains the head angles between -45º and -30º. 
Class 2 : The second one is the frontal class and contains the head angles between -15º and 15º. 
Class 3 : The last one is the looking-left class and con angles between 30ºtains the head and 45º. 


Result Analysis and Conclusion
Comparing the result of all possible algorithm implemented in this project, Logistic Regression with K-fold perform better than other


References

https://cs231n.github.io/python-numpy-tutorial/
https://github.com/ageitgey/face_recognition
https://www.ini.rub.de/PEOPLE/wiskott/Bibliographies/FaceRecognition.html