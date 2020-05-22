# Introduction-of-a-picture_cartoonlizing-program
Introducing a program that cartoonlize a real picture
# A programe that cartoonized a picture
## 1. Introduction
   The program is done in matlab and it can make a real photo into  the one that seems like a picture in a cartoon.
   There are 3 major differences between a real photo and a cartoonlized one:
- More prominent edge contour in cartoonlized pictures.
- There are relatively few details in cartoonlized pictures.
- Cartoonlized pictures are more colorful animation.

## 2. Needs
What should be done to cartoonlize a picture:
- Highlighting the edge line.
- Weakening and removing the details.
- Making the image more colorful.

## 3. Solusions
How to realize the needs:
- Use "edge" function to find the edge and subtract the pixels at the edge position from the original image, so that the edge becomes black, forming a "stroke" effect.
- Use "Bilateral filter" to blur only the interior of the area and keep clear edges.
- Increase the saturation to make colors bright.

## 4. Link
https:// github.com/wyfunique/Image_cartoonlization
