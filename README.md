# Object-detection-using-CNN

The objective here is to detect chairs in a room

step 1- Download train and test data from google. I have used 100 training images and 20 test images

step 2 - I am using labelimg as the graphical annotation tool. 
  First download python 3.5 then install PyQt5 and lxml using pip command.
  Install the prebuilt libraries for labelimg from here https://tzutalin.github.io/labelImg/
  Now Open cmd and go to labelImg directory and type th efollowing commands
    pyrcc4 -o resources.py resources.qrc
    python labelImg.py
    python labelImg.py [IMAGE_PATH] [PRE-DEFINED CLASS FILE]
    
  Usage:
  Build and launch using the instructions above.
  Click 'Change default saved annotation folder' in Menu/File
  Click 'Open Dir'
  Click 'Create RectBox'
  Click and release left mouse to select a region to annotate the rect box
  You can use right mouse to drag the rect box to copy or move it
  The annotation will be saved to the folder you specify.

  You can refer to the below hotkeys to speed up your workflow.

  Ctrl + u	Load all of the images from a directory
  Ctrl + r	Change the default annotation target dir
  Ctrl + s	Save
  Ctrl + d	Copy the current label and rect box
  Space	    Flag the current image as verified
  w	        Create a rect box
  d 	      Next image
  a	        Previous image
  del	      Delete the selected rect box
  Ctrl++	  Zoom in
  Ctrl--	  Zoom out
  ↑→↓←	    Keyboard arrows to move selected rect box

step 4 : Now convert the xml file to csv file by executing xml_to_csv.py. Change the file path.
