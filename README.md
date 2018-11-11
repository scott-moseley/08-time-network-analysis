# Core skills program - week 9 - Special Data Types

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/core-skills/08-time-network-analysis.git/master)

Today's session will introduce techniques to handle time series data. We will have a look at optimisation and genetic algorithms (GA), linear autoregressive models (AR), local constant models, and nonlinear global models. We will also discuss the complex network approach to time series data and how to use network properties to get insights about your data.  

You should aim to understand:

- The main features and limitation of computational optimisation and its importance for data science.
- How to implement a simple genetic algorithm.
- The distinction between prediction and simulation for time series analysis and the  several existing approaches.
- How to use the package **networkx** to calculate several network quantification measures and how to interpret the measures.
- The challenges and possible solutions for an industry scale network optimisation strategy.


## Pre-session Reading & Resources

We will use python notebooks exercises on different datasets to have a practical go on the discussed methods in practise. Have a go and check if everything is running on your machine before the class. The environment provided for this week will install python 3.5 and GDAL on your machine.  Please, use *environment_mac.yml* if you use Mac and *environment_win.yml* if you use Windows.

Note: python 3.6 may not work well on Windows machines and GDAL has also some problems with this more recent python version.  

For the complex network analysis, we will use **networkx**. You can find the documentation of  this package [here](https://networkx.github.io). 

To work on the available industry datasets provided for this week, we need to be able to read *.shp* files, and for that we will use the GDAL (Geospatial Data Abstraction Library) library - you can reading about it [here](https://www.gdal.org). 

Stack Overflow is a useful website to find solutions for when you get stuck with python and libraries: 
https://stackoverflow.com/questions/tagged/networkx
https://stackoverflow.com/questions/tagged/gdal.

**References and Pre-reading**:

Genetic Algorithms with Python - Clinton Sheppard.
Source code from the book: https://github.com/handcraftsman/GeneticAlgorithmsWithPython

M. Small. Applied Nonlinear Time Series Analysis: Applications in Physics, Physiology and Finance. Nonlinear Science Series A, vol. 52. World Scientific, 2005. 

M. Small. Dynamics of Biological Systems., Mathematics and Computational Biology Series, Chapman & Hall/CRC, 2011.

Network Science by A.-L. Barabási: http://networksciencebook.com

Networks: An Introduction by Mark E. J. Newman
https://www.amazon.com/Networks-Introduction-Mark-Newman/dp/0199206651
