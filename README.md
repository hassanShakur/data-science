# Data Science & Machine Learning

## A Few Basic Requirements

- Install `conda` or `miniconda`.
- Create a project folder.
- Then proceed.

To create a new environment with dependencies to use:

```sh
# For an empty environment
conda create --prefix ./env

# Env with some tools
conda env create --prefix ./env pandas scikit-learn and-all-other-dependencies-here
```

To export an already created environment so it can be replicated:

- Activate the `env` you want to track:

```sh
conda env list
conda activate /path/to/project/env
conda env export > environment.yml
```

- Navigate to the project to create the new environment and run:

```sh
conda env create --prefix ./env -f ../path/to/environment.yml
```

You can always deactivate an environment through:

```sh
conda deactivate
```

## About the Project

This project is a collection of notebooks and scripts that I use to learn and practice data science and machine learning. It starts from the very basics and goes on to more advanced topics. The project is divided into two main parts:

- **Data Science**: This part is about data analysis and visualization. It covers the basics of data analysis and visualization using `pandas`, `matplotlib`, `seaborn`, and `plotly`. It also covers some advanced topics such as time series analysis and geospatial data analysis.
- **Machine Learning**: This part is about machine learning. It covers the basics of machine learning using `scikit-learn`. It also covers some advanced topics such as deep learning and natural language processing.

## About the Notebooks

Notebooks can be found in individual folders in the repo, Ex. `np` contains notebooks for `numpy`. As for advanced Machine learning and Deep learning, I used [Google Colab](https://colab.research.google.com/) to run the notebooks. The links to the notebooks are provided in the `README.md` files in the respective folders.

## References

- [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
- [Python for Data Analysis](https://www.oreilly.com/library/view/python-for-data/9781491957653/)
- [Scikit-Learn](https://scikit-learn.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [PyTorch](https://pytorch.org/)
- [FastAI](https://www.fast.ai/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
