# Lidl Product Association Generator
Build with Python Data Science stack, NetworkX (for graphs) and Tensorflow, LPAG provides an accurate way to mimic the product recommendations produced by Lidl's<sup>1</sup> recommendation engine.

To use it LPAG on your machine, you need to use Python 3.7+ and install the requirements provided in the repo through `pip install -r requirements.txt`. All the code is in the notebook, `Lidl Product Association Generator.ipynb`. The configuration specific to the Lidl subsidiary used in this project is specified (and internally loaded in the notebook) in `config.yaml`.

---
<sup>1</sup> Lidl is a German supermarket chain with presence all over Europe. In this exercise, I use its Poland's subsidiary [website](https://www.lidl.pl/) to collect product metadata.