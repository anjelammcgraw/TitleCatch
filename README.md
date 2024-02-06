## TitleCatch Demo

# Unsupervised Pre-Training of a GPT-Style Model

Today, we'll be working on demo-ing "Title Catch," a specialized model tasked with analyzing essays to autonomously generate titles that encapsulate their content.

This involves fine-tuning a GPT-style, decoder-only architecture, tailored through unsupervised learning to master the art of title creation from extensive textual data.

We'll be using Andrej Karpathy's [nanoGPT](https://github.com/karpathy/nanoGPT/tree/master) as our base model builder and architecture. 

You can find Colab link to the notebook below:
- [Title Catch](https://colab.research.google.com/drive/1dRPXfGLHejRCQCGAv47M8TLVG8_gX01K?usp=sharing)


## Purpose 🏗️
We will leverage a dataset of 28 compiled college essays I've written to train our model. 
