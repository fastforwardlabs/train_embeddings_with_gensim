# Learning item embeddings with Gensim's Word2Vec
[Gensim]() provides one of the most well-known and oft-used implementations of the Word2Vec algorithm for learning word embeddings over natural langauage. However, this is not the only use case. 

### TODO
- [] some kind of figure to jazz up the README
- [] fix broken links in the **Deploying on CML** section

## Deploying on Cloudera Machine Learning (CML)
There are three ways to launch this notebook on CML:

* **From Prototype Catalog** - Navigate to the Prototype Catalog in a CML workspace, select the "Analyzing News Headlines with SpaCy" tile, click "Launch as Project", click "Configure Project"
* **As ML Prototype** - In a CML workspace, click "New Project", add a Project Name, select "ML Prototype" as the Initial Setup option, copy in the repo URL, click "Create Project", click "Configure Project"
* **Manual Setup** - In a CML workspace, click "New Project", add a Project Name, select "Git" as the Initial Setup option, copy in the repo URL, click "Create Project".

Once the project has been initialized in a CML workspace, run the notebook by starting a Python 3 Jupyter notebook server session. All library and model dependencies are installed inline in the notebook.

Happy hacking!