# Face Recognition
A facial recognition system is a technology capable of identifying or verifying a person from a digital image or a video frame from a video source. There are multiple methods in which facial recognition systems work, but in general, they work by comparing selected facial features from given image with faces within a database. It is also described as a Biometric Artificial Intelligence based application that can uniquely identify a person by analysing patterns based on the person's facial textures and shape.

# What the project does?
Project contain a python file named face_recognition.py that has the code to recognise the face of any person.
While running that python file the camera can recognise the entered face photos of any person.

# Why the project is useful?
The project has a vast application.
It can be used to take attendance in classes,offices,any institutes. It reduces the need for manual labour which is prone to human errors and time consuming.

It can be used for security checks and accessing any document.

It can be used for criminal identification etc.,

# How users can get started with the project?
face_recognition.py file has the code to recognise the face of any person.You simply have to load the photo and give the name you want to see if your face is recognised.Like in my case I loaded one of my photo by giving path["C:/Users/AJAY/Desktop/adi1.jpg"] of that photo:-

 aditya_image = face_recognition.load_image_file("C:/Users/AJAY/Desktop/adi1.jpg")
 
 aditya_face_encoding = face_recognition.face_encodings(aditya_image)[0],  and here I encoded that variable aditya_image in which I loaded  my image.
 
 known_face_encodings = [
    aditya_face_encoding
]
Here in known_face_encodings[] list you can write the variable you created for encodings.

known_face_names = [
    "Aditya Surana"
]

Here in known_face_name[] list you can add your name you want to see while camera is recognising you.

# Who maintains and contributes to the project?
Created and managed by
# ADITYA SURANA.
Thanks to google.

