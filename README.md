# Krafthack-2022

Team Data Liberators: Hayden, Simon, Andris

## Summary

This repo looks at using the KraftHack data to do the following:
* Develop a model that can predict the strain rates of 6 different bolts for Kvilldal Hydropower plant
* Use the models to calclate end-of-life of each bolt based on strain threshold of 3000 um/m

## Structure

The repo is structured as follows:

* The main notebook that should be evaluated is `main-notebook.ipynb`. 
* Data exploration notebooks can be found in the `data-exploration` folder. We particularily recommend the `dataset_exploration.html` file which is a very good summary of dataset 2.
* Machine learning scripts that were used to develop the final model can be found in `machine-learning-notebooks` folder
* Slide deck can be found in the `slide-decks` folder

## Getting started

We use poetry to control our python packages. Installation instructions can be found here:https://python-poetry.org/docs/. After you have done that, you can follow the following steps:

* `git clone` the repo on your local machine
* Install all required packages with poetry `poetry install`
* Make sure all data is stored locally under `data`

## Main conclusions

The model achieves good performance on test and training set and can be used to predict end-of-life for each bolt. See image below:

![image](https://user-images.githubusercontent.com/29730122/157108130-d38cfa6f-f097-4d8a-89e5-bed45960759f.png)



Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
