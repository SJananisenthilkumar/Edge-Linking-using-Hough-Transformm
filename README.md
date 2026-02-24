# Edge-Linking-using-Hough-Transformm
## NAME : JANANI S
## REG NO : 212223230086
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image

<img width="669" height="541" alt="image" src="https://github.com/user-attachments/assets/ca3a5f74-1ed4-455d-9fcd-b6dd079f75cb" />

<img width="678" height="553" alt="image" src="https://github.com/user-attachments/assets/4211ffc6-49d8-4d9a-877a-7ffd2058df05" />


### Canny Edge detector output

<img width="679" height="552" alt="image" src="https://github.com/user-attachments/assets/df0d3f9d-4349-4319-aff4-500d228735fd" />


### Display the result of Hough transform

<img width="679" height="540" alt="image" src="https://github.com/user-attachments/assets/26f9e86b-e8f5-4961-8093-fd779bab0b1c" />

