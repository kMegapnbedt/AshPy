# Examples

Runnable training scripts; each one can also be opened in Colab.

| script | shows |
|---|---|
| `classifier.py` | multi-GPU classifier trainer with model selection |
| `unet.py` | the prebuilt UNet model |
| `gans/mnist.py` | conditional GAN on MNIST |
| `gans/bigan.py` | BiGAN training loop |
| `gans/pix2pix_facades.py` | pix2pix on the facades dataset |
| `gans/pix2pix_facades_multi_gpu.py` | the same with a distribution strategy |

Run any script from the repository root, e.g. `python examples/gans/mnist.py`.
