# ELEG5491 A2 Programming - CNN on CIFAR

A simple CNN implementation for image classification. We use PyTorch framework and the installation is detailed on the 
[official website](http://pytorch.org/).

## How to submit your code

Please write an `.ipynb` file including all your code/figure/necessary(and brief!) comments. An example of iPython notebook is [here](https://github.com/pytorch/tutorials/blob/master/Reinforcement%20(Q-)Learning%20with%20PyTorch.ipynb). The installation of python notebook is [here](http://jupyter.readthedocs.io/en/latest/install.html).

You can use Amazon AWS web service to launch GPU mode if you do not have it in local computer.
Maximum reimbursement of 20 USD per person at the end of the course. 
**Remember** to close the instance every time you log off. A tutorial on Mar 10 will have some cover to using AWS.

Submit your notebook file to the elearning-system before A2 deadline. **NOTE** that the derivation of theory part in Problem 5 has to be written alongside with other problems; no need to write it again in the notebook. 

[UPDATE]
The demo code has some confusion part:

- In python notebook, you can not parse arguments via `argparse`. Just use fixed (and well tuned) parameters in your submission, removing the `parser` part in the demo.

- The [loss](http://pytorch.org/docs/nn.html#torch.nn.CrossEntropyLoss) in the demo may be misleading from the cross entropy loss. Think about this and decide which one is the correct version.
