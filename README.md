# Data Science & Machine Learning

## A Few Basic Requirements

- Install `conda` or `miniconda`.
- Create a project folder.
- Then proceed.

To create a new environment with dependencies to use:

```sh
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


