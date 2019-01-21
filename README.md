# Oxford Flower Dataset Classifier using Pytorch

This is part of Udacity's **Pytorch Facebook Challenge** where we are required to be able to classify the flower breeds with highest accuracy possible

# Training Steps and Iterations
- Using Pretrained Resnet152 with all layers but the last layers frozen (**Validation accuracy:~93%**)
- Using Pretrained Resnet152 with the last 3 layers unfrozen (**Validation accuracy:~98.8%**)
- Using Pretrained Resnet152 with the last 4 layers unfrozen (**Validation accuracy:~99.1%**)
- Same config as previous but adding using Adam with weight decay (**Validation accuracy: ~99.5%**) (*This is the procedure you will see in the file*)

# License
[MIT](https://opensource.org/licenses/MIT)