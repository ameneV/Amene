This is a python implementation Of Maximum Local Variation-based Unsharp Masking technique for image enhancement. It done in google colab.

Maximum Local Variation-based Unsharp Masking (MLVUM) is an image enhancement technique that aims to increase the local contrast and sharpness of an image. 
It does this by identifying areas with low local variation, which are likely to appear blurry, and then enhancing those areas to make them appear sharper. 
The MLVUM algorithm works as follows: Calculate the local variation for each pixel in the image using a predefined neighborhood size.
Identify the pixels with low local variation, indicating areas that are likely blurry or lacking in detail. Apply an unsharp mask to these identified pixels, 
sharpening them and increasing local contrast. Combine the sharpened areas with the original image to produce the enhanced image.

In this implementation, we use the Laplacian operator to calculate the local variation, and then apply an unsharp mask using the GaussianBlur and addWeighted functions.
Finally, we combine the sharpened areas with the original image to produce the enhanced image.
