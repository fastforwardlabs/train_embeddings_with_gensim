# Learning item embeddings with Gensim's Word2Vec
With support for hyperparameter optimization and early stopping. 


### TODO
- [] clean up the Jupyter notebook and add more documentation
- [] some kind of figure to jazz up the README
- [] install script because I think it's too much for the jupyter notebook
- [] fill out the yaml to include running the scripts as jobs?
- [] alternatively, include instructions in the `scripts` directory on how to run them separately?
- [] fix broken links in the **Deploying on CML** section

## Deploying on Cloudera Machine Learning (CML)
-----
There are three ways to launch this notebook on CML:

* **From Prototype Catalog** - Navigate to the Prototype Catalog in a CML workspace, select the "Analyzing News Headlines with SpaCy" tile, click "Launch as Project", click "Configure Project"
* **As ML Prototype** - In a CML workspace, click "New Project", add a Project Name, select "ML Prototype" as the Initial Setup option, copy in the repo URL, click "Create Project", click "Configure Project"
* **Manual Setup** - In a CML workspace, click "New Project", add a Project Name, select "Git" as the Initial Setup option, copy in the repo URL, click "Create Project".

Once the project has been initialized in a CML workspace, run the notebook by starting a Python 3 Jupyter notebook server session. All library and model dependencies are installed inline in the notebook.

Happy hacking!