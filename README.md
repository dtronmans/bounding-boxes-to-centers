# bounding-boxes-to-centers
Code for changing bounding box annotations to single-pixel centers

This Jupyter notebook was used to convert bounding box annotations to single-pixel center labels. This was done by getting the center of each bounding box.

Original data: one line for each object in each image, in the form [filename, xmin, ymin, width, height]
Modified data: one line for each image, in the form [filename, count, [xcenter, ycenter]]
