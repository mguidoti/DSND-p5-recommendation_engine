# README

> This is my work for the fifth project of the Data Scientist Nanodegree Program from Udacity.

In this project we work with IBM user-article interaction dataset to implement a recommendation system based on collaborative filtering and matrix factorization (SDV).


## Disclaimer
I applied the [Udacity Git Commit Message Style Guide](https://udacity.github.io/git-styleguide/) in this repository, with one addition to the type list: `file`, used when I uploaded or changed non-coding files, like the pickle file.

I also used [Pipenv](https://pipenv-fork.readthedocs.io/en/latest/), hence the [Pipfile](https://github.com/mguidoti/DSND-p1-blog/blob/master/Pipfile) and [Pipfile.lock](https://github.com/mguidoti/DSND-p1-blog/blob/master/Pipfile.lock) in this repository.


## Files
```
|--data
  |--articles_community.csv                 # Raw data with all articles
  |--user-item-interactions.csv             # Raw data with all user-articles interactions
|--.gitignore
|--LICENSE
|--Pipfile
|--Pipfile.lock
|--project_tests.py                         # Tests routines
|--README.md
|--Recommendations_with_IBM.ipynb           # Jupyter Notebook with all code
|--top_5.p                                  # Pickle file used in tests
|--top_10.p                                 # Pickle file used in tests
|--top_20.p                                 # Pickle file used in tests
|--user_item_matrix.p                       # Pickle file used to load matrix for Part V
```


## Installing & Running
It's advisable to install Pipenv and run `pipenv install` in the cloned directory to install all packages and their dependencies in a new virtual environment. Then, open the jupyter notebook and make sure your kernel is set to the virtual environment that you created.


## Acknowledgements
Lots of Numpy and Pandas documentation reading, tons of Stack Overflow browsing (but special thanks to [this question](https://stackoverflow.com/questions/7340019/sort-values-and-return-list-of-keys-from-dict-python)), and a few GitHub repositories of former students:

- [Anka-Liu's](https://github.com/Anka-Liu/Data-Science-Nanodegree)
- [Sajjadmanal](https://github.com/Sajjadmanal/Udacity-Data-Scientist-Nanodegree)
- [chen-bowen](https://github.com/chen-bowen/Data_Science_Portfolio)
- [SThornewllvE](https://github.com/SThornewillvE/Udacity-DataScience-Nanodegree) <-- This repo is awesome!


## License
MIT