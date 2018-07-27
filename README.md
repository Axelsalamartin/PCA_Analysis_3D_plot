# PCA Analysis

Creating a PCA analysis of the Iris data set and then create an interactive 3D plot to display the result.

## What is the point of PCA ( Primary Component Analysis ) ?

When you have a lot of features it's hard to visualize how the data is placed inside the multidimensional space. PCA allows to see how the data is dispatched in a lower dimensional space and it makes it easier, for exemple, to visualize clusters.
Here we squash the features of the flowers into 3 primary components because we want a 3D plot. If we only want to see a 2D plot we would need to set the number of PCA down to 2.

The interactive plots are being done with 2 different methods : 

 - 1 - Matplotlib 
 - 2 - Plotly
 
PS - To get the "Plotly" plot you need to run the notebook cell with your own credentials (read the "Important Comment" inside the notebook).
