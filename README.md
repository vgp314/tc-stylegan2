## Teaching StyleGAN to Read: Improving Text-to-image Synthesis with U2C Transfer Learning<br>
Pytorch implementation for reproducing Text-Conditional Stylegan2 (TC-Stylegan2), in the paper Teaching StyleGAN to Read: Improving Text-to-image Synthesis with U2C Transfer Learning, by Vinicius Pereira and Jonatas Werhmann.

![Architecture](./docs/architecture.png)

The core architecture was adapted from [Stylegan3](https://github.com/NVlabs/stylegan3).


![Comparative image](./docs/comparative_fakes_reals.png)


## Requirements

* 64-bit Python 3.8 and PyTorch 1.9.0 (or later). See https://pytorch.org for PyTorch install instructions.
* CUDA toolkit 11.1 or later. 

* Python libraries: see [environment.yml](./environment.yml) for exact library dependencies.  You can use the following commands with Miniconda3 to create and activate your StyleGAN3 Python environment:
  - `conda env create -f environment.yml`
  - `conda activate stylegan3`



