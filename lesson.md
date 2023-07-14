# Lesson

## Brief

### Preparation

#### Prerequisite knowledge for this program

Familarity with Python programming language, at a basic to intermediate level. At least an understanding of and ability to code the following concepts:

- Variables
- Data types
- Operators
- Control structures
- Loops
- Built-in methods and functions
- Classes and objects

### Lesson Overview

This lesson contains a lot of installations. Learners should expect hiccups and some waiting time while instructor is troubleshooting issues for other learners.

---

## Part 1 - Introduction to data science and databases

Conceptual knowledge, refer to slides.

---

## Part 2 - Introduction to data science toolbox

### Install development tools

- Download and install git [here](https://git-scm.com/downloads)
  - Git is a version control system that we will be using throughout this program, to manage our codes
- Download and install miniconda [here](https://docs.conda.io/en/latest/miniconda.html)
  - Conda is a package and environment manager that we will be using throughout this program, to manage our Python packages and environments
- Download and install DBeaver Community [here](https://dbeaver.io/download/)
  - DBeaver is a SQL client that we will be using throughout this program, to connect to databases and write SQL codes
- Download and install vscode [here](https://code.visualstudio.com/download)
  - VSCode is an IDE (Integrated Development Environment) that we will be using throughout this program, to write Python and SQL codes

### Install the following vscode extensions

Go to the `Extensions` tab, search for the following extensions in the marketplace and install them:

- Python
- Jupyter

---

## Part 3 - Python environments and git + github workflow

### Python environments

We can use conda to install different versions of Python. Conda also allows us to create and manage virtual environments for different projects. A `conda environment` is a self-contained virtual environment that contains its own Python installation and packages. This allows us to have different versions of Python and packages for different projects, without them conflicting with each other.

#### Create a conda environment

```bash
conda create -n <env_name> python=<python_version>
```

for example:

```bash
conda create -n myenv python=3.10
```

#### Activate a conda environment

```bash
conda activate <env_name>
```

#### Deactivate a conda environment

```bash
conda deactivate
```

#### Remove a conda environment

```bash
conda remove -n <env_name> --all
```

#### Install packages in a conda environment

```bash
conda install -n <env_name> <package_name>
```

or activate the environment first, then:

```bash
conda install <package_name>
```

to install multiple packages at once:

```bash
conda install <package_name_1> <package_name_2> <package_name_3>
```

#### Uninstall packages in a conda environment

```bash
conda uninstall -n <env_name> <package_name>
```

or activate the environment first, then:

```bash
conda uninstall <package_name>
```

#### Freeze dependencies

Freezing dependencies is the process of writing the dependencies of an environment to a file. This allows us to recreate the exact same environment for the application, with the exact same versions of packages.

Activate the environment first, then:

```bash
conda env export > environment.yml
```

> Walk through the creation of an environment for this module

#### Recreate conda environment from environment.yml

```bash
conda env create -f environment.yml
```

#### Running python scripts in a conda environment

After activating the environment, run:

```bash
python <script_name.py>
```

### Git

Git is a version control system which allows us to track changes to our codes.

#### Create a git repository

```bash
git init
```

#### Add files to staging area

```bash
git add <file_name>
```

or add all files to staging area:

```bash
git add .
```

#### Commit changes

```bash
git commit -m "<commit_message>"
```

for example:

```bash
git commit -m "Initial commit"
```

#### Check status

```bash
git status
```

#### Check commit history

```bash
git log
```

### Github

Github is a cloud-based hosting service for git repositories. It allows us to store our git repositories in the cloud, and collaborate with other developers.

#### Clone a git repository

```bash
git clone <repo_url>
```

#### Pull changes from remote repository

```bash
git pull
```

#### Push changes to remote repository

```bash
git push
```

> Walk through the forking of this repository and cloning of the forked repository to the local machine. Then attempt the 1st question of the assignment, and push the changes to the forked repository.
