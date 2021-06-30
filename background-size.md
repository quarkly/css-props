## background-size

The background-size CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.


## Values

contain
Scales the image as large as possible within its container without cropping or stretching the image. If the container is larger than the image, this will result in image tiling, unless the background-repeat property is set to no-repeat.

cover
Scales the image as large as possible to fill the container, stretching the image if necessary. If the proportions of the image differ from the element, it is cropped either vertically or horizontally so that no empty space remains.

auto
Scales the background image in the corresponding direction such that its intrinsic proportions are maintained.

<length>
Stretches the image in the corresponding dimension to the specified length. Negative values are not allowed.

<percentage>
Stretches the image in the corresponding dimension to the specified percentage of the background positioning area. The background positioning area is determined by the value of background-origin (by default, the padding box). However, if the background's background-attachment value is fixed, the positioning area is instead the entire viewport. Negative values are not allowed.

## Examples

background-size: cover;
background-size: contain;
background-size: 50%;
background-size: 3.2em;