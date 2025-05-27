# Wasserstein distance demonstration
This is a short Jupyter notebook demonstrating the advantage of using the Wasserstein distance over the L2 distance.

The $$\ell^2$$ distance (or alternatively an $$\ell^2$$ votemap) is commonly used metric in data science to compare similarity between distributions. However, if there is no overlap between features of the models being compared, then the $$\ell^2$$ distance cannot differentiate between model similarity. The Wasserstein distance (or earth mover's distance) quantifies the amount of work needed to transform one distribution into another, at the cost of higher computational expense.

Check out the image below, or open with Binder to interact with the plot: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tom-new/Wasserstein-distance-demonstration/main?filepath=wass_test_2d.ipynb)

