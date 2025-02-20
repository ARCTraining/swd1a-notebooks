# swd1a-notebooks
A repository for notebook copies of the lessons in SWD1a, that can be launched in Colab.

To update a file/create the notebook:

- Copy the `.md` file for the lesson, and strip out links, images, and `Rmd` code fencing (marked by `:::`, for callout blocks etc.)
- In a Python env with Jupytext, run `jupytext --to ipynb 01-intro.md` to create `01-intro.ipynb`.
- Check that Jupyter notebook looks correct and is functional; ensure that you clear all output before saving.
- Remove large "solution" blocks to the challenges where appropriate.
- Generate link for Colab: after pushing to the repository, replace the `github.com` in the url to the notebook with `colab.research.google.com/github`
- Remember to add cells for downloading and unzipping the data when necessary.


## Directory of notebooks:

(These are given in the order we deliver our materials in)

### Day 1 notebooks:

- [Introduction](colab.research.google.com/github/ARCTraining/swd1a-notebooks/blob/main/01-intro.ipynb)
- [Lists](colab.research.google.com/github/ARCTraining/swd1a-notebooks/blob/main/04-lists.ipynb)
- [Loops](colab.research.google.com/github/ARCTraining/swd1a-notebooks/blob/main/05-loops.ipynb)
- [Numpy](colab.research.google.com/github/ARCTraining/swd1a-notebooks/blob/main/02-numpy.ipynb)