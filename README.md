# NST-2d-3d
Neural Style Transfer  - 2d to 3d
## Intro

Neural style transfer is an optimization technique used to take two images—a *content* image and a *style reference* image (such as an artwork by a famous painter)—and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.

This is implemented by optimizing the output image to match the content statistics of the content image and the style statistics of the style reference image. These statistics are extracted from the images using a convolutional network.

For example, let’s take an image of this site and try to transfer the styles from that to the picture in Auckland City.

* Artisitic image
<p align="center">
  <img src="https://github.com/thiwankajayasiri/NST-2d-3d/blob/master/Emily_Carr_2-660x330.jpg" width="450" title="Chart-Selection">
</p>

* Real world image

<p align="center">
  <img src="https://github.com/thiwankajayasiri/NST-2d-3d/blob/master/auckland-new-zealand-city-sunset_1591955741.jpg" width="450" title="Chart-Selection">
</p>



