# FlowNet: Learning Optical Flow with Convolutional Networks :- 

Pytorch implementation of FlowNetS

## Abstract :- 
Convolutional neural networks (CNNs) have recently
been very successful in a variety of computer vision tasks,
especially on those linked to recognition. Optical flow estimation has not been among the tasks where CNNs were successful. In this paper we construct appropriate CNNs which
are capable of solving the optical flow estimation problem
as a supervised learning task. We propose and compare
two architectures: a generic architecture and another one
including a layer that correlates feature vectors at different
image locations.
Since existing ground truth datasets are not sufficiently
large to train a CNN, we generate a synthetic Flying Chairs
dataset. We show that networks trained on this unrealistic
data still generalize very well to existing datasets such as
Sintel and KITTI, achieving competitive accuracy at frame
rates of 5 to 10 fps.

## Architecture :- 
![image](https://user-images.githubusercontent.com/76057253/137062340-97985759-a699-4ed0-a011-45b1d81c1f46.png)


### Refinement Layer :- 
![image](https://user-images.githubusercontent.com/76057253/137062380-3f498eda-e8b8-46d0-a00e-766368fad31a.png)



```
@misc{fischer2015flownet,
      title={FlowNet: Learning Optical Flow with Convolutional Networks}, 
      author={Philipp Fischer and Alexey Dosovitskiy and Eddy Ilg and Philip Häusser and Caner Hazırbaş and Vladimir Golkov and Patrick van der Smagt and Daniel Cremers and Thomas Brox},
      year={2015},
      eprint={1504.06852},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
