# Makemore-2-layer-MLP
We have now a 2-layer MLP (with BatchNorm) and backpropagate through it manually 
without using PyTorch autograd's loss.backward(): 
through the cross-entropy loss, 2nd linear layer, tanh, batchnorm, 1st linear layer, 
and the embedding table. 

The focus for the previous projects was to gain an understanding of how gradients flow
backward through the compute graph and on the level of efficient Tensors, not just 
individual scalars like in micrograd. This helps build competence and intuition around 
how neural nets are optimized and set you up to more confidently innovate on and debug 
modern neural networks.
