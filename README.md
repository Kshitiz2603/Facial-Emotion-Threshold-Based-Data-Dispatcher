Project Name: Facial Emotion Threshold based data dispatcher
 
Requirements:

opencv_python==4.1.1.26
Keras==2.3.1
pandas==0.25.3
numpy==1.17.4
imutils==0.5.3
scikit_learn==0.22.1

Dataset and Models:

Dataset used: fer2013
Facial detection model: Haarcascade model
Emotion Recognition(CNN): mini_XCEPTION model



## What does Emotion Recognition mean?

Emotion recognition is a technique used in software that allows a program to "read" the emotions on a human face using advanced image processing. Companies have been experimenting with combining sophisticated algorithms with image processing techniques that have emerged in the past ten years to understand more about what an image or a video of a person's face tells us about how he/she is feeling and not just that but also showing the probabilities of mixed emotions a face could has.

Flow of the project:

This project is automated. The application starts from tk_login.py(login page).
1)login page (tk_login.py)
2)Fill the details of the patient(tk_details.py)
3)Agree to the instructions and guidelines(tkt.py)
4)Facial detection and emotion recognition(real_time_video.py)

After certain time limit emotions along with the details of the person is dispatched to the mail.

Text Files:

Statistics.txt: Stores the expression of the user at each frame
details.txt: Stores the details of the patient
emotions.txt: Stores the counter of each expression

