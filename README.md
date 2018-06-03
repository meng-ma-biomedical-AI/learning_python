# README

Python is a general-purpose programming language [that is very popular](https://madnight.github.io/githut/). I have wanted to learn Python for a long time but have put it off because I could get everything done in Perl and R. However, recently I've been working with [Snakemake](https://snakemake.readthedocs.io/en/stable/#), which is a workflow management system based on Python, and realised that knowing Python would help me use the tool better. In addition, a lot of my colleagues are using Python, so it helps to be able read and write Python.

# The Jupyter Notebook

The notebook formerly known as the [IPython Notebook](https://ipython.org/notebook.html) has also been on my list of things to learn. It serves as an interactive session for interweaving code and plain text. After [installation](https://jupyter.readthedocs.io/en/latest/install.html), run `jupyter notebook` to host an interactive session. I will use Jupyter notebooks to keep track of my Python code. Below are some useful links:

* [Comprehensive Beginner’s Guide to Jupyter Notebooks for Data Science & Machine Learning](https://www.analyticsvidhya.com/blog/2018/05/starters-guide-jupyter-notebook/)

# Reticulate

The [reticulate package](https://github.com/rstudio/reticulate) provides a comprehensive set of tools for interoperability between Python and R. Reticulate embeds a Python session within your R session, enabling seamless, high-performance interoperability.

    install.packages("reticulate")
    library(reticulate)
    use_python("/anaconda3/bin/python")

Using Python in R Markdown

    ```{python}
    import sys
    print(sys.version)
    ```

# Links

* Perl to Python [phrasebook](https://wiki.python.org/moin/PerlPhrasebook) for those coming from Perl and wanting to learn Python

