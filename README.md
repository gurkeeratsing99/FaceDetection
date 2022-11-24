# FaceDetection
Project For INFO 3150

Note : This project has been referenced from carolinedunn/facial_recognition

Step - 1 : Before using this project we will need to add the pictures of the test principle,create a new folder in dataset folder with the desired principle name which will be showed in the program, open the file headshots.py in any text editor and rename the name variable to the same pricliple name which you just created in dataset folder ,run the file headshots.py, this will open up the camera, press spacebar to take a photo each time try to take different angles (prefered to take atleast 8-10 pictures) after you are done taking pictures press the Esc to close.

Step - 2 : Now we have taken the photo dataset of our user, now we need to train our model, run train_model.py, this script will process the images which we took in the previous step, after successful processing close the window (this may take a couple of mins)

Step - 3 : Now to run the face Recognition program run the file called facial_req.py, this will open up the camera and will start finding for the face that the program was trained for in the above steps. If a successfull match is found a frame with the user name will be diplayed otherwise Unknown will be displayed.



Tips: To add multiple faces to the dataset repeat steps 1 and 2
