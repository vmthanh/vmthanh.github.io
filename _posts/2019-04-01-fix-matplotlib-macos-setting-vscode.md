---
title: Fix cannot use Matplotlib in MacOS - Configure VSCode to recognize VirtualENV 
layout: post
excerpt: "Fix Matplotlib with MacOS and configure VSCode" 
tags:
- code
- matplotlib
- virtualenv

---
## 1. Fix Matplotlib with MacOS
Here is my quick fix when installing the Matplotlib package in MacOS. Simply describe that, when we use python in MacOS and we install the Matplotlib module, we cannot run module to show the plot due to the differences in using python framework of MacOS. (for more detail, please look that this [link](https://matplotlib.org/faq/osx_framework.html))

Creating file if you dont have it: `~/.matplotlib/matplotlibrc`. In file, insert with this line:

`backend: TkAgg`

Run again, the error will be fixed.

## 2. Config VSCode to recognize VirtualENV

When you create the virtualenvs and you wish that VSCode interpreter will recognize them for you when open project. However, sometimes it doesn't update all of virtualenvs. One of the way to fix is that we manual tell the VSCode know where to look at all the virtualenvs.

Suppose, I store all my virtualenvs in the `Documents` folder. Open VSCode setting, search `Python: Venv Path`. In here, we input the directory of `Documents` folder, for ex:

`/Users/thanhvo/Documents`

Then VSCode will look into Documents folder and scan all of the VirtualEnv for you.