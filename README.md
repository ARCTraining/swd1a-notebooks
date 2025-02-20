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

# Using the notebooks

Provide learners with the snippet below (this is added to the beginning of the first notebook).

***

## How to use these notebooks

Note that links in these notes may be broken, please
see the [course notes here](https://arctraining.github.io/python-novice-inflammation/01-intro.html) for correct links etc.

### Stop! When you see the header "solution"

When you read a challenge asking you to do something, don't read beyond the next header that reads "Solution". Insert a new code cell below the question and attempt to solve it yourself before reading on.

### Remember to apply PRIMM

When you see a piece of code, remember:

1. Before you do anything else, **predict** what the output is going to be.
2. Then **run** it, and compare the output to your prediction.
3. You can begin to **investigate**, especially if your guess is way off - what information can you find in the notes, or online?
4. Once you've tried to understand how the code works, try to **modify** it and make some changes.
5. Then, you're ready to start **making** your own code!

We will mainly be cycling through stages 1 and 2, with some of the later stages coming in as you build more knowledge.