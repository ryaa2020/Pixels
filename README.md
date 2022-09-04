# Pixels

# Description

I discover the art of Pixels with these two projects. The first is Steganography and the second is Image Filters! 

* Steganography
  * Steganography is the practice of embedding hidden messages or codes within another message - or image, in our case. 
  * I first extract a message that has been steganographically embedded into the lowest order of its bits (desteganographize). Next, I take an image and message and return a copy of the image, but with the least-significant bits of some/all of its pixels changed to hold the message, one bit at a time! 
  
* Image Filters
  * An "image filter" describes a transformation from an input image (or several) to an output image (or several) -- by manipulating the pixels themselves.
  * One-image filters: I design one rgb-based filter and one hsv-based filter. Each takes in a single image, transforms its pixels in an unusual way and outputs the result. 
  * Two-image filters: I design a rgb-based two-image filter and one hsv-based two-image filter. Each takes in two images, transforms their pixels in an unusual way so that each image has a "role" in the output somehow -- and outputs the result.
