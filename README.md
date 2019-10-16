# PyTorch_examples

### Content:
1. `01_tensor_tutorial.ipynb` - what is PyTorch,  numpy bridge, how to use CUDA

2. `02_autograd_tutorial.ipynb` - explanation how Automatic Differentiation works in PyTorch with examples

3. `03_neural_networks_tutorial.ipynb` - how to define a model, loss function, backprop, update weights

   1. `03_1_Fast_example_MNIST.ipynb` - fast example for classifying task on MNIST dataset 
   2. `03_2_MNIST_with_visualization.ipynb` - example of classifying on MNIST with visualizations, graphs and etc.

4. `04_cifar10_tutorial.ipynb` - example of classifying task on CIfar10 dataset

5. `05_transfer_learning_tutorial.ipynb` - example of transfer learning on bees/ants dataset

6. `06_neural_style_tutorial.ipynb` - Neural Transfer Using PyTorch. Example of applying similar algorithm to Prisma app

7. `07_tensorboard_tutorial-checkpoint.ipynb` - example how to use TensorBoard with PyTorch.

### Difference between TF and PyTorch:

![sad](https://media.proglib.io/wp-uploads/2019/02/Graphs.jpg)

Something more [RUS]: https://proglib.io/p/dl-frameworks/

Something more [ENG]: https://medium.com/@UdacityINDIA/tensorflow-or-pytorch-the-force-is-strong-with-which-one-68226bb7dab4

Something more [ENG]: https://www.youtube.com/watch?v=DmI58jz2i6w

### Dependencies
All examples checked on 
`torch==1.2.0`
`torchvision==0.4.0`

### Useful packages:

1. Model summary:
https://github.com/sksq96/pytorch-summary

2. Progress bar (actually same as `tqdm`):
https://github.com/yusugomori/barbar

### Check if GPU is available:
```torch.cuda.is_available()```
