![ml-notebooks](https://raw.githubusercontent.com/arvest-data-in-context/ml-notebooks/refs/heads/main/docs/images/main-title-card.png)

This is a collection of python notebooks that perform common tasks and demonstrate methods and workflows used in the digital humanities. 
- They can be run either online in [Google Colab](https://colab.research.google.com/) or locally with tools like [JupyterLab](https://jupyter.org/) or [vs code](https://code.visualstudio.com/).
- They are also designed to work with [Arvest](https://arvest.app), a free to use web app that allows you to store your corpora online and view and share the results of machine learning processes.

**⚠️ Please note that these notebooks are pedagogical in tone and configuration. If you are looking for notebooks where all you need to do is drop your media and press play, please visit the [Arvest API Tools](https://github.com/arvest-data-in-context/arvest-api-tools) repo which is designed as a collection of functional tools that follow many of these same workflows.**

1. [Usage](#1-using-the-notebooks)
2. [Content Map](#2-content-map)
3. [Projects](#3-projects)

# 1. Using the notebooks

- The notebooks are designed to require little to no setup from the user (click-and-play): all of the packages needed to run the notebooks are imported and installed at the top of each notebook. 
    - This means that anyone can run the notebook succesfully, however each notebook can take a few moments to set up.
    - Mainly concieved of as examples and as a means of trying things out, the next step would be to use these notebooks as a base for writing your own scripts or notebooks.

## In Google Colabs

Either click on the direct links to open a notebook given in this documentation, or...

1. Go to [Google Colabs](https://colab.research.google.com/).

2. `File` > `Open notebook` > `GitHub` > Paste the url of this repo (`https://github.com/arvest-data-in-context/ml-notebooks`).

3. Choose a notebook to run.

## In JupyterLab or vs code

1. Clone or download this repo onto your machine.

2. Choose a notebook from the [_local](/_local/) folder and run.

# 2. Content Map

What can you find in this repo? Things are broken up into the following sections:

## [Arvest API Tutorials](/docs/arvest/README.md)
This is a good starting point, as it will take you through the Arvest platform and its API, and show you how to manage your media and create IIIF Manifests and porjects to share the results of your work with the world.

## [ML Workflow Tutorials](/docs/workflows/README.md)
Next, you can move on to the workflow tutorials which will take you through a number of common digital humanities workflows.

## [ML Module Tutorials](/docs/modules/README.md)
Finally, we also decompose several machine learning modules in finer detail, if you really want to get into the meat of things.

# 3. Projects

A number of different research projects drove the writing of these notebooks.

- [Arvest](https://arvest.app): these notebooks were written in the context of the development of Arvest, an environment for the manipulation of networks of digital traces.
- [STAGE](https://stage-to-data.huma-num.fr/): an ERC-funded research projet.