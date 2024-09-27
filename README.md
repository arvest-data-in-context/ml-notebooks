# ml-notebooks

This is a collection of python notebooks that perform common tasks and demonstrate methods used in the digital humanities. 
- They can be run either online in [Google Colab](https://colab.research.google.com/) or locally in [JupyterLab](https://jupyter.org/).
- They are designed to require no setup from the user (click-and-play): all of the packages needed to run the notebooks are imported and installed at the top of each notebook. 
    - This means that anyone can run the notebook succesfully, however each notebook can take a few moments to set up.
    - Mainly concieved of as examples and as a means of trying things out, the next step would be to use these notebooks as a base for writing your own scripts of notebooks.
    - To keep things clean, we have also created two repos which are python packages containing common utility functions (one for [Colab](https://github.com/arvest-data-in-context/gcu), one for [JupyterLab](https://github.com/arvest-data-in-context/jlu)).
- These notebooks are notably great for a workshop or pedagogical setting.

1. [ML Map](#ml-map)
2. [Usage](#using-the-notebooks)
3. [Projects](#projects)
4. [Roadmap](#roadmap)

## 1. ML Map

This project is part of a larger effort to map the different workflows that are possible in the digital humanities thanks to machine learning. For an interactive map that gives an overview of the contents of this repo, please look [here](www.arvest.learn/ml).

The notebooks are broken down into modules (the building blocks of machine learning workflows) and workflows (different modules chained together in larger notebooks representing common DH workflows). 

### Modules

1. **Source Extraction**: notebooks for finding sources from things like websites or online databases.

2. **Conversion**: notebooks for converting media into different formats.

3. **Decomposition**: notebooks for breaking down media across different dimensions.

4. **Feature Extraction**: notebooks for extracting data out of media.

5. **Database Management**: notebooks for dealing with large collections of data.

6. **Collection Processing**: notebooks for performing processing tasks on large collections of data.

7. **Visualization**: notebooks for visualizing data.

8. **Other**: ad hoc methods that don't fall easily into the other categories.

### Workflows:

1. **Distant Reading**: various workflows for making the computer read and extract data from written sources.

2. **Distant Viewing**: various workflows for making the computer view and extract data from visual sources.

3. **Distant Listening**: various workflows for making the computer listen and extract data from audio sources.

## 2. Using the notebooks

### In Google Colabs

1. Go to [Google Colabs](https://colab.research.google.com/).

2. File > Open notebook > GitHub > Paste the url of this repo (https://github.com/arvest-data-in-context/ml-notebooks).

3. Run the notebook you want from the [colab](/colab/) folder.

### In JupyterLab

1. Clone or download this repo onto your machine.

2. Download [Anaconda](https://www.anaconda.com/).

3. Launch JupyterLab from the Anaconda-Navigator.

4. Run the notebook you want from the [jupyter](/jupyter/) folder.

## 3. Projects

A number of different research projects drove the writing of these notebooks. Some notebooks from these projects are included in this repo.

- [Arvest](https://arvest.gitpages.huma-num.fr/): these notebooks were written in the context of the development of Arvest, an environment for manipulation networks of digital traces.

## Roadmap

See what is implemented, and what will soon be implemented [here](/docs/roadmap.md).