# pyopenset

Pyopenset is a package that implements the methodology described in the paper: Hyperspherical embedding for novel class classification: https://arxiv.org/abs/2102.03243

It allows a easy and intuitive way to add novel classes to a pretrained model without requiring further optimization, new classes will always be added after the last.

So for example if your model has 10 neurons each for a single class ,the new class would be associated with neuron 11.

We also provide functions for the disjoint scenario, and how to best use then is presented in the tutorial notebook

Note that current implementation only supports softmax activation functions on the last layer.
