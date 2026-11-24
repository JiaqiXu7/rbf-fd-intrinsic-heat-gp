# Intrinsic heat-kernel Gaussian processes on point clouds

Code, synthetic data and numerical results accompanying *Mass-compatible heat features for certified Gaussian process inference on point clouds with reflecting boundaries*.

**[Download the complete research supplement (ZIP)](https://github.com/JiaqiXu7/rbf-fd-intrinsic-heat-gp/releases/download/v1.0/rbf-fd-intrinsic-heat-gp-1.0.zip)**

Extract the archive and open `README.md` (English) or `README_zh-CN.md` (中文). Both guides link the figures and tables of the paper to the corresponding measurements. The supplement includes the RBF-FD and heat-feature methods, the rolled-strip observations and query coordinates, likelihood and posterior error bounds, and paired timing measurements.

From the extracted directory, using Python 3.13:

```sh
python3 -m pip install -r requirements.txt
python3 reproduce.py tables
python3 reproduce.py check
```

The table command recomputes numerical summaries from the saved measurements. The archive includes separate instructions for repeating the six spatial-state calculations, the physical posterior comparison and the shared-design likelihood experiment.
