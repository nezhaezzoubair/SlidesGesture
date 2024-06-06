# SlidesGesture

SlidesGesture is a Python project for controlling presentations using hand gestures captured by a webcam. Using the OpenCV and CVZone libraries, the application recognizes specific gestures to navigate between slides and make annotations in real time. This system is designed to provide an interactive, hands-free presentation experience.


## Description 


Ce projet offre une interface intuitive permettant aux utilisateurs de contrôler les diapositives de présentation via des gestes de la main reconnus en temps réel par une webcam. Les présentateurs peuvent facilement passer d'une diapositive à l'autre, dessiner des annotations et utiliser leur doigt comme pointeur pendant les présentations.
## Main features

*Gesture control*: Navigate between slides with left and right hand gestures, mimicking page flipping.
*Annotation*: Draw on slides using hand gestures, allowing for real-time illustrations or highlighting.
*Pointer mode*: Use the index finger as a virtual pointer to interact with specific elements on the slides.
*Clear Annotations*: Instantly erase drawn annotations with a specific gesture.


## Technologies used
*Python*: Primary language for developing application functionality and logic.
*OpenCV (cv2)*: Webcam access management, image manipulation and gesture recognition for slide control and annotations.
*NumPy*: Efficient management and manipulation of image data for gesture recognition and processing.
*CVZone*: Specialized tools for precise hand tracking and gesture-based interactions.
## Requirements and Configurations 

## Requirements 

* Python 3.x
* Webcam




## Configurations
* Adjust the webcam resolution via the width and height variables.
* Change FolderPath in the main.py file to indicate the directory containing the presentation slides.
* Fine-tune the gestureThreshold, button_delay, etc. settings as needed.
## Deployment

Accessing the project involves a few steps:

*Step 1 :* Clone the Repository : 

bash
  git clone https://github.com/nezhaezzoubair/SlidesGesture.git


*Step 2 :* Set Up Environment and Dependencies
 *Install Python :*  Ensure Python (preferably Python 3.x) is installed on your system.

 *Install Required Libraries :* Navigate to the project directory and install the necessary Python libraries by running -

bash
  pip3 install -r requirements.txt


If there's a requirements.txt file in the project, this command installs all the dependencies needed for the project to run.

*Step 3 :* Configure and Run the Project

*Place Presentation Slides :* Follow the project's instructions to place the presentation slides in the designated folder (ppt or as specified).

*Adjust Configuration (if required) :* Modify any configuration parameters in the code if needed, such as webcam resolution or folder paths.

* *Run the Script :* Execute the Python script that controls the presentation slides - 

bash
  python main.py



* *Interact with the Presentation :* Use the hand gestures as specified in the project's README to control and interact with the presentation slides via the webcam.


*Step 4 :* Quitting the Application
Press the specified keyboard key 'q' to exit or close the application when done.

## Conclusion

The system offers a convenient gesture-based command to swiftly clear annotations. With a specific gesture, presenters can reset the slide, removing any drawn annotations instantly. This functionality ensures a clean slate for new annotations or a clear view of the original slide content.
