# Estra
A pipeline to help automate, inform, and improve astrophysical data visualization using machine learning.

A proof of concept visualization of the moon-forming synestia simulation from [Lock et al. (2018)](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1002/2017JE005333).

*Authors:* 
[Patrick D. Aleo](https://astro.illinois.edu/directory/profile/paleo2)

## Description:

Estra is a python pipeline designed to use clustering and dimensionality-reduction techniques to inform astrophysical data visualization in [Houdini](https://www.sidefx.com/products/houdini/). This allows the user to more easily create their own cinematic visualizations without need for a team of visualization artists. The visualizations can be used for simulation prototyping, public outreach, in publications, etc.

Setup:
```
pip install ...
```

Usage:
```
...
```
Example of the Advanced Visualization Lab (AVL) render of the synestia, created by a team of viz artists.
<img src="https://github.com/patrickaleo/estra/blob/master/AVL_final_render_1%25.jpg" alt="AVL_render" width="512"/>

Example of the Estra visualization of the synestia, using a color mapping informed by a Gaussian Mixture Model (GMM) clustering algorithm and a simple, custom shading network detailed in ...  
<img src="https://github.com/patrickaleo/estra/blob/master/Estra_final_render_062119.jpg" alt="Estra_render" width="512"/>
 

## Cite

```
@article{Aleo2019,
  title={Estra: Clustering Methods for Astrophysical Data Visualization in the Moon-forming Synestia Simulation},
  author={{Aleo}, P.~D. and others},
  year={in prep.},
  journal={ApJ},
}
```

Please contact the author for any questions, at paleo2@illinois.edu.
