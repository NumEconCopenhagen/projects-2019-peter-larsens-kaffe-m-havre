# Dataproject

Dataproject 

The objective with our dataproject is to show how different key expense figures for the danish municipalities have developed from 2008 to 2018 (I.e. after the municipal reform in 2007).
In the first part of the project we download data for the development in the long-term debt for each municipalitiy in Denmark from Statistics Denmark, which is avaible in Data folder. The development in the long-term debt for each municipality is then displayed interactively such that one can visually compare the development in the municipality with the mean of the country as whole.
In the second part of the project we focus on the entire country 'Denmark' , where we fetch data from Statistics Denmark using an API that showcase the development in 11 key expense figures. These figures are then scaled by the first observation and illustrated graphically. We have also chosen to plot them. This is done to portray the use of Python to visualize data interactively.
For you to get the same results in our notebook, you need to download a few packages through anaconda prompt or terminal. The following packages are required. 
pip install pandas-datareader 
pip install git+https://github.com/elben10/pydst
We are not sure if the package below is neccesary, but we had difficulties to make the widgets for interactive plot work unless we installed this package:
jupyter labextension install @jupyter-widgets/jupyterlab-manager

