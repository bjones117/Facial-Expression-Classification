# Facial Expression Classification

I used the FER 2013 data which included 7 classes of facial expressions:
  -Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise
  -There are about 29000 training images and around 7000 validation images
  
How everything works together is as follows:
  -Training model was developed in Jupyter Notebook
  -Python script was created to output the model
  -Python script "camera.py" gathers the live camera feed and converts to frames
  -Python script "main.py" pulls everything together to run using Flask app

To run the model, you need to just run python main.py in cmd prompt and go to the URL.
