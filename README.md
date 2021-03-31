# ByteHole
The detalis of what we are building and how to run the code is given here.

# AI Teach (smart online classes with AI feedback system and air canvas).
# The problem.
The education sector had a major change during this pandemic, most of the regular offline class has changed mode to online. What ever be the mode of teaching, our objective and concern is about the quality of education. With the conversations and discussion with teacher's we find that, how teacher's maintained their quality of teaching is through the feedback that they get from the students, through the medium of vision, by looking at the face of students teacher can understand whether the students grabbed what has been teached.

The problem here with online teaching method is that teachers didn't get this valuable feedback from students, even students are requested to turn on their cameras, it's not possible for a teacher to monitor each student and continue with the class as in a offline mode. Due to the lack of proper feedback from student's the quality of education has dropped significantly.

When having the conversation with the teachers they also shared that they they are lacking a black board, even the teachers who have a touchscreen also said it's difficult for them to write and draw on it.

# Solution
The solution is AI Teach. The new AI based platform for online classes. What we are going to buid: While during an online class on AI Teach platform, each of the students face is absorved by our AI model. Our AI model will detect the face of students and extract the features from the face with that the AI model will analysis the emotions, postures, yawn etc, to predict the state of the students. The teacher will get live report on the activeness of students in the class, so teacher can change the mood of the class accordingly. The AI Teach also has another good feature for Teacher's who want a Black board like experience to write on especially for the one who didn't have a touchscreen/ writting pen, The Air-Canvas. While you are in Air-Canvas the camera will be on and it will detect the movement of your and with that what you draw on the air is there in the canvas too, it's that easy to use.

# Experience our creation
To run our webapp (created using flask) and to see the working of it, Clone the repository, install python and other libraries given in the 'requirements.txt' file. Open the terminal and go to the directory where the code is downloaded. In the terminal type 'python main.py runserver' and that it's you are ready to experiment with our AI model. It's not the final outcome that you will be seeing but an prototype. In this prototype our AI model will detect the face, extract the features and analysis your emotions and show the predicted output realtime. The output will be like this: image
![image](https://user-images.githubusercontent.com/61120485/113183224-68137f00-9271-11eb-9f2e-3e11a5b4c21a.png)


To experience the Air-Canvas on the terminal run code 'python Air-Canvas.py' it's a must try and you will be amazed with the result. On the air canvas screen their is option to change colour of the pen and to erase what have drawn, but it didn't require any physical touch, it's all about your magic gestures. 

The final outcome that we are working on to achieve is 1) First to make browser extension of our model to work on the existing online teaching app like Google meet and our model will analysis the face of each student and give the analysised report live time to teacher. If the teacher want to use the Air-Canvas just, teacher can open the Air-Canvas from the same extension. 2) To develop our on online teaching platform like Google meet with all this added features.
