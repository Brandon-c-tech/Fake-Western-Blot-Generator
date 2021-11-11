# Fake-Western-Blot-Generator
A python program for generating fake WB image. The project is intended to mock the ease with which life science results can be falsified.
## Random bands track generate
Random parameters and mathematical equations were used to generate blots similar to WB bands.
* Use trigonometric functions to add twist to the strip.
* The elliptic equation was used to add distortion to the transverse strip to simulate the edge effect of electrophoresis.
## Noice and Indistinctness (to do)
Make the image more like the real result of the experiment by the following ways.
* The strip is processed with Gaussian blur.
* Add noise to the background.
* Add distortion to the entire image.
## Whole customized WB image generate (to do)
Based on the logarithmic relationship between electrophoretic mobility and relative molecular mass, arbitrary horizontal bands are combined to form the whole result.
