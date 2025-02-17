# notebook1
Code Snippets on Image Processing (Computer Vision)
1) Thresholding (Binary Thresholding) – A fundamental technique in segmentation that converts grayscale images into binary (black and white) based on a threshold value.1st code applies thresholding, which is a type of point operation in image processing. Specifically, you're using binary thresholding, where pixel values above a certain threshold (200 in your case) are set to 255 (white), and the rest are set to 0 (black).
   
2) The type of image processing used in 2nd is Gamma Correction, which is a form of point-wise intensity transformation.                                                               Use Cases of Gamma Correction:
Enhancing Dark or Bright Images,Correcting Display Response

3) The 3rd image processing technique used is Contrast Stretching, also known as Normalization or Piecewise Linear Contrast Enhancement.Contrast stretching is a point processing technique, meaning it modifies the pixel intensity values independently without considering neighboring pixels.

4) Fourier Transform-based image processing
   Frequency Domain Processing: The image is transformed from the spatial domain (pixel representation) to the frequency domain using the 2D Fourier Transform.
The magnitude spectrum shows how different frequency components contribute to the image.
The Fourier Transform is often used in filtering operations (e.g., low-pass, high-pass, band-pass filters) to remove noise or enhance specific features.
-> The Ideal Low-Pass Filter (ILPF) removes high-frequency components while preserving low-frequency components.
It smooths the image by eliminating sharp edges and noise.
->The Butterworth Low-Pass Filter (BLPF) attenuates high frequencies while preserving lower frequencies.
Unlike the Ideal Low-Pass Filter (ILPF), which has an abrupt cutoff, BLPF provides a smoother transition between low and high frequencies, reducing ringing artifacts.

