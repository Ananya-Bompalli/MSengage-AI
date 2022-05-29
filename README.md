# AI - The Artificial Eye
## Purpose
3.44 % of the world’s population is visually impaired of whom 0.49% are blind. Spending an entire lifetime in dark, hoping every step taken isn't fatal could be quite tedious. AI aims to make use of rapidly advancing technology for the benefit of blind and make their lives a tiny bit easier and happier.

![home image](https://user-images.githubusercontent.com/106391241/170805667-02ad4c5c-a301-48ce-8c8e-5fd5e5153a06.png)

## Features and Interfaces
The various features of AI are:
- Store new faces
- Face recognition
- Criminal directory
- Emotion detection
- Text recognition

![about image](https://user-images.githubusercontent.com/106391241/170805764-453c535a-d6d2-4921-a2bd-d5097a3bba79.png)

**Store new faces** 

This feature gives an option to store the names and faces of people through manual input and aids in facial recognition in the next encounter of that face.

![input face image](https://user-images.githubusercontent.com/106391241/170805827-14c78170-c48c-4e09-b28e-e14c39eb4b38.png)

![input entry image](https://user-images.githubusercontent.com/106391241/170805828-bd33bc95-efa7-4380-8150-379813464f4d.png)

**Face recognition**

This feature finds if the face shown to the cam is present in the criminal directory first. If the search is affirmative, the voice output would be a cautionary meassage. Else, if the face is a part of face directory, the name of the person is given as voice output. However, if the face isn't part of both the directories, the voice output would be something like - " No known face found". The feature also detects the absence of a face and notifies the same.

![face rec image](https://user-images.githubusercontent.com/106391241/170806074-fa1789b0-225d-4eab-8932-f61aeb27a6f7.png)

**Criminal directory**

This feature works similar to the 'store new faces' feature except the faces taken as input are stored into the criminal directory.

**Emotion detection**

when triggered, the feature produces a voice output of the expression on the face of the listener to the blind. Thus helping them recieve feedback and have a productive conversation.

![face rec image](https://user-images.githubusercontent.com/106391241/170806451-4495808b-ccec-43a2-8900-cc0e609e5440.png)

**Text recognition**

One of the major setbacks of being blind is not being able to read text - be it a sign board or a news article. This feature recognizes text and gives it as voice output to the blind thus enabling them to know what is written.

![text image](https://user-images.githubusercontent.com/106391241/170806682-d48c43f7-20c1-4f64-92d7-c31d5ced5e2f.png)

Here, the output would be the oral message of the sentence - "They said, don't give up on your dreams. So, I went back to sleep."

# Important instructions while using the app

1. Libraries to be imported to the jupyter notebook are:
- tkinter
- PIL
- opencv
- dlib
- cmake
- numpy
- pyttsx3
- face_recognition
- os
- keras
- pytesseract

2. To install tesseract:

Windows

If you have windows, go on this page https://github.com/UB-Mannheim/tesseract/wiki, download and install tesseract 64 bit.

Linux

On Linux you can simply open the terminal and insert the following commands:

sudo apt install tesseract-ocr

sudo apt install libtesseract-dev

If the commands don’t work, you can refer to the Tesseract website page for more instructions: https://tesseract-ocr.github.io/tessdoc/Home.html.

Mac

To install tesseract on Mac use this command:

sudo port install tesseract

If this command doesn’t work, check this page for more instructions: https://tesseract-ocr.github.io/tessdoc/Home.html

3. **While storing the faces in face and criminal directory, ensure that the path of face directory, criminal directory and haar cascade files are given correctly according to their location on your computer. Also note the difference between / and \ while giving the path and change according to the direction in source code and requirement (i.e, retrieval or input)**

![input instructions](https://user-images.githubusercontent.com/106391241/170808490-7a970427-7986-4b03-af76-417320f3259c.png)

![criminal instructions](https://user-images.githubusercontent.com/106391241/170808493-296c53dc-11b2-4ddd-8c8d-206a177be7c3.png)

4.**In face recognition, the paths of face directory and criminal diractory must be given accurately. Note the directions of \ and /. Also make sure that the face and criminal directory folders have no other files (like ipynb checkpoints or any other files) except purely images. If ipynb checkpoints are being created, try to move the folders from notebook to some other location and give the path accordingly.**

![face recognition instructions](https://user-images.githubusercontent.com/106391241/170808690-696ca8b4-ddff-4c6c-b81a-26b14c9dfd1d.png)

5.**In emotion detection and text recognition, maintain correct locations of model.h5, haar cascade file and tesseract files according to their location on local computer**

![emotion instruction](https://user-images.githubusercontent.com/106391241/170808749-6eec0f06-5849-4b8f-a5fa-33ddcdb43021.png)

![text instructions](https://user-images.githubusercontent.com/106391241/170808753-eb2f0510-9811-47f9-8137-1f67b462833c.png)

**This location of tesseract files is the default location that comes while installation**

6. For any queries, feel free to contact me through [LinkedIn](https://www.linkedin.com/in/ananya-bompalli-708031201?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3Bz2p7RkBdS8y%2BwQf1secuYg%3D%3D) or mail - abompalli@gmail.com

## Link to demo video

- [demo video](https://drive.google.com/drive/folders/1nkfsA9SyPh12mW_ExzkYZWrcTvAAcTKf?usp=sharing).


if (youEnjoyed) 

    {
    starThisRepository();
    }










