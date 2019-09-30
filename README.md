# ai-for-trading
nlp for trading analysis

## Requirement
### Window Anaconda
Install miniconda on your computer, by selecting the latest Python version for your operating system.
Create and activate * a new conda [environment](https://conda.io/projects/conda/en/latest/user-guide/concepts/environments.html).
* Each time you wish to work on any exercises, activate your conda environment!

## Create and Activate the Environment
### Git and version control
<pre>conda install git</pre>

## Create local environment
1. Clone the repository, and navigate to the downloaded folder. This may take a minute or two to clone due to the included image data.
```
git clone https://github.com/udacity/deep-learning-v2-pytorch.git
cd deep-learning-v2-pytorch
```
2. Create (and activate) a new environment, named deep-learning with Python 3.6. If prompted to proceed with the install (Proceed [y]/n) type y.
  ```
  conda create --name deep-learning python=3.6
  activate deep-learning
  ```
3. Install PyTorch and torchvision; this should install the latest version of PyTorch.
4. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```

### Run
```
cd deep-learning-v2-pytorch
jupyter notebook
```
