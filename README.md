# Intrinsic heat-kernel Gaussian processes on point clouds

**Jiaqi Xu and Tao Liu**

Code, synthetic data and numerical results for *Mass-compatible heat features for certified Gaussian process inference on point clouds with reflecting boundaries*.

**[Download the v1.0 research supplement](https://github.com/JiaqiXu7/rbf-fd-intrinsic-heat-gp/releases/tag/v1.0)**. On the release page, choose the named research ZIP under **Assets**. It contains the complete numerical methods, measurements and bilingual guides. The automatic “Source code” archives contain the repository landing page.

The final v1.0 release follows the figure and table numbers in the 20-page SIAM article and its supplementary materials.

After extraction, start with README.md (English) or README_zh-CN.md (中文). From the extracted directory, with Python 3.13:

    python3 -m pip install -r requirements.txt
    python3 reproduce.py tables
    python3 reproduce.py check
