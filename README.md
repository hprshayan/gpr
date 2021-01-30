This repository contains supplementary files of the paper "A Novel Method for GPR Imaging Based on Neural Networks and Dictionary Learning." It includes two datasets used for training material type determination and image reconstructor models. All datapoints are represented with .npy format, which could be read with numpy package.

epsr_dataset contains b-scans and images of buried objects with different material types.
shapes_dataset contains b-scans and images of buried objects with a reference material type and different shape classes.

Information of buried circles, rectangles, and triangles are presented in file names:

circles: x_y_r.npy where x, y, and r are coordinates and radius in meters

rectangles: x1_y1_x2_y2.npy where x1, y1, x2, and y2 are coordinates of top left and right bottom vertices.

triangles: x1_y1_x2_y2_x3_y3.npy where x1, y1, x2, y2, x3, and y3 are coordinates of triangles vertices.
