# MLSS 2026 Riemannian Deep Learning Tutorial

Hands-on notebooks for the MLSS 2026 tutorial on Riemannian deep learning.
The live session focuses on the following two activities:

| Activity | Notebook | Launch |
|---|---|---|
| 1. Hyperbolic trees, horospheres, and a two-layer HBNN | [`01_Two_Layer_HBNN.ipynb`](01_Two_Layer_HBNN.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GitZH-Chen/MLSS-RDL-Tutorial/blob/main/01_Two_Layer_HBNN.ipynb) |
| 2. ResNet-18 with a Poincaré BMLR head | [`02_ResNet18_Poincare_BMLR_MNIST.ipynb`](02_ResNet18_Poincare_BMLR_MNIST.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GitZH-Chen/MLSS-RDL-Tutorial/blob/main/02_ResNet18_Poincare_BMLR_MNIST.ipynb) |

## Optional activity

The Riemannian batch normalization notebook is provided as optional material for self-study.
| Activity | Notebook | Launch |
|---|---|---|
| Visualizing LieBN | [`Optional_LieBN_Visualization.ipynb`](Optional_LieBN_Visualization.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GitZH-Chen/MLSS-RDL-Tutorial/blob/main/Optional_LieBN_Visualization.ipynb) |

## How to use the notebooks

1. Click **Open in Colab** for an activity.
2. Sign in to Google if Colab asks you to do so.
3. Select **Runtime → Run all**.
4. To keep your changes, select **File → Save a copy in Drive**.

Activity 2 is designed for a GPU runtime; Activity 1 and the optional LieBN activity also run on CPU.

## Local use

The notebooks are standard Jupyter `.ipynb` files. For local execution, install
the common dependencies with:

```bash
python -m pip install -r requirements.txt
```
