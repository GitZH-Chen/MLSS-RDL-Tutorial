# MLSS 2026 Riemannian Deep Learning Tutorial

Hands-on notebooks for the MLSS 2026 tutorial on Riemannian deep learning.
Each activity opens directly in Google Colab and runs independently.

| Activity | Notebook | Launch |
|---|---|---|
| 1. Visualizing LieBN | [`01_BN_Visualization.ipynb`](01_BN_Visualization.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GitZH-Chen/MLSS-RDL-Tutorial/blob/main/01_BN_Visualization.ipynb) |
| 2. Build a two-layer HBNN | [`02_Two_Layer_HBNN.ipynb`](02_Two_Layer_HBNN.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GitZH-Chen/MLSS-RDL-Tutorial/blob/main/02_Two_Layer_HBNN.ipynb) |
| 3. Train a small HNN | [`03_HNN_Training.ipynb`](03_HNN_Training.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GitZH-Chen/MLSS-RDL-Tutorial/blob/main/03_HNN_Training.ipynb) |

## How to use the notebooks

1. Click **Open in Colab** for an activity.
2. Sign in to Google if Colab asks you to do so.
3. Select **Runtime → Run all**.
4. To keep your changes, select **File → Save a copy in Drive**.

Each participant receives an independent Colab runtime. The notebooks install
or download the dependencies they need and do not require a local checkout of
this repository.

## Local use

The notebooks are standard Jupyter `.ipynb` files. For local execution, install
the common dependencies with:

```bash
python -m pip install -r requirements.txt
```

