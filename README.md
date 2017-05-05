# pytorch-vgg-cifar10
This is the PyTorch implementation of VGG network trained on CIFAR10 dataset 

### Requirements. 
[PyTorch] (https://github.com/pytorch/pytorch)

[torchvision] (https://github.com/pytorch/vision)

### Download the model
The trained VGG model. 92.4% Accuracy [VGG](http://www.cs.unc.edu/~cyfu/cifar10/model_best.pth.tar)

### Evaluation 
	
	
	wget http://www.cs.unc.edu/~cyfu/cifar10/model_best.pth.tar
	python main.py --resume=./model_best.pth.tar -e
	
![alt text](vgg_plot.png)


