🔬 allfed-research
------

Exploratory work for the development of new methods and datasets for ALLFED projects.

Primarily done via Jupyter notebooks (for the time being). More formal structure WIP for repo WIP 
(will most likely use a variant of data science `cookiecutter` template)

### Setup instructions

We recommend using Anaconda, which you can download for your system here:
https://www.anaconda.com/distribution/
 (choose the Python 3.7 version)

#### MacOS / Linux

Assuming you have Anaconda installed, execute the following in a terminal window:

```bash
conda create -n allfed-research python=3.7
conda activate allfed-research
pip install -r requirements.txt
```

#### Windows

Open "Anaconda prompt", which comes with the Anaconda Windows install, execute
the following in an Anaconda prompt window:

```bash
conda create -n allfed-research python=3.7
activate allfed-research
pip install -r requirements.txt
```

### Running notebooks

Once you've completed the setup instructions above, simply execute the following
in your terminal or Anaconda prompt, making sure you're in the `allfed-research`
repo folder.

```bash
jupyter lab
```

This will spawn a new Jupyter instance in your environment, where you can access
the `notebooks` folder of this repository and access / do work.



