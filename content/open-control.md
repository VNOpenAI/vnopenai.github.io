+++
title = "OpenControl - Python Library for Control System"
image = "/images/open-control.png"
author = "VNOpenAI"
date = 2021-07-05T00:00:00Z
description = "Release Open Control - ."
categories = ["News"]
type = "post"

+++

# Open Control - Python Library for Control System

We've just released Open Control - a python package that implements basic algorithms for analysis and design of optimal feedback controllers.

### Features:

- Classical control methods
- Linear quadratic regulator (``LQR``) computation
- Adaptive Dynamic Programming (``ADP``) for optimal linear/nonlinear control systems
- Off-policy, On-policy learning algorithms for linear/nonlinear systems
- Experience replay algorithms for linear/nonlinear systems (TODO)

# Learn Reinforcement Learning by the tutorial [notebook](https://colab.research.google.com/drive/10mYMDliuOZD5i-YqmD9noOL8JDhC6t3x#scrollTo=E7MYyIKnQDjr) and [examples](https://github.com/VNOpenAI/OpenControl/tree/master/examples) code.

OpenControl provides algorithms for wide range of system dynamics, including classical control module and reinforcement learning control systems with ADP module. For learning purpose, we recommend starting with our example code to [define a system](https://opencontrol.readthedocs.io/en/latest/system.html) and [run the simulation](https://opencontrol.readthedocs.io/en/latest/linCon.html).

## Development

You can check out the latest version of our source code by cloning the repository:

```
git clone https://github.com/VNOpenAI/OpenControl`
```

## Installation

Before all, create a new virtual conda environment and install requirements 

```
pip install requirements.txt
```

You can do minimal installation of OpenControl with

```
pip install OpenControl
```

Check version

```python
python
>>> import OpenControl 
>>> OpenControl.__version__
````

## Documentation 

Please read the lastest version of our documentation [here](https://opencontrol.readthedocs.io/en/latest/intro.html)

## How to contact us

For any question, drop an email at **phi9b2@gmail.com**.

Follow us on our website https://vnopenai.org/.