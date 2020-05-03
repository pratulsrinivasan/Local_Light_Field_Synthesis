## Learning to Synthesize a 4D RGBD Light Field from a Single Image

[Pratul P. Srinivasan](https://people.eecs.berkeley.edu/~pratul/), [Tongzhou Wang](https://ssnl.github.io/), Ashwin Sreelal, [Ravi Ramamoorthi](http://cseweb.ucsd.edu/~ravir/), [Ren Ng](http://www.eecs.berkeley.edu/Faculty/Homepages/yirenng.html/)

In the International Conference on Computer Vision (ICCV) 2017 (Spotlight Oral Presentation)


[Paper](https://arxiv.org/abs/1708.03292), [Video](https://youtu.be/yLCvWoQLnms), [Flowers Dataset (~169 GB)](https://cseweb.ucsd.edu/~viscomp/projects/LF/papers/ICCV17/lfsyn/LF_Flowers_Dataset.tar.gz), [Supplementary Material](https://people.eecs.berkeley.edu/~pratul/pdf/ICCV17_LF_Synthesis_Supplementary.pdf)

Example Input 2D Image

![Example Input 2D Image](https://people.eecs.berkeley.edu/~pratul/lf_synthesis/central.png)

Predicted 4D Ray Depths

![Predicted 4D Ray Depths](https://people.eecs.berkeley.edu/~pratul/lf_synthesis/depth.gif)

Synthesized 4D Light Field

![Synthesized 4D Light Field](https://people.eecs.berkeley.edu/~pratul/lf_synthesis/pred.gif)

Synthesized Synthetic Depth-of-Field (Focused on Flower)

![Synthesized Synthetic Depth-of-Field](https://people.eecs.berkeley.edu/~pratul/lf_synthesis/full.png)


Synthesized Synthetic Depth-of-Field (Focused on Background)

![Synthesized Synthetic Depth-of-Field](https://people.eecs.berkeley.edu/~pratul/lf_synthesis/full2.png)

### Contents

This repository contains:
1) Local_Light_Field_Synthesis.ipynb Jupyter notebook with an implementation of our algorithm. Note that this code may contain slight updates and modifications to the code used in our paper.

### Dependencies

This code depends on a working installation of Tensorflow and basic Python libraries (numpy, scipy, matplotlib).

### Acknowledgments

This work was supported in part by ONR grants N00014152013 and N000141712687, NSF grant 1617234, NSF fellowship DGE 1106400, a Google Research Award, the UC San Diego Center for Visual Computing, and a generous GPU donation from NVIDIA.
