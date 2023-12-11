Note: To reduce the file size i cleared my all outputs, so anyone who wants to see results can open it and run all cells.

The Canny edge detection algorithm comprises five essential steps. First, it starts with noise reduction, achieved by applying Gaussian blur to the input image. Following this, the gradient of the image is calculated in both the x and y directions using Sobel operators. The subsequent step involves non-maximum suppression, where only local maxima in gradient magnitude are retained, eliminating non-maximum values. Subsequently, a double thresholding process is implemented, categorizing edges as strong, weak, or non-edges based on gradient magnitude. Finally, the algorithm performs edge tracking by hysteresis, connecting weak edges to strong edges, resulting in coherent and accurate edge detection in the image.

1. RESULT :

After applying all the steps in this edge detection code, the final result i got is an image where prominent edges are highlighted, and weaker edges and noise are suppressed. This result is essentially a binary image where edge pixels are set to white, and non-edge pixels are set to black.



2. What i learned:

In performing edge detection, I have observed that it is a multi-step process involving image preprocessing, gradient calculation, thresholding, and edge tracking. Careful parameter selection is crucial to highlight desired edges while suppressing noise, and results vary based on threshold values and image characteristics.



3. Cause-and-effect relationships of data preprocessing:

Firstly, noise reduction techniques, such as smoothing their are different types of function to so such as gaussian, median, bilateral, remove pixel-level fluctuations, making it easier for the tracking algorithm to focus on genuine edges.
Secondly, gradient calculation methods, applied during preprocessing, provide valuable information about edge directions and strengths, guiding the tracking process.



4. Change of values in edge detection variable:

Brightness and Contrast: Increasing brightness and contrast can make edges more pronounced, enhancing their visibility in the image. Conversely, decreasing these values may soften edges, making them less distinct.

Resize: Resizing the image can affect edge detection. Upscaling can introduce artifacts and make edges thicker

Threshold Values: Higher threshold values in edge detection lead to greater selectivity, emphasizing only the strongest edges and reducing noise. Lower thresholds capture weaker edges and increase sensitivity but may also detect noise.


