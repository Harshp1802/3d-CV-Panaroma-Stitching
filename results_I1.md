### Results on Dataset-1

+ Images here are just for reference. It is suggested to see from the results folder.

1.  Without use of in-built Homography Estimation:

- For this dataset, the images are bit complex. So, the parameter for no. of iterations of RANSAC needs to be increased than the default value to find a best fit. Value I took = **1800**

+ <img src=".\results\I1\stitch_1_2.jpg" width="40%" height="40%" > | <img src=".\results\I1\stitch_1_2_3.jpg" width="40%" height="40%">

:-------------------------:|:-------------------------:

[Stitching of 2 Images | [Stitching of 3 Images]

+ Final Stitching of 4 Images:

    + <img src=".\results\I1\Panorama_1_2_3_4.jpg" width="40%" height="40%" >


2.  Using in-built Homography Estimation:


+ <img src=".\results\I1\stitch_in_built_1_2.jpg" width="40%" height="40%"> | <img src=".\results\I1\stitch_in_built_1_2_3.jpg" width="40%" height="40%">

:-------------------------:|:-------------------------:

[Stitching of 2 Images | [Stitching of 3 Images]

+ Final Stitching of 4 Images:

    + <img src=".\results\I1\Panorama_in_built_1_2_3_4.jpg" width="40%" height="40%">