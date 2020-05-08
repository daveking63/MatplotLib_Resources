<h2>Introduction to Matplotlib</h2>

<b>matplotlib</b> is one of the core (Python) libraries or packages in the well-known, open-source ecosystem <a href='http://scipy.org'>Scipy</a>. Like the other packages in Scipy, it is widely used in mathematical and statistical, scientific and engineering circles. Unlike the other packages, it's primary focus is on 'data visualization,' or more specifically on 2D (and secondarily 3D) charting. While it has unique cababilities, it is rarely used alone.  Instead, it works hand-in-hand with the other core elements of Scipy, especially numpy and pandas which provide their on unique data preparation and analysis features.

matplotlib is 'designed to reproduce as much as possible' the graphic capabilities of Mathwork's extremely popular <a href="https://www.mathworks.com/products/matlab.html">MATLAB</a>. This means that not only does it have extensive capabilities, but it is also relatively straight forward and simple to use. Essentially, charts can be constructed and embellished in a step-by-step fashion, making it relatively easy for first time users to grasp. Towards this end, matplotlib can also be used in an interactive fashion either in an IPython interactive Python shell or a Jupyter Notebook.

There are a wide variety of sources covering in various levels of detail the 'introductory, intermediate, and advanced' features and function of matplotlib. This repository aims to summarize these sources, highlighting their contents and pointers to existing code and Jupyter notebooks. In those cases where notebooks are missing, I'll be provide summary notebooks (either running on the Jupyter nbviewer site or Colab).

<h3>Sources:</h3>

<ul>
  <li>Source: <a href="http://matplotlib.org">Matplotlib.org's</a> user's guide, gallery, and tutorials. This is the group responsible for developing and maintaining the library/package.
    <ul>
    <li>Code: Both the extensive <a href="https://matplotlib.org/gallery/index.html">gallery of examples<a> and the more in-depth <a href="https://matplotlib.org/tutorials/index.html">tutorial guides</a> provide downloadable zip files of Python code or Jupyter notebooks -- gallery_python.zip, gallery_jupyter.zip, tutorial _python.zip, and tutorial_jupyter.zip. This code can also be found on github/maptplotlib/matplotlib. Together they cover an enormous range of chart or plot types, as well as myriad of keyword and parameter setting.</li>
    </ul>
  </li>
  <li>Source: Chapter 7 of <a href="https://www.apress.com/us/book/9781484239124#otherversion=9781484239131">Python Data Analysis with Pandas, Numpy and Matplotlib</a> by Fabio Nelli, Apress, 2018. Explores a range of chart types including: Line, Histogram, Bar, Pie, Countour, Polar, 3D Surfaces, Scatterplots in 3D, Barcharts in 3D, Subplots and Grids of Subplots.
    <ul>
    <li>Code: Jupyter Notebook found on Github at: https://github.com/meccanismocomplesso/python-data-analytics-2e/blob/master/Chapter%207%20-%20Data%20Visualization%20with%20matplotlib.ipynb</li>
    <li>Note: Complete code for the entire book is provided on the same Github site.</li>
    </ul>
  </li>
  <li>Source: <a href="https://www.packtpub.com/big-data-and-business-intelligence/matplotlib-30-cookbook">Matplotlib 3.0 Cookbook</a> by Srinivasa Rao Poladi, Packt Publishing, 2018. Soup to nuts coverage of charting fundamentals, as well as discussions and examples of various aspects of the backend, artist and scripting layers.  In Chapter 2, specific examples devoted to: Line plot, Bar plot, Scatter plot, Bubble plot, Stacked plot, Pie plot, Table chart, Polar plot, Histogram, Box plot, Violin plot, Heatmap, Hinton diagram, Images, Contour plot, Triangulations, Stream plot, and Path. In Chapter 3, focus is on multiple plots and subplots.
    <ul>
    <li>Code: Jupyter Notebook found on Github at: https://github.com/PacktPublishing/Matplotlib-3.0-Cookbook.</li>
    </ul>
  </li>
  <li>Source: <a href="https://www.packtpub.com/big-data-and-business-intelligence/matplotlib-python-developers-second-edition">Matplotlib for Python Developers - Second Edition</a> by Aldrin Yim, Claire Chung, Allen Yu. Packt Publishers, April 2018. Practical, hands-on resource to help you visualize data with Python using the Matplotlib library. Shows you how to create attractive graphs, charts, and plots using Matplotlib. Also, provides quick introduction to third-party packages, Seaborn, Pandas, Basemap, and Geopandas, and learn how to use them with Matplotlib.
   <ul>
     <li>Code: Jupyter Notebook's found on Github at: https://github.com/PacktPublishing/Matplotlib-for-Python-Developers-Second-Edition</li>
    </ul>
  </li>
  <li>Source: Chapter 4 of <a href="https://www.apress.com/us/book/9781484242452#otherversion=9781484242469">Numerical Python: Scientific Computing and Data Science Applications with Numpy, SciPy and Matplotlib (2nd Edition)</a> by  Robert Johansson, Apress Publisher, 2019. Chapter 4 focuses on the use of matplotlib in generating and displaying the "plots and figures used to visualize results and data in scientific and technical disciplines, suc as line, bar, contour, colormap and 3D surface plots."
   <ul>
     <li>Code: found on Github at https://github.com/Apress/numerical-python-second-ed/blob/master/ch04-code-listing.ipynb</li>
     <li>Note: Complete code for the entire book is provided on the same Github site.</li>
   </ul>
   </li>   
  <li>Source: <a href="https://www.datacamp.com/community/tutorials/matplotlib-tutorial-python">Matplotlib Tutorial: Python Plotting</a> by Karlijn Willems, Dec 2019. Tutorial covers the basics Python data visualization including: anatomy of a Matplotlib plot; plot creation; plotting routines; basic plot customizations; saving, showing and clearing plots; and customizing plots.
    <ul>
      <li>Code: Interactive code is provided within the tutorial.</li>
    </ul>
  </li>
</ul>
