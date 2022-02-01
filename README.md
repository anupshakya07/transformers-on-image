# Using the Transformer Model on Image Data

## Abstract
Pure transformer-based applications has been very limited in computer vision tasks. For the vision transformer to compete with the convolution-based models, it needs to be robust to commonly occurring noise and perturbations. We present a controlled study of the robustness of the Vision Transformer when subjected to different types of noise. Further, we also show how even the simplest data augmentation techniques can help the model generalize and perform better.

## Requirements
- absl-py>=0.12.0
- chex>=0.0.7
- clu>=0.0.3
- einops>=0.3.0
- flax>=0.3.5
- ml-collections==0.1.0
- numpy>=1.19.5
- pandas>=1.1.0
- tensorflow-cpu>=2.4.0
- tensorflow-datasets>=4.0.1
- tensorflow-probability>=0.11.1
