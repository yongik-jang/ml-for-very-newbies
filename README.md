# Machine Learning for Very Newbies — A Practical Guide

Slide and hands-on notebooks for an introduction to machine learning,
given at the JCP HEP School at Chungnam National University.

No prior ML experience is assumed. If you can write a Python loop, you can follow along.

## What we cover

Build a function, measure how wrong it is, and make it less wrong.

1. **Building Blocks** — perceptron, XOR, MLP, nonlinearity, universal approximation
2. **Training** — data splits, loss, cross-entropy, backpropagation, SGD → Adam, overfitting and regularization
3. **Hands-On MNIST** — build and train an MLP on handwritten digits
4. **CNN** — why the MLP breaks when the digit moves, and how convolution and global average pooling fix it

## Notebooks

Open in Colab.

| | Student (blanks to fill) | Solution |
|---|---|---|
| 01 Worked examples | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yongik-jang/ml-for-very-newbies/blob/main/notebooks/01_examples_student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yongik-jang/ml-for-very-newbies/blob/main/notebooks/01_examples_solution.ipynb) |
| 02 Hands-On MNIST | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yongik-jang/ml-for-very-newbies/blob/main/notebooks/02_mnist_student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yongik-jang/ml-for-very-newbies/blob/main/notebooks/02_mnist_solution.ipynb) |

`01` reproduces claims from the slide in small, checkable pieces (a perceptron by hand,
autograd, the optimizers written out). `02` is the real thing: MNIST with an MLP, then a CNN.

Cells marked `# TODO` in the student notebooks are left for you to fill in.
A `...` placeholder is valid Python, so a cell will run — and fail loudly — until you replace it.

## Repository layout

```
slide/       lecture slide (PDF)
notebooks/    01_examples_*.ipynb, 02_mnist_*.ipynb
```

## Running locally

Colab has everything preinstalled. For a local run:

```bash
pip install numpy matplotlib seaborn scikit-learn torch torchvision
```

