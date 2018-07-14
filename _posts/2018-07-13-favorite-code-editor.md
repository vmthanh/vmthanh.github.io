---
title: "Visual Studio Code: How I changed from Sublime Code to Visual Studio Code"
layout: post
excerpt: "Like many developers, I don't like Microsoft and many others M$ products. But this is the reasons I started to love and changed from Sublime Code to Visual Studio Code as my main code editor."
tags:
  - code
  - visual studio code
  - sublime code
  - code editor
---

Like many developers, I don't like Microsoft and many other Microsoft products. Window kernel based runs on DOS (correct me if I'm wrong) but many tools, libraries and support frameworks (especially in machine learning and big data) are written Unix/Linux based. My main working environment has been Ubuntu for nearly 3 years since I became Android developer and now is a Machine learning engineer. 

At that time, beside other heavy specific programming studio such as Android Studio, I always to look up a light weight code editor for helping me work fast and easily. So that, [Sublime Text](https://www.sublimetext.com/) became my favorite editor. Using Sublime, I could edit any files, code web with front end and backend, loop up a function in source code, replace a world, code syntax highlight, formating and much more. Life becomes simple with Sublime. 

But recently, I found my new favorite one, [Visual Studio Code](https://code.visualstudio.com/) (VSC). With after a few configurations, VSC could satisfy me as same as Sublime and even more. Here are some reasons with simple configurations to make me change from Sublime to VSC.

## How to install VSC in Ubuntu 

VSC is a cross platform editor that could work in Microsoft, Linx, Mac. Just need go to [VSC](https://code.visualstudio.com/Download)  and download it. Because I use Ubuntu so I choose .deb file. Install and ta-da, it comes to life.

![VSC images](/images/favorite-code-editor/vsc-main.png)

## What I likes Visual Studio Code 

### IntelliSense 

Just like Sublime, as soon as you open a project, VSC will start to scan it for syntax highlighting and autocomplete. VSC has been integrated with many other popular programming languages (C++, C#, Java, Python, Javascript, Go...) so that it could provide with smart completion, finding a keyword function, definition with your code. 

### Fast 

To be honest, VSC is much slower than Sublime in compared of openning a project and scan. But it still be MUCH MUCH better than others. I used to open a Python project with 10GB images with Pycharm (other Python editor). And it stucks and swallows all my RAM for scanning and indexing file. But for VSC, it still work fine and fast. 

### Built in Debugger

This is definitely my most favorite features. For many years, Sublime cannot satisfy me because it does not support debugging plugins offically (other Sublime pluggins are suck). When I write Python code, I have to open Pycharm to debug something tricky. With VSC and Python extension, I could do the same thing in Pycharm with VSC. Moreover, at anytime in VCS, I coud stop at one line of code and use Debug Console (View/Debug Console) to play arround with variables  such as add/change/modify value while they are running (sound like Matlab, right?!).

![VSC debug](/images/favorite-code-editor/vsc-debug.png)

### Built in Terminal 

Suppose you writte a website running on NodeJS backend or just write Jekyll blog like me by Subline, you have to open a separate terminal to run server and control the unit test running. More window, more distraction. The life of backend devoper or ML engineer will force you to work with terminal a lot. VSC has come with built in terminal where everything I need runs in one large window. I could write blog by Markdown in the left layout, look the preview in the right one while controlling the Jekyll build at the bottom. How easy it is!

![VSC terminal](/images/favorite-code-editor/vsc-terminal.png)

### Build in Git

Lots of features are build in VSC. One of these is Git integration. Simple but enough, now I could stage files, review diffs and make commits right from editor. 

![VSC terminal](/images/favorite-code-editor/vsc-git.png)

## Some configurations for VSC 

Beside build in features, VSC could be boosted and customized with many extensions. Here are some my favorites ones 

![VSC terminal](/images/favorite-code-editor/vsc-extensions.png)

### [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

A Visual Studio Code extension with rich support for the Python language (including Python 3.6), including features such as linting, debugging, IntelliSense, code navigation, code formatting, refactoring, unit tests, snippets, and more!

### [VSCode-Icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons)

Bring icons to your Visual Studio Code

### [Eclipse Keymap](https://marketplace.visualstudio.com/items?itemName=alphabotsec.vscode-eclipse-keybindings)

This extension ports popular Eclipse keyboard shortcuts to Visual Studio Code. Eclipse key bindings are provided for Windows, Linux and macOS.

### [Jupyter](https://marketplace.visualstudio.com/items?itemName=donjayamanne.jupyter)

Data Science with Jupyter on Visual Studio Code

## Conclusion

In the end, text editors are all about personal preferences and job requirements. For my use case, Visual Studio Code has help me a lot to write code faster. At last, I feel less hate a little bit with Microsoft now. 

Let me know what your favorite editor is in the comments!