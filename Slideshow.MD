# Slideshow
![Screenshot from image](docs/Slideshow-screenshot-01.png)
## Purpose - Display a slideshow and allow it to be edited in different ways

### Details
Given a simple and incomplete implementation of the Slideshow program I added or completed the following features.

### Editing
+ Display the list of thumbnail images. The thumbnails should be displayed left to right, in COLUMNS columns.
+ Highlight the currently selected image (eg, by drawing a red rectangle around it).
+ Enable the user to add a new image before the currently selected image.
+ Enable the user to delete the currently selected image, and to remove all images.
+ Enable the user to move the currently selected image to the left, to the right, to the beginning, or to the end of the list.
+ Enable the user to change which image is selected (see the hints in the doKey method).
+ Enable the user to add a new image file name after the currently selected image
+ Enable the user to reverse the order of the images in the list, and to shuffle them randomly. (Look for useful methods in the Collections class.)
+ Enable the user to use the mouse to select an image or to move an image to another position in the list.
### Running
+ Complete the runShow method so that it starts a loop to repeatedly display the currently selected image then, after one second, move to the next image.
+ Complete the editShow method to stop the show running, and display the list of all thumbnails again.
