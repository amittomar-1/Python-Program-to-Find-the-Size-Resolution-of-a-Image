# Python-Program-to-Find-the-Size-Resolution-of-a-Image
The python program shows the size or the resolution of the image. 

JPEG (pronounced "jay-peg") stands for Joint Photographic Experts Group. It is one of the most widely used compression techniques for image compression.

In this program we provide the path and name of image to calculate the resolution. 

For example, jpeg headers contain information like height, width, number of color (grayscale or RGB) etc. In this program, we find the resolution of a jpeg image reading these headers, without using any external library.

In this program, we opened the image in binary mode. Non-text files must be open in this mode. The height of the image is at 164th position followed by width of the image. Both are 2 bytes long.

We convert the 2 bytes into a number using bitwise shifting operator <<. Finally, the resolution is displayed.
