<link rel='stylesheet' href='../assets/css/main.css'/>

## [Contents](../contents.md)

[LICENSE](LICENSE.md)

---
# Setting Up a Python Machine Learning Development Environment

There are few options
- Option 1: Cloud platforms
- Option 2: Native setup of your machine
- Option 3: Running a docker container
- Finally, get some data.  See our [data page](data.md)

## Option 1: Cloud Platforms
There are popular hosted ML environments.  
This is the quickest way to get going with Python and machine learning.

Supported operating systems : All

### 1A: Google Colab

We recommend [Google Colaboratory](https://colab.research.google.com/).

Pros
- Nothing to setup on your laptop
- Just need a Google account
- Supports majority of ML libraries
- Provides CPU / GPU / TPU runtime environments
- And important of all It is FREE

Cons
- Works great with single notebooks, but including other python modules can be tricky

---

## Option 2: Native Machine Setup

Here we are going to install and setup the computer.

Supported operating systems : Windows, Mac, Linux

### Step 2A: Install Anaconda Python
We highly recommend installing Anaconda Python distribution.  
It has pretty much all the packages needed for ML.

Get it from [here](https://www.anaconda.com/) for your platform

### Step 2B:  Install Additional Packages
The following extra packages are recommended
- jupyterlab

Install as follows using CLI
```bash
    $   conda install jupyterlab
```
Also can be done via Anaconda console.

### Step 2C: Start Jupyter or Jupyterlab
Start as follows
```bash
    $   jupyter lab
```

In browser, go to Jupter page;  Usually at [localhost:8888](http://localhost:8888)


### Step 2D: Test the Setup
Use this notebook to see if your environment is setup
[Testing123](https://github.com/elephantscale/learning-path-for-ML-labs/blob/master/python/testing-123.ipynb) notebook

---


## Option 3: Docker Images
There are variety of Docker images that have fully setup ML environments.  
Follow the instructions for each Docker

- [ElephantScale training image](https://hub.docker.com/r/elephantscale/es-training)


---

## Checklist
You should have access to an python machine learning environment

---

[LICENSE](LICENSE.md)

## [Contents](../contents.md)
