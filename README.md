<h1 style="background-color:powderblue;"align="center">Gun-Detection-using-Yolov5</h1>
<code>Description</code></br>
-----------------------------------------------------------------------------------------------------------------------------------------------------------<br>
Images folder has images in <code>jpeg</code> format. Labels folder has <code>txt</code> files where in each file, the first line contains the number of objects in the corresponding image and the next lines contain the co-ordinates of the box describing the object.
<br>
In this project i have used yolov5 to detect gun in an image. the dataset is taken from kaggle and the images resolution was irregular. I have used python library "Chitra" 
to resize all the images with their bounding box and applied the yolov5 model. The model achieved better MAP score
<div align="center">
  <img src="img.jpeg" alt="gun image" width="400" height="350" title="Gun">
  </div>
