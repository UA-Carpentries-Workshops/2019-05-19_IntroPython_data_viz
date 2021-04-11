# 2021-04-11 PVAMU SWEETER Intro to Data Analysis with Python Pandas on NSF Jetstream Cloud Computing

## Introduction
We'll be using the NSF-funded Jetstream research computing cloud (https://jetstream-cloud.org/). All of us will be using Jupyter notebooks as set up through JupyterHub (https://jupyter.org/hub). In short: 
- We all are going to be running the notebooks on the same computing resources (cloud computers; official terms are virtual machines and if they're running it's called an instance)
- I set up JupyterHub on the Jetstream instances I created using an excellent Jetstream tutorial called ["The Littlest JupyterHub"](https://tljh.jupyter.org/en/latest/install/jetstream.html).

### What does it all mean!? 
Well, we won't have to install much (possibly nothing) at the beginning of the class. And because we're all on the same running cloud computer, instance, we have the same operating system, the same software packages, and the same versions of all of that too. So you'll notice we'll all (likely) have the exact same experience in the class! This saves a ton of time when it comes to the beginning of the class. 

### Can I install all this on my local computer?
We'll be using Python 3, Jupyter (JUlia + PYThon +R = Jupyter) Notebooks, and Pandas to analyze the Titanic passenger log. The easiest way to install all of these on your local computer, that's your laptop or desktop, is using Anaconda: https://docs.anaconda.com/anaconda/install/

Python updates a lot and the code that Python depends on also changes a lot. Anaconda helps to keep some of those changes stable. For this session I used:
conda install plotnine
conda install pandas

But your installation might be different than mine! Your operating system, your version of the OS, all of the software and code languages installed on your computer, and lots of other things will all be different from the ones on my computer. I like to call it the "genetic variablity of computers."
