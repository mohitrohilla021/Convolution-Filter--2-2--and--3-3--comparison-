# Convolution-Filter-2-2-and-3-3-comparison

Convolution is the process of adding each element of the image to its local neighbors, weighted by the kernel. 

This is related to a form of mathematical convolution. The matrix operation being performed—convolution—is not traditional matrix multiplication.

For example, if we have two three-by-three matrices, the first a kernel, and the second an image piece, convolution is the process of flipping both the rows and columns of the kernel and multiplying locally similar entries and summing. 
 
If the kernel is symmetric then place the center (origin) of the kernel on the current pixel.

The kernel will overlap the neighboring pixels around the origin. 

Each kernel element should be multiplied with the pixel value it overlaps with and all of the obtained values should be summed. This resultant sum will be the new value for the current pixel currently overlapped with the center of the kernel.

If the kernel is not symmetric, it has to be flipped both around its horizontal and vertical axis before calculating the convolution.
