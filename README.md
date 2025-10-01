Dataset:

Total Images: 157

Generation Process:

All possible combinations of Modi script vowels, consonants, and matras were generated.

Each combination was converted into a black-and-white image.

Segmentation Pipeline

The segmentation process consists of several steps:

Grayscale Conversion:

All 157 images are converted into black-and-white format for processing.

Shirorekha Removal:

Using thresholding, continuous white lines (pixel value = 255) are detected and removed.

This eliminates the horizontal line (shirorekha) commonly present in Modi script.

Bounding Box Extraction:

Sliding window technique is used to detect black pixels.

Vertical and horizontal movements are used to detect character boundaries.
Recognition and training:
From segmentation we get each alphabetical image and performed text recognition which is classfication using modi char dataset which has alphabets along with their labels.


Bounding boxes are drawn around individual characters.

This approach allows effective segmentation of Modi script characters for further recognition or processing.
