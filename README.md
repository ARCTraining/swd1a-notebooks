# swd1a-notebooks
A repository for notebook copies of the lessons in SWD1a, that can be launched in Colab.

To update a file/create the notebook:

- Copy the `.md` file for the lesson, and strip out links, images, and `Rmd` code fencing (marked by `:::`, for callout blocks etc.)
- In a Python env with Jupytext, run `jupytext --to ipynb 01-intro.md` to create `01-intro.ipynb`.
- Check that Jupyter notebook looks correct and is functional; ensure that you clear all output before saving.
- Generate link for Colab: after pushing to the repository, replace the `github.com` in the url to the notebook with `colab.research.google.com/github`
- Remember to add cells for downloading and unzipping the data when necessary.
