# Basics of Data Analytics

This repository serves as a tutorial for beginner level data science practitioners to acquaint with some of the packages and tools that most data science projects use.<br>

## Learning Content Outline

### [**NumPy**](https://github.com/CertifaiAI/basics-of-data-analytics/tree/main/Numpy/exercise)
1. NumPy ndarray
2. Array Creation
3. Basic Operation
4. Iterating, Indexing and Slicing
5. Manipulating ndarray
6. Exercise for Array Creation & Basic Operation
7. Exercise for Iterating, Indexing and Slicing & Manipulating ndarray

### [**Pandas**](https://github.com/CertifaiAI/basics-of-data-analytics/tree/main/Pandas/Exercise)
1. Fundamentals of Pandas
2. Basic Functions
3. Common Operations
4. Data Cleanup and Missing Data
5. Exercise for Fundamentals of Pandas & Basic Functions
6. Exercise for Common Operations & Data Cleanup and Missing Data

### [**Matplotlib**](https://github.com/CertifaiAI/basics-of-data-analytics/tree/main/Matplotlib/Exercise)
1. Getting Started with PyPlot
2. Getting Started with PyPlot (Exercise)
3. Creating Different Types of Graphs with PyPlot
4. Creating Different Types of Graphs with PyPlot (Exercise)

<hr/>

## Guidelines to Use this repo for students

1. Ensure that you have [**Anaconda**](https://docs.anaconda.com/anaconda/install/) or [**Miniconda**](https://docs.conda.io/en/latest/miniconda.html) installed in your system.

2. [Clone](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository) this repo into your local machine.

    `git clone https://github.com/CertifaiAI/basics-of-data-analytics.git `

    >   Alternatively, you may just "Download ZIP" and unzip the folder locally.

3. Open terminal and cd to the `basics-of-data-analytics` folder.

    ```shell
    cd <your-path>/basics-of-data-analytics
    ```

4. Create a new Conda environment using the the following command line.

    `conda create --name basics-of-data-analytics python=3.7`

    > Alternatively, you may create a new `conda` environment using `environment.yml`.
    >
    > `conda env create -f environment.yml`

5. Activate the newly created environment `basics-of-data-analytics`.

    `conda activate basics-of-data-analytics`

6. Install Jupyter Notebook using conda command.

    `conda install -c conda-forge jupyterlab` 

    > You may skip this step if you've create the environment using `environment.yml` file in step 4.

7. Open Jupyter Notebook using

    `jupyter notebook`

8. Every package folder (Eg: NumPy) has an *"Exercise"* folder and a *"Solution"* folder. Follow along the notebooks in the *"Exercise"* folder. 

    >   But if you couldn't resolve certain exercises or tasks within those notebooks in the *"Exercise"* folder, refer to the solution counterpart of that notebook located in the *"Solution"* folder (has the same file name)<br/>
    >   Eg: `Numpy/exercise/01 - NumPy ndarray.ipynb` -> `Numpy/solution/01 - NumPy ndarray.ipynb`

<hr/>

*Last updated: 21 June 2021*<br>
