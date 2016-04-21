# Software-1
This commit contains files for hog feature extraction and svm.The "svm-hog.py" file
creates vec files.This progra has 2 inputs.When 3rd input is 1 2nd input is
the name of folder containing positive images.When it is -1 the folder is of
negative images.The program creates vec files for images in input
folder/original to input folder/vectors."svm-train.py" creates a dat file from the
vec files."dt.py" detects the objects from tests/original and save output to
tests/heatmap.
