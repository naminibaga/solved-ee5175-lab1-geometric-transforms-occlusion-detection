Download Link: https://assignmentchef.com/product/solved-ee5175-lab1-geometric-transforms-occlusion-detection
<br>



<h1>A. Geometric Transforms</h1>

<ol>

 <li>Translate the given image (pgm) by (<em>t<sub>x</sub></em><em>=</em>3.75,<em>t<sub>y</sub></em><em>=</em>4.3) pixels.</li>

 <li>Rotate the given image (pgm) about the image centre, so as to straighten the Pisa tower.</li>

 <li>Scale the given image (pgm) by 0.8 and 1.3 factors.</li>

</ol>

<h1>B. Occlusion detection</h1>

Given are two aerial images (IMG1.pgm, IMG2.pgm) of an airport parking bay. These images were captured using two cameras placed at different locations and at different instants of time but overlooking the same area. It is known that the images are related by an in-plane rotation and translation. The following point correspondences are given:

<table width="259">

 <tbody>

  <tr>

   <td width="109">Correspondence</td>

   <td width="84">IMG1 (<em>x</em>, <em>y</em>)</td>

   <td width="66">IMG2 (<em>x</em>, <em>y</em>)</td>

  </tr>

  <tr>

   <td width="109">1</td>

   <td width="84">(125,30)</td>

   <td width="66">(249,94)</td>

  </tr>

  <tr>

   <td width="109">2</td>

   <td width="84">(373,158)</td>

   <td width="66">(400,329)</td>

  </tr>

 </tbody>

</table>

Determine the changes in IMG2 with respect to IMG1.

NOTE : Use bilinear interpolation during target-to-source mapping.

NOTE for occlusion detection : Co-ordinate convention followed to represent the above points,

<ol>

 <li>Origin (1,1) at top left corner of the image</li>

 <li><em>x</em>-axis = along the columns of the image</li>

 <li><em>y</em>-axis = along the rows of the image</li>

</ol>

How to read and write pgm images in Scilab?

<ol>

 <li>sci : demo file that shows how to read images into Scilab, write images to a file and display the image files from Scilab.</li>

 <li>sci : the file that contains functions to read (pgmread) and write (pgmwrite) the images. Please use this function in subsequent assignments also.</li>

 <li>To execute a file (say, sci), type the following in Scilab command window:</li>

</ol>

cd ’PATH’ // where PATH is the location of the file exec file.sci

1