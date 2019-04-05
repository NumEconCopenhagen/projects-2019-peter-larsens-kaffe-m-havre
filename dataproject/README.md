# Dataproject

The objective with our dataproject is to show how different key expense figures for the danish municipalities have developed from 2008 to 2017 (I.e. after the municipal reform in 2007). 

In the first part of the project we download data for the development in the long-term debt for each municipalitiy in Denmark from Statistics Denmark, which is avaible in Data folder. The development in the long-term debt for each municipality is then displayed interactively such that one can visually compare the development in the municipality with the mean of country as whole.

In the second part of the project we focus on the entiry country 'Denmark' in its entirety, where we fetch data from Statistics Denmark using an API that showcase the development in 11 key expense figures. These figures are then scaled by the first observation and illustrated graphically. Secondly,we have also choosen to plot them. This is done as away to portray the use of Python to visualize data interactively.   

For you to get the same results in our notebook, you need to download a few packages though anaconda prompt or terminal (if you haven't already ). Needed packages:

pip install pandas-datareader

pip install git+https://github.com/elben10/pydst

# I am not sure if the package below is neccesary, but I/we had difficulties to make the widgets for interactive plot work unless I installed this package:

jupyter labextension install @jupyter-widgets/jupyterlab-manager

