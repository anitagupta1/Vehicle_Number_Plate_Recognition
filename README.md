# Vehicle_Number_Plate_Recognition

Number Plate Recognition System is a car license plate identification system made using OpenCV , EasyOCR , imutils ,numpy , matplotlib in python. It can be used to detect plate no. from image.
Number Plate recognition, also called License Plate recognition using image processing methods is a potential research area in smart cities and the Internet of Things. An exponential increase in the number of vehicles necessitates the use of automated systems to maintain vehicle information for various purposes

# Approach
1>   Find all the contours in the image.
2>   Find the bounding rectangle of every contour.
3>   Compare and validate the sides ratio and area of every bounding rectangle with an average license plate.
4>   Apply image segmentation in the image inside the validated contour to find characters in it.
5>   Recognize characters using an OCR.
