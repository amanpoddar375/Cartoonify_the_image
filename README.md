# Cartoonify_the_image
Internship task given by Intern'spedia.

The objectives of this Machine learning project was to Cartoonify the image. 

First of all using easygui, we will upload the image, and then the image is converted to a greyscale image. The next two steps are critical in converting images into cartoon images. They are smoothing and then retrieving the edges. In this color, the image is smoothed to give it a cartoon look, and then the edges are recovered and highlighted in the final image. 

Next, we'll create a mask Image. In this case, we use the bilateral filter, which removes noise and smoothens it to some extent. The final step is to add the cartoon effect. We combine our two important steps and finally give a mask-edged image that looks like a cartoon image to the image obtained in the previous step.
