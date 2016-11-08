# Visualizations of feature importance in the Inception (v1) network

This page shows visualizations of feature importance generated by applying the
technique of **interior gradients** to the [Inception (v1)][incp-paper] object recognition network.

In a nutshell, interior gradients are gradients of counterfactual images constructed
by scaling down the pixel intensities of the original image. Specifically, the
countefactual images are obtained by interpolating between the black image
(baseline) and the original image.

Interior gradients can be directly visualized as an animation (GIF), which shows
how the gradient of the image changes as the pixel intensities are scaled up.
Interior gradients can also be cumulated by integrating them along the scaling
path (from the black image to the original image). The resulting gradients are
called **integrated gradients**. We recommend reading our
[paper][iclr-submission], presently under submission
to ICLR 2017, for more details.

Below are some visualizations of interior gradients (as a GIF) and integrated
gradients for some images from the ImageNet object recognition dataset. For
comparison, we also show a visualization of the gradients at the actual image.

## Image: 8e570672510267d3
![8e570672510267d3](/Visualizations/IntegratedGradients/8e570672510267d3.jpg
![8e570672510267d3](/Visualizations/Gifs/8e570672510267d3.gif)
## Image: 70bfca4555cca92e
![70bfca4555cca92e](/Visualizations/IntegratedGradients/70bfca4555cca92e.jpg
![70bfca4555cca92e](/Visualizations/Gifs/70bfca4555cca92e.gif)
## Image: 700a04c5c2ca6e80
![700a04c5c2ca6e80](/Visualizations/IntegratedGradients/700a04c5c2ca6e80.jpg
![700a04c5c2ca6e80](/Visualizations/Gifs/700a04c5c2ca6e80.gif)
## Image: 80c64f2e27f8784a
![80c64f2e27f8784a](/Visualizations/IntegratedGradients/80c64f2e27f8784a.jpg
![80c64f2e27f8784a](/Visualizations/Gifs/80c64f2e27f8784a.gif)
## Image: c0a9ce885a9c26bc
![c0a9ce885a9c26bc](/Visualizations/IntegratedGradients/c0a9ce885a9c26bc.jpg
![c0a9ce885a9c26bc](/Visualizations/Gifs/c0a9ce885a9c26bc.gif)
## Image: 1bd6987fa9219dec
![1bd6987fa9219dec](/Visualizations/IntegratedGradients/1bd6987fa9219dec.jpg
![1bd6987fa9219dec](/Visualizations/Gifs/1bd6987fa9219dec.gif)
## Image: 2587b0bd7d764bd9
![2587b0bd7d764bd9](/Visualizations/IntegratedGradients/2587b0bd7d764bd9.jpg
![2587b0bd7d764bd9](/Visualizations/Gifs/2587b0bd7d764bd9.gif)
## Image: a2c980be2b5d464d
![a2c980be2b5d464d](/Visualizations/IntegratedGradients/a2c980be2b5d464d.jpg
![a2c980be2b5d464d](/Visualizations/Gifs/a2c980be2b5d464d.gif)
## Image: 7bcfe0265ad6a2b5
![7bcfe0265ad6a2b5](/Visualizations/IntegratedGradients/7bcfe0265ad6a2b5.jpg
![7bcfe0265ad6a2b5](/Visualizations/Gifs/7bcfe0265ad6a2b5.gif)
## Image: 7f12674c6943381d
![7f12674c6943381d](/Visualizations/IntegratedGradients/7f12674c6943381d.jpg
![7f12674c6943381d](/Visualizations/Gifs/7f12674c6943381d.gif)
## Image: 7f59ece15328c57d
![7f59ece15328c57d](/Visualizations/IntegratedGradients/7f59ece15328c57d.jpg
![7f59ece15328c57d](/Visualizations/Gifs/7f59ece15328c57d.gif)
## Image: 82262660db12ad85
![82262660db12ad85](/Visualizations/IntegratedGradients/82262660db12ad85.jpg
![82262660db12ad85](/Visualizations/Gifs/82262660db12ad85.gif)
## Image: 82ba0b4b5bb0f7d6
![82ba0b4b5bb0f7d6](/Visualizations/IntegratedGradients/82ba0b4b5bb0f7d6.jpg
![82ba0b4b5bb0f7d6](/Visualizations/Gifs/82ba0b4b5bb0f7d6.gif)
## Image: 83abcb73307791e8
![83abcb73307791e8](/Visualizations/IntegratedGradients/83abcb73307791e8.jpg
![83abcb73307791e8](/Visualizations/Gifs/83abcb73307791e8.gif)
## Image: ba024e2cc38f0704
![ba024e2cc38f0704](/Visualizations/IntegratedGradients/ba024e2cc38f0704.jpg
![ba024e2cc38f0704](/Visualizations/Gifs/ba024e2cc38f0704.gif)
## Image: f33412087d9c224e
![f33412087d9c224e](/Visualizations/IntegratedGradients/f33412087d9c224e.jpg
![f33412087d9c224e](/Visualizations/Gifs/f33412087d9c224e.gif)
## Image: 2587b0bd7d764bd9
![2587b0bd7d764bd9](/Visualizations/IntegratedGradients/2587b0bd7d764bd9.jpg
![2587b0bd7d764bd9](/Visualizations/Gifs/2587b0bd7d764bd9.gif)
## Image: 5832f36306fb3d66
![5832f36306fb3d66](/Visualizations/IntegratedGradients/5832f36306fb3d66.jpg
![5832f36306fb3d66](/Visualizations/Gifs/5832f36306fb3d66.gif)
## Image: 92445d6529368418
![92445d6529368418](/Visualizations/IntegratedGradients/92445d6529368418.jpg
![92445d6529368418](/Visualizations/Gifs/92445d6529368418.gif)
## Image: 69e36e11e9ea9671
![69e36e11e9ea9671](/Visualizations/IntegratedGradients/69e36e11e9ea9671.jpg
![69e36e11e9ea9671](/Visualizations/Gifs/69e36e11e9ea9671.gif)
## Image: fff0b93993175fb2
![fff0b93993175fb2](/Visualizations/IntegratedGradients/fff0b93993175fb2.jpg
![fff0b93993175fb2](/Visualizations/Gifs/fff0b93993175fb2.gif)

[incp-paper]:http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Szegedy_Going_Deeper_With_2015_CVPR_paper.pdf
[iclr-submission]:http://104.155.136.4:3000/pdf?id=rJzaDdYxx
