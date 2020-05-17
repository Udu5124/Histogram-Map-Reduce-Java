# Histogram-Map-Reduce-Java
CSE 6331 : Map Reduce in Java to take pixel values (ie RGB values) as input and give count of each pixel intensity for each color

Project Description: Pixel Histogram

A pixel in an image can be represented using 3 colors: red, green, and blue, where each color intensity is an integer between 0 and 255. 
In this project, you are asked to write a Map-Reduce program that derives a histogram for each color. 
For red, for example, the histogram will indicate how many pixels in the dataset have a green value equal to 0, equal to 1, etc (256 values).
The pixel file is a text file that has one text line for each pixel. 
For example, the line
23,140,45
represents a pixel with red=23, green=140, and blue=45

The necessary details are provided in the project1.txt file.
