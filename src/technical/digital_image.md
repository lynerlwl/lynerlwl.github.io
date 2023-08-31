An image is a 2D array of numbers ranging from some minimum to some maximum.

Images is a function $I$ of $x$ and $y$: $I(x,y)$, which xy is the pixel's position.

Color images as functions: $f(x,y) = [r(x,y)\\ g(x,y)\\ b(x,y)]$.
f: [x_1, x_2] x [y_1, y_2] -> [_, _] (intensity)
f: R x R -> R

A 3-channel color image is a mapping from a 2D space of locations to a 3D space of color intensity values.
f: R x R -> R^3

For digital images, we typically operate on discrete images, which (i) sample 2D space on a regular grid and (ii) quantize each sample that round the number to nearest integer.

Image thus represented as a matrix of integer values.

If we visualise the image using plot, we can see the intensity is arranged in a way that higher intensity having higher amplitude. So, high-frequency signal means those having high intensity. Then high-pass filter that keep the high intensity pixel is sharpening, while low-pass filter is bluring.