

In density estimation problem, we have to convert labeled point annotation into density map to use as ground truth for supervise training.

## Basic method

If there are head at pixel x_i in image, we present as delta function
$$
\delta\left(\boldsymbol{x}-\boldsymbol{x}_{i}\right)
$$

So, a image with N head is present by function: 

$$
H(\boldsymbol{x})=\sum_{i=1}^{N} \delta\left(\boldsymbol{x}-\boldsymbol{x}_{i}\right)
$$

We can convolve with Gaussian kernel to make density map

$$
F(\boldsymbol{x})=H(\boldsymbol{x}) * G_{\sigma}(\boldsymbol{x})
$$

#### question I am wonder:

What is x in delta function and H(x) ? If we are going to put the number into H(x), how it going to be ? What is value of x_i ? 
$$
\delta\left(\boldsymbol{x}-\boldsymbol{x}_{i}\right)
$$





[MCNN](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Zhang_Single-Image_Crowd_Counting_CVPR_2016_paper.pdf) 