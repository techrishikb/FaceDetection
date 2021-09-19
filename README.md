# FaceDetection
Images are represented in matrix format which is composed of rows and columns.
Each image is made up of pixels. For a color image each pixel is made up of Red, Green and Blue(RGB) colors mixed in different proportions. Total number of information in a color image is: (height of image* weidth of image *3). 3 is the number of channel of a color image which is red, green and blue. For a grey scale image R, G and B are mixed in equal proportion. So the total number of information is equal to (height of image* weidth of image).


In Cascade classifiers, sliding windows having a combination of white and black colors are passed over the images. Final pixel is calculated using the formaula (Sum of White Pixel -Sum of Black Pixel).
