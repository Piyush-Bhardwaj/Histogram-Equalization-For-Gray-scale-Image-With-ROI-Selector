# Histogram-Equalization-For-Gray-scale-Image-With-ROI-Selector
The histogram in image processing is the techniqu by which
the occurrences of each intensity value in the image is shown. Normally, 
the histogram is a graph showing the population of pixels in an image at each different 
intensity value found in that image. For an 8-bit grayscale image there are 256 different
possible intensities.

Histogram equalization is the method where all gray levels have ideally equally number of pixels.
Histogram equalization increases the dynamic range of the histogram of an image. 
Histogram equalization assigns the intensity values of pixels such that the output image 
contains a uniform distribution of intensities. It improves contrast of the image. Its goal
is to obtain a uniform histogram. This technique can be used on a whole image or just on a part of an image. 
Histogram equalization redistributes intensity distributions.

ALGORITHM  FOR  HISTOGRAM EQUALIZATION

Step 1: Arrange the Gray Levels (rk) in Increasing Order .

Step 2: Count the number of pixels (nk) (ie population) for each Gray level.

Step 3: Calculate the Probability density function (PDF) for each gray levels.

Pr(rk) = n k/n

Step 4: Calculate the Cumulative density function (CDF) for each gray levels.

SK= ∑ PK (rk)

Step 5: Multiply SK  with (L-1) , where L = Number of gray levels = 2^k
k= number of bits.

Step 6: Rounding off the values obtained in step 5.

Step 7: Equate new Gray levels to the number of pixels.
