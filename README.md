# Cartoonizer

In this project we are going to convert normal image to its cartoon version using OpenCV library.
We are using Color space conversion, Median blur, Bilateral Filter and Adaptive thresholding to convert the image to its cartoonized version. All these mentioned steps are applied step by step to convert the image. The image is initially stored in a folder, this folder is given as input in the program.
There is another folder where we get the final product of the image, that is the cartoon version.
We have defined a function to load all these images from the input file with the help of the ‘os’ library
and after applying special effects, store these images in the output folder, which we mention in the code. We have the main function named ‘cartoonify’ which is responsible for applying the special effects so we can get the final images.
