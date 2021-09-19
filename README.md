# FaceDetection
Images are represented in matrix format which is composed of rows and columns.
Each image is made up of pixels. For a color image each pixel is made up of Red, Green and Blue(RGB) colors mixed in different proportions. Total number of information in a color image is: (height of image* weidth of image *3). 3 is the number of channel of a color image which is red, green and blue. For a grey scale image R, G and B are mixed in equal proportion. So the total number of information is equal to (height of image* weidth of image).


In Cascade classifiers, sliding windows having a combination of white and black colors are passed over the images. Final pixel for describing the features is calculated using the formaula (Sum of White Pixel -Sum of Black Pixel). Images are represented by matrix. Each images has a X and Y axis. So , in the matrix the positions of the faces in the images are displayed. For example if a face in an image is represented as array[677,72,68,68], it means that the face in the image is at position (677, 72) where 677 represents the x-axis and 72 represents the y-axis. And the size of the face detected in 68 by 68.
