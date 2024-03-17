"# Face-Detection-with-Voice" 


The Project is being divided into three Parts: 

1. Face-Detection -
2. Training the Model
3. Recognizing the faces

This Repository consists of Three Python files responsible for the Face-Recognition along with the two extra python files which was created for just testing the camera module using the cam.read() function. 

Please find the steps and the detailed information about the Python files respectively:

Firstly, we would be asking the camera module to open the camera and to read the face of the person next in-front of the camera and would be asking to capture certain counts of the frames and store it to the some directory.  
  Create the Directory called as a "Dataset" under the same Project and assigned the path of the directory to the python file to write over it the images captured.



Secondly, When we are done with capturing the face and stored few of the frames of it into the dataset-directory thereby we would be requiring the images to get trained which is known as  "Training the Model" and converting it into the YML type of file. So in this case we would be converting the images into the YML language and would be asking the system to create a model type of YML in  my case I have used trainer.py file and converting into the trainner.yml type of the file which is getting saved into the trainner folder again which need to be created locally within the same project and assing the path into the trainer.py file while coding. 


Lastly, we need to run the Recognizer.py file which would be helping us to recognizing the faces based upon the ID's and with the help of the Array Index-Concept Id would is gonna used as a ndex value and would be writing the name which is present on that specific index value on your screen. 

***Ehancement****
Added the voice module into it, and as a function the person whose name is getting displayed on the screen it would be keep on saying the name of the Person until the execution is not stopped or the object is not getting removed from the camera.

****Used Python Text-to-SPeech- Package "Pyttsx3"***
>>>Import pyttsx3
>>>engine = engine.pyttsx3.init()
>>>engine.say()
>>>engine.runAndWait()

The above few lines of the code help us to initalize the sound engine and it says the same which is being passed as a "Argument" for the engine.say("Arguments")

****It was great Experience to develop this project and learned a lot to work on the different section of the python packages and the modules. 



