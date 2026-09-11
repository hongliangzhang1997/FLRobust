You can change the default values of other parameters to simulate different conditions. Refer to the config federated.py.


This is the official implementation for the paper "Defending Federated Learning Against Backdoor Attacks via Local Secondary Optimization and  Sparsified-Parameter Inspection".

You can find the paper once it is published.


## Usage

You can easily run the code by executing  federated.py.

### Environment

Our code does not rely on special libraries or tools, so it can be easily integrated with most environment settings. 

If you want to use the same settings as us, we provide the conda environment we used in `env.yaml` for your convenience.

### Dataset

The paper used CIFAR10   CIFAR100   datasets are available on `torchvision` and will be downloaded automatically.

Tiny-ImageNet must be downloaded separately  before running the corresponding experiments.
