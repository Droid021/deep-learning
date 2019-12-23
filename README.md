[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<h1 align="center">
    Deep Learning
   </h1>

This repository contains notebooks and material related to deep learning including Udacity's [Deep Learning Nanodegree program](https://www.udacity.com/course/deep-learning-nanodegree--nd101) and some of the projects done from the program

Some of the materials and projects include: 

* [Generating Human celebrity faces using GANs](https://github.com/styluna7/dl-nanodegree/tree/master/deeplearning-nanodegree/projects/project-face-generation): Implement a DCGAN to generate new images based on the Celeba dataset.

* [Classifiying skin cancer using a CNNs](https://github.com/styluna7/dl-nanodegree/tree/master/deeplearning-nanodegree/dermatologist-ai): Using a pretrained network, a network is trained on images 3 classes of skin cancer. a technique known as **transfer learning**
<img src="https://github.com/styluna7/dl-nanodegree/blob/master/images/skin-cancer.png"/> 

* [Generating TV Scripts using an RNN](https://github.com/styluna7/dl-nanodegree/tree/master/deeplearning-nanodegree/projects/project-tv-script-generation): Using a supplied tv script, an LSTM network is trained to generate text. Here is a sample of the generated text:

<img src="https://github.com/styluna7/dl-nanodegree/blob/master/images/tv-script.png"/> 

# Dependencies

## Configure and Manage Your Environment with Anaconda

Per the Anaconda [docs](http://conda.pydata.org/docs):

> Conda is an open source package management system and environment management system 
for installing multiple versions of software packages and their dependencies and 
switching easily between them. It works on Linux, OS X and Windows, and was created 
for Python programs but can package and distribute any software.

## Overview
Using Anaconda consists of the following:

1. Install [`miniconda`](http://conda.pydata.org/miniconda.html) on your computer, by selecting the latest Python version for your operating system. If you already have `conda` or `miniconda` installed, you should be able to skip this step and move on to step 2.
2. Create and activate * a new `conda` [environment](http://conda.pydata.org/docs/using/envs.html).

\* Each time you wish to work on any exercises, activate your `conda` environment!

---

## 1. Installation

**Download** the latest version of `miniconda` that matches your system.

|        | Linux | Mac | Windows | 
|--------|-------|-----|---------|
| 64-bit | [64-bit (bash installer)][lin64] | [64-bit (bash installer)][mac64] | [64-bit (exe installer)][win64]
| 32-bit | [32-bit (bash installer)][lin32] |  | [32-bit (exe installer)][win32]

[win64]: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86_64.exe
[win32]: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86.exe
[mac64]: https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
[lin64]: https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
[lin32]: https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86.sh

**Install** [miniconda](http://conda.pydata.org/miniconda.html) on your machine. Detailed instructions:

- **Linux:** http://conda.pydata.org/docs/install/quick.html#linux-miniconda-install
- **Mac:** http://conda.pydata.org/docs/install/quick.html#os-x-miniconda-install
- **Windows:** http://conda.pydata.org/docs/install/quick.html#windows-miniconda-install

## 2. Create and Activate the Environment

For Windows users, these following commands need to be executed from the **Anaconda prompt** as opposed to a Windows terminal window. For Mac, a normal terminal window will work. 

#### Git and version control
These instructions also assume you have `git` installed for working with Github from a terminal window, but if you do not, you can download that first with the command:
```
conda install git
```

If you'd like to learn more about version control and using `git` from the command line, take a look at Udacity's free course [Version Control with Git](https://www.udacity.com/course/version-control-with-git--ud123).

**Now, we're ready to create our local environment!**

1. Clone the repository, and navigate to the downloaded folder. This may take a minute or two to clone due to the included image data.
```
git clone https://github.com/styluna7/dl-nanodegree
cd deep-learning
```

2. Create (and activate) a new environment, named `deep-learning` with Python 3.6. If prompted to proceed with the install `(Proceed [y]/n)` type y.

	- __Linux__ or __Mac__: 
	```
	conda create -n deep-learning python=3.6
	source activate deep-learning
	```
	- __Windows__: 
	```
	conda create --name deep-learning python=3.6
	activate deep-learning
	```
	
	At this point your command line should look something like: `(deep-learning) <User>:deep-learning <user>$`. The `(deep-learning)` indicates that your environment has been activated, and you can proceed with further package installations.

3. Install PyTorch and torchvision; this should install the latest version of PyTorch.
	
	- __Linux__ or __Mac__: 
	```
	conda install pytorch torchvision -c pytorch 
	```
	- __Windows__: 
	```
	conda install pytorch -c pytorch
	pip install torchvision
	```

6. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```

7. That's it!

Now most of the `deep-learning` libraries are available to you. Very occasionally, you will see a repository with an addition requirements file, which exists should you want to use TensorFlow and Keras, for example. In this case, you're encouraged to install another library to your existing environment, or create a new environment for a specific project. 

Now, assuming your `deep-learning` environment is still activated, you can navigate to the main repo and start looking at the notebooks:

```
cd
cd deep-learning
jupyter notebook
```

To exit the environment when you have completed your work session, simply close the terminal window.

## Acknowledges
1. Udacity
2. Everyone in deep learning 

## Contact

Twitter - [@darctrac3](https://twitter.com/darctrac3) Droid - vincivenv@gmail.com

Project Link: [Deep Learning](https://github.com/styluna7/dl-nanodegree)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/styluna7/dl-nanodegree.svg?style=flat-square
[contributors-url]: https://github.com/styluna7/dl-nanodegree/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/styluna7/dl-nanodegree.svg?style=flat-square
[forks-url]: https://github.com/styluna7/dl-nanodegree/network/members
[stars-shield]: https://img.shields.io/github/stars/styluna7/dl-nanodegree.svg?style=flat-square
[stars-url]: https://github.com/styluna7/dl-nanodegree/stargazers
[license-shield]: https://img.shields.io/github/license/styluna7/dl-nanodegree.svg?style=flat-square
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/v3nvince
[product-screenshot]: screenshots/travelui1.png
