# GUI-Image_Analysis
A GUI tool to analyze optical waveguide efficiency and uniformity via pixel-wise division, colormaps, and percentile threshold masking.

**The downloadable .exe has been uploaded to Releases. You can find it in the sidebar on the right in the main page.

﻿IMAGE ANALYSIS: EFFICIENCY AND UNIFORMITY Developed by Yen-Chi Chung (Angel)

I developed this GUI to make image-based optical performance analysis
more accessible and consistent. It compares measured and reference
grayscale images through pixel-wise division to map relative efficiency
and summarize spatial uniformity.

The tool helps locate high- and low-response regions that a single
average value can hide. It brings the analysis into one interface so
users can evaluate images without editing the underlying scripts.

See the accompanying PPT for the measurement concept, metric definitions,
examples, and user guide.

*********************************************************************************
You can download the images from the “Testing images” folder for testing. In my example images(in "Testing images" folder), the reference image is abbreviated as “ref”, and the measured image as “mea”.

Reference image: captured without the DOE waveguide (projector → camera)
Measured image: captured with the DOE waveguide (projector → DOE waveguide → camera)
You may run the Python script directly or download the standalone .exe app (“Image analysis.exe”), which requires no installation.
