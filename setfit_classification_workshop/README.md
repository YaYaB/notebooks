# Setfit classification workshop


## Objectives
The goal of this workshop is to show how we can create a mode with very few data points and not a lot of time to work on it.

To do so we'll use [SetFit](https://arxiv.org/pdf/2209.11055.pdf), aka Sentence Finetuning.

## Agenda

This workshop is intended for a 2 hour session and consists of several parts:
- few-shot text classification with SetFit
- distillate a model
- quantize a model
- zero-shot text classification

In the first part we show how to train a text classification with very few labels, several datasets are available and you can also yours.
The second part tackles the distillation part and explain how we can train a smaller model with very good perfomances using distillation.
The third part explains and illustrates the quantization, that is changing the range of values of the weights of the model for performance (in time) gains.
Finaly, we show how we can do zero-shot text classification using SetFit, without any labels how we can classify new content based on wanted labels.


## Installation

This workshop can be launched on jupyter notebook or colab. Using a gpu makes everything faster however having only a good cpu is enough.

I usually use colad to avoid any local installations on the students' machine.


## Additional notes

Please note that this notebook is GREATLY inspired from the notebooks available in the official [repository](https://github.com/huggingface/setfit/tree/main/notebooks).
Here we combine some of them to have an overview of SetFit.