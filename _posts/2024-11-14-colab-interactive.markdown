---
layout: post
title: "Making Google Colab Interactive"
date:  2024-11-14 06:00:00 -0500
categories: blog
---

I'm integrating a Google Colab notebook into a project for school, as an evaluator will need to run some ML code that I include, and I wrote it in Jupyter Notebook.

One thing that I wanted to include is some sort of interactivity, using buttons and sliders. I could probably have the evaluator edit some code, but that feels like an inconvenient request. To do this, I found a [handy notebook made by Google](https://colab.research.google.com/notebooks/forms.ipynb) that details some different field options that Colab supports. It also suggests that Jupyter Widgets can be used.

Unfortunately, it links to the v8.1.5 documentation. A few of the examples won't work in Google Colab, due to a mismatched version. Luckily, I was able to type in the following:

 `print(ipywidgets.__version__)`

This displayed the current version of the library as supported by Colab, which is v7.7.1. The [documentation can be found here](https://ipywidgets.readthedocs.io/en/7.7.1/). It wasn't terrible to figure out, but I'm hoping I can find a spot to suggest a fix to that Colab documentation so that it will link to the version being used!