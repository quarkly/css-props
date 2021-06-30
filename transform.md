## transform

The transform CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.


## Values

<transform-function>
One or more of the CSS transform functions to be applied. The transform functions are multiplied in order from left to right, meaning that composite transforms are effectively applied in order from right to left.

none
Specifies that no transform should be applied.


## Examples

transform: translate(30px, 20px) rotate(20deg);
transform: matrix(1.0, 2.0, 3.0, 4.0, 5.0, 6.0);
transform: matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1);
transform: perspective(17px);