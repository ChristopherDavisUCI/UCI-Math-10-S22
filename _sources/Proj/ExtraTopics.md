# Possible extra topics

One of the rubric items for the course project is to include something "extra" that wasn't covered in Math 10.  Here are a few possibilities.  It's even better if you find your own extra topic; it can be anything in Python that interests you.

More possibilities will be added as I think of them.

## Neural Networks

In both Fall 2021 and Winter 2022, Math 10 included a significant portion on Neural Networks.  These are a fundamental (maybe the most fundamental) area of modern Machine Learning.  If you want to try learning about them, that would be a great extra topic.  In Fall 2021, we used the library TensorFlow (especially using the command `from tensorflow import keras`).  In Winter 2022, we used the library PyTorch.  Overall I think TensorFlow is easier to use (but PyTorch teaches some fundamentals of Object Oriented Programming).

## Principal Component Analysis in scikit-learn

![faces with pca](../images/pca.png)

[Principal component analysis](https://scikit-learn.org/stable/modules/decomposition.html#pca).  Another type of unsupervised learning (in addition to *clustering*) is *dimensionality reduction*.  Principal Component Analysis (PCA) is a famous example, and it involves advanced linear algebra.  The above image shows a visual example of the result of PCA.

## Kaggle

A general way to get ideas is to browse [Kaggle](https://www.kaggle.com/).  Go to a competition or dataset you find interesting, and then click on the *Code* tab near the top.  You will reach a page like this one about [Fashion-MNIST](https://www.kaggle.com/zalando-research/fashionmnist/code).  Any one of these notebooks is likely to contain many possibilities for extra topics.

## Big Data(sets)

Deepnote does not allow files bigger than 100mb to be uploaded.  Many real-world datasets are bigger than this.  Deepnote does definitely work with larger datasets.  If you end up using a larger dataset, describe how you made it work in Deepnote.  Some general guidelines are listed in the [Deepnote documentation](https://docs.deepnote.com/importing-and-exporing/importing-data-to-deepnote#uploading-files-to-deepnote).

## Other libraries
Here are a few other libraries that you might find interesting.  (Most of these are already installed in Deepnote.)
* [sympy](https://www.sympy.org/en/index.html) for symbolic computation, like what you did in Math 9 using Mathematica.
* [Pillow](https://pillow.readthedocs.io/en/stable/index.html) for image processing.
* [re](https://docs.python.org/3/library/re.html) for advanced string methods using regular expressions.
* [Seaborn](https://seaborn.pydata.org/) and [Plotly](https://plotly.com/python/plotly-express/).  We introduced these plotting libraries briefly together with Altair early in the quarter, and we have used Seaborn frequently for importing datasets.  Their syntax is similar to Altair.

## Different Python libraries

If you want to use a Python library that isn't by default installed in Deepnote, you can install it yourself within Deepnote, using a line of code like the following, which installs the `vega_datasets` library.  Notice the exclamation point at the beginning (which probably won't appear in the documentation you find for the library).
```
!pip install vega_datasets
```