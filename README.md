# Welcome to the Data Science Course!

Welcome to our exciting journey into the world of Data Science! This course is designed to provide you with a comprehensive understanding of Data Science fundamentals, focusing on practical skills and real-world applications using Python.

### Current Course Materials

Here's what you can find in our repository:

- **Python Jupyter Notebooks**: Interactive notebooks with code, explanations, and exercises.
- **PDF Presentations**: Slides covering key concepts and examples.
- **Assignments**: Python notebook assignments to apply what you've learned.
- **Datasets**: A collection of datasets used in our materials, including links to Kaggle datasets for hands-on practice.
- **Additional Resources**: Links to further reading and external resources.

### Course Structure

Each week, we'll explore different topics in Data Science, starting from the basics and gradually moving to more advanced concepts. The course is designed to be hands-on, with a mix of theory, practical exercises, and projects.

Here's a tentative outline of the course:

 - **Week 1**: Introduction to Data Science
    - Overview of Data Science
    - The role of a Data Scientist
    - Key concepts and applications in Data Science
    - Course summary and expectations

 - **Week 2**:  Python for Data Science
    - Introduction to Python programming
    - Jupyter notebooks
    - Python libraries for Data Science: NumPy and pandas
    - Basic Python data structures (lists, dictionaries, sets, tuples)
    - Basic operations with pandas: data loading, cleaning, and manipulation

 - **Week 3**:  Basic Data Processing and Transformations
    - Data preprocessing techniques
    - Handling missing data (imputation)
    - Data transformation: encoding, scaling, normalization
    - Introduction to data wrangling with pandas

 - **Week 4**:  Review of Statistics and Probability
    - Descriptive statistics and inferential statistics
    - Probability distributions and their applications in Data Science
    - Hypothesis testing basics
    - Correlation vs causation

 - **Week 5**:  Exploratory Data Analysis (EDA)
    - What is EDA? Why?
    - Descriptive statistics
    - Basic data visualization (histograms, scatter plots, line plots)
    - Finding outliers
    - Multivariate analysis
    - Connecting features (correlation)
    - Dimension Reduction: PCA

 - **Week 6**:  Advanced Data Visualization Techniques
    - Visualization best practices and storytelling
    - Multivariate density plots and box plots
    - Working with geographical data (GeoPandas)
    - Interactive visualizations
    - Non-linear dimension reduction

 - **Week 7**:  Introduction to Machine Learning
    - Overview of Machine Learning
    - Supervised vs. Unsupervised Learning
    - Clustering: K-Means, Hierarchical Clustering
    - Basic concepts: evaluation, overfitting, underfitting, and model tuning
    - Using ML pipelines for data analysis

 - **Week 8**: Dealing with Network Data (Graphs)
    - Introduction basic concepts in network analysis.
    - Representing networks, nodes, edges, and their properties.
    - Overview of common algorithms used in network analysis.
    - Network analysis tools: NetworkX, igraph, gephi.
    - Networks and machine learning.
    - Real-world applications: social networks, biological networks, and more.

 - **Week 9**:  Dealing with Textual Data
    - Text preprocessing: tokenization, lemmatization, stop word removal
    - Vectorization of text: TF-IDF
    - Neural network embeddings for text data
    - Case studies in Natural Language Processing (NLP)

 - **Week 9**: Introduction to Big Data
    - Big Data Fundamentals.
    - Basic concepts and applications of the MapReduce programming model.
    - Overview of Hadoop and Spark.
    - Introduction to NoSQL databases.
    - Basic approaches and tools for processing and analyzing large datasets.
    - Real-world Big Data case studies.

 - **Week 11**:  Project and/or Hackaton
 
 - **Week 12**:  Final Exam

As of now, only the materials for **Week 5: Exploratory Data Analysis** are available in the repository.

### Prerequisites
Students are required to know the basics of algorithms and programming (preferably Python), statistics and linear algebra.

### Grades
Students will be evaluated based on their performance in participation, attendance, assignments, final project and the final exam. The final grade will be calculated as follows:

 - 20% - Participation and attendance
 - 20% - Assignments
 - 30% - Final project
 - 30% - Final exam

Some assignments may give bonus points for the final grade.


### Recommended Books and Resources

Here are some highly recommended books and resources on Data Science with Python:

1. **"Python Data Science Handbook" by Jake VanderPlas**: A comprehensive guide to using Python for data analysis, manipulation, and visualization.
2. **"Data Science from Scratch" by Joel Grus**: A great introduction to Data Science fundamentals using Python.
3. **"Python for Data Analysis"** by Wes McKinney (the creator of pandas): A practical guide to using Python for data analysis, manipulation, and visualization.
4. **"Introduction to Machine Learning with Python" by Andreas C. Müller & Sarah Guido**: A practical approach to learning machine learning with Python.
6. **Kaggle**: Participate in competitions or explore kernels for practical experience. (https://www.kaggle.com)
7. **Awesome Public Datasets**: For understanding Python in-depth. (https://github.com/awesomedata/awesome-public-datasets)

### Getting Started

To get started, please ensure you have set up your environment as described in the next sections. We encourage you to explore the materials, complete the assignments, and actively participate in discussions using the Issues tab of this .



## Setting Up Your Data Science Environment

### Step 1: Install Miniconda

Miniconda is a minimal installer for Conda, a package manager and environment manager. Here’s how to install it:

1. **Download Miniconda**:
   - Visit the [Miniconda download page](https://docs.conda.io/en/latest/miniconda.html).
   - Choose the version suitable for your operating system (Windows, macOS, or Linux).
   - Download the appropriate installer (Python 3.x is recommended).

2. **Install Miniconda**:
   - **Windows**: Run the downloaded `.exe` file and follow the on-screen instructions.
   - **macOS/Linux**: Open a terminal, navigate to the folder containing the downloaded file, and run `bash Miniconda3-latest-MacOSX-x86_64.sh` (adjust the filename as needed).

3. **Verify the Installation**:
   - Open a new terminal window.
   - Type `conda list`. If Miniconda is installed correctly, you'll see a list of installed packages.

### Step 2: Create a Conda Environment

Creating a separate environment for your Data Science projects is good practice:

1. **Create a New Environment for this course**:
    - Run the command: `conda env create -f environment.yml`. This will create a new environment called datascience with all the necessary packages installed.

2. **Activate the Environment**:
   - Run: `conda activate datascience`.

3. **Launch Jupyter Lab**:
   - Run: `jupyter lab`.
   - This will open Jupyter Lab in your default web browser.

### Step 3: Manually Install Essential Packages

The created environment already includes most of the packages we'll need, but if you need to install any additional packages, here's how:

1. **Manually Install Packages **:
   - In your activated environment, run: `conda install <name of the package>` to install the packages
   - For example, to install the `scikit-learn` package, run: `conda install scikit-learn`.
   - Alternatively, you can use `pip install <name of the package>` to install packages from PyPI.

### Step 4: Verify Installation

Make sure everything is installed correctly:

1. **Open a New Notebook in Jupyter Lab**:
   - In Jupyter Lab, create a new notebook.

2. **Test the Packages**:
   - Try importing the packages: `import numpy as np`, `import pandas as pd`, `import matplotlib.pyplot as plt`.
   - If there are no errors, the packages are installed correctly.

### Additional Tips

- **Updating Conda**: Keep Conda and your packages updated with `conda update conda` and `conda update --all`.
- **Managing Environments**: View your environments with `conda env list` and switch between them using `conda activate <env_name>`.
- **Finding Packages**: To find available packages, use `conda search <package_name>`.
- **Conda Cheat Sheet**: For more commands, see the [Conda Cheat Sheet](https://docs.conda.io/projects/conda/en/latest/user-guide/cheatsheet.html).




## Basic GitHub Usage for the Data Science Course  (for submitting assignments)

### Step 1: Fork the Course Repository

"Forking" means creating a personal copy of someone else's project. To fork the `filipinascimento/datascience` repository:

1. **Navigate to the Repository**:
   - Go to the [filipinascimento/datascience](https://github.com/filipinascimento/datascience) repository on GitHub.

2. **Fork the Repository**:
   - Click on the "Fork" button at the top right corner of the page.
   - This will create a copy of the repository in your GitHub account.

### Step 2: Clone the Forked Repository

After forking, you'll want to clone the repository to work on it locally:

1. **Clone the Repository**:
   - On your forked repository page, click the "Code" button and copy the URL under "Clone with HTTPS".
   - Open a terminal on your computer and run `git clone [URL]` (replace `[URL]` with the copied URL).

### Step 3: Use the Issues Tab

The Issues tab in GitHub is used to track ideas, enhancements, tasks, or bugs:

1. **Navigate to Issues**:
   - In the original `filipinascimento/datascience` repository, go to the "Issues" tab.

2. **Create a New Issue**:
   - Click on "New Issue".
   - Provide a title and a detailed description of your problem or discussion point.
   - Click "Submit new issue" when done.

### Step 4: Submitting Assignments as Pull Requests

Submit your completed assignments as Pull Requests:

1. **Complete Your Assignment**:
   - Work on the assignment in your local clone of the forked repository.
   - Rename the assignment file to include your GitHub username (e.g., `assignment1-username.ipynb`).

2. **Commit Your Changes**:
   - Use `git add .` to stage your changes.
   - Commit the changes with `git commit -m "Completed Assignment"`.

3. **Push to GitHub**:
   - Push your changes to your forked repository using `git push`.

4. **Create a Pull Request**:
   - Go to the original `filipinascimento/datascience` repository.
   - Click on "Pull Requests" and then "New Pull Request".
   - Choose your forked repository as the source.
   - Add a title and description for your PR.
   - Click "Create pull request".

### Step 5: Keep Your Fork Updated

Ensure your fork is up to date with the main repository:

1. **Configure a Remote for the Fork**:
   - Run `git remote add upstream https://github.com/filipinascimento/datascience.git`.

2. **Sync Your Fork**:
   - Fetch the changes with `git fetch upstream`.
   - Check out your fork's local default branch (`main` or `master`) with `git checkout main`.
   - Merge changes from `upstream/main` into your local branch with `git merge upstream/main`.

### Additional Resources

- **GitHub Documentation**: For more detailed instructions, visit [GitHub Docs](https://docs.github.com/en).
- **Git Cheatsheet**: Refer to this [Git Cheatsheet](https://training.github.com/downloads/github-git-cheat-sheet.pdf) for common Git commands.

