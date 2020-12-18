# Demos

Each folder contains a separate demo. (Open this file [on github](https://github.com/juliangaal/facial_recog) for the best viewing experience.)

## First Order Model

Demo for [First Order Model](https://github.com/AliaksandrSiarohin/first-order-model). Can be run on *CPU or GPU*. Training on CPU takes 15-30 mins (15 mins on Desktop class PC).

#### Prerequisites

* git installed
* ffmpeg installed for video creation (apt install ffmpeg, brew install ffmpeg, windows idk)

#### Linux and Mac

```
conda env create -f fom.yml
conda activate fom
jupyter notebook
```

#### Windows

```
conda env create -f fom_windows.yml
conda activate fom
jupyter notebook
```

If you run into any issues, try creating an environment from scratch

```
conda env create -n fom python=3.6
pip install -r requirements.txt
jupyter notebook
```

## StyleGAN1 Demo 

Demo for [StyleGAN](https://github.com/NVlabs/stylegan). GPU support only. No Mac Support.

***Strong* Recommendation: Use [Google Colab](https://colab.research.google.com)** and simply upload the notebook to get started. Google Colab is
* the only environment we could test to the full extent (StyleGAN1 and StyleGAN2)
* the chance is very high that your GPU (if any) doesn't have enough memory (we hit the limits on local installation)

##### Local Installation: Prerequisites

* GPU support only 
* ffmeg installed for video generation
* Cuda 9.0+
* cuDNN 7.3.1+

#### Linux

#### Windows

## StyleGAN2

Demo for [StyleGAN2](https://github.com/NVlabs/stylegan2). GPU support only. No Mac support.

***Strong* Recommendation: Use [Google Colab](https://colab.research.google.com)** and simply upload the notebook to get started. Google Colab is
* the only environment we could test to the full extent (StyleGAN1 and StyleGAN2)
* the chance is very high that your GPU (if any) doesn't have enough memory (we hit the limits on local installation)

##### Local Installation: Prerequisites

* GPU support only 
* ffmeg installed for video generation
* Cuda 10.0
* cuDNN 7.5

#### Linux

```
conda env create -f stylegan2.yml
conda activate stylegan2
jupyter notebook
```

#### Windows

```
conda env create -f stylegan2_windows.yml
conda activate stylegan2
jupyter notebook
```

If you run into any issues, try creating an environment from scratch

```
conda env create -n stylegan2 python=3.6
pip install -r requirements.txt
jupyter notebook
```

##### Known Issues
* Windows: MSCV Compiler error, solution [here](https://github.com/a312863063/generators-with-stylegan2/blob/master/README_EN.md#common-problem-under-windows-could-not-find-msvcgccclang-installation-on-this-computer-how-to-solve-it)

### Troubleshooting
If you run into trouble, make sure to *include your OS, OS Version and Python in the bug report in the forum.*
