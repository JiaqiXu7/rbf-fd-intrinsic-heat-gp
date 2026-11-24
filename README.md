# Intrinsic heat-kernel Gaussian processes on point clouds

**Jiaqi Xu and Tao Liu**

Code, synthetic data and numerical results for *Mass-compatible heat features for certified Gaussian process inference on point clouds with reflecting boundaries*.

**[Download the latest research supplement](https://github.com/JiaqiXu7/rbf-fd-intrinsic-heat-gp/releases/latest)**. On the release page, choose the named research ZIP under **Assets**. It contains the complete numerical methods, measurements and bilingual guides. The automatic “Source code” archives contain the repository landing page.

Release v1.1 follows the figure and table numbers in the 20-page SIAM article and its supplementary materials. The underlying experimental measurements are the same as in v1.0.

After extraction, start with README.md (English) or README_zh-CN.md (中文). From the extracted directory, with Python 3.13:

    python3 -m pip install -r requirements.txt
    python3 reproduce.py tables
    python3 reproduce.py check
