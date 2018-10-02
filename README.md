Materials used for ECE 5554 course at VT

## Summary
### Smoothing
- Box filter
- Median filter
- Mean filter (possibly weighted)
- Gaussian filter (must tune std deviation)

### Sharpening
- Unsharp masking: $J(p) = I(p) + \lambda [I(p)-S(p)]$
- Histogram equalization

### Edge Detection
- Discrete derivatives: $I_x = [-1 0 1] \ast I$, $I_y = [-1 0 1]^T \ast I$
- Sobel: Gaussian filter + discrete derivative, $S_x = [-1 0 1]^T [1 2 1]$
- Canny
- Laplacian: edges = zero crossings of $\nabla^2 I = I_{xx} + I{yy}$

### Corner Detection
- Harris
