# Garbage_bin_scanner

A machine learning project to learn how to spot and count
the number of garbage bins on a photo taken from streetview.
I am using google colaboration and matplotlib to achieve this.
I am creating the dataset from my own photos.
<br>
![garabage bins streetview](https://res.cloudinary.com/djunroohl/image/upload/v1700420679/Garabage_bin_scanner/cyhjr6q4lbaxhaxrmvsu.png)

The Bins have all of the same size and color. So to determine where they are located on an image one way could be
to look for the colors of the sides of the bin and the brightest color which is often the topside. From a photoeditor app
I could determine the RGB values value of all sides to be approx:
- shaded side: rgba(71, 90, 57, 1)
- unshaded side: rgba(134, 144, 119, 1)
- topside: rgba(220, 236, 220, 1)

Then the computer vison model YOLO (You only look once) could be used to find and target the bins. 
