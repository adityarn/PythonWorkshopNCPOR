# Python Workshop for the National Center for Polar and Ocean Research (NCPOR)

## Getting Getting Started

Hello Everyone!

Welcome to the Python Workshop! This week-long module will introduce you to the basics of using the Python programming language for scientific computing. The workshop will run from the [*insert dates here*]. We will be using the following Webex link: [*insert link here*]

We will begin with an introduction to the basics of Python. The module does not assume any prior programming experience or knowledge and is designed to be friendly to absolute beginners. That said, we would also like to provide a challenge, that both beginners and more advanced learners may find interesting! We will introduce the packages in Python that are commonly used in scientific computing and data visualization. The final exercises will involve handling real-life data from the lab and the field! All the material is available on the [Github repository](https://github.com/adityarn/PythonWorkshopNCPOR) in the form of “Python notebooks”. You can view these noteboooks directly on Github. When you download them to your laptop, you will need to [install Python](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) and launch a [Jupyterlab session](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) first before you are able to view them. Please make sure you've also installed necessary packages to your machines, using the environment.yml file provided in this repository.

### Recommended Installation Procedure

Conda is a package manager that help avoid conflicts between installed Python packages. It can also create virtual environments within which different sets of Python packages may be installed.

1. You'll find the installation files for Conda [here](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).
2. Once you've installed conda, download the environment.yml file available in the Github repository.
3. You can create an environment by opening up the terminal and typing the following code.: ```conda env create -f environment.yml ```
4. Next activate your environment: ```conda activate oceanpy```
5. You should now have all the packages necessary for the course available within this environment!
6. Next, launch jupyterlab in the terminal: ```jupyter lab```
7. Your OS will launch Jupyter Lab in your default web browser.
8. You can now open any jupyter notebook within Jupyter Lab.

Python notebooks are interactive environments where you can write code, visualize the output, and write documentation as well. You can also download all the material needed for the workshop from this Github repository.


### Course Syllabus

|Day|Topic|
|---|---|
|1|Pure Python basics -- data types, lists, for loops, conditional statements, functions. How to read documentation on libraries and functions.|
|2|Numpy arrays, slicing, efficient vectorized operations versus pure Python operations.|
|3|Computation on Numpy arrays, indexing, broadcasting, boolean masks. Intro to Pandas: Series, Dataframes, indexing, selection, boolean selection.|
|4| Matplotlib: scatter, line, fill_between, bar, contour, contourf, pcolormesh, quiver. Modifying plot elements: axis labels, legends, axis limits, title, figsize, subplots, gridspec.GridSpec|
|5| Introduction to Pandas for data analysis. Analysis of Lagrangian float data.|
|6|Pandas contd. -- analysis of Pseudocalanus prosome length.|
|7| Gridded datasets: analysis using Xarray, mapping using Cartopy|



### Important Note

To get the most out of this course, I recommend that you follow along each lesson while running the same Python notebook on your laptop. This will allow you to learn by interacting with the code live in the classroom. I encourage you to play with the code, modify things, and break things if you must. This is the best way to learn by doing!

The pace in the class may be too overwhelming for many beginners. But this course is only meant to provide an introduction to programming and to give you tools to try and learn and solve problems on your own. We will learn how to read error messages and how to use tools such as the package documentation, Stackoverflow, and ChatGPT to fix our code.

A great source of reference material for much of the topics that we will cover in the workshop is [JakeVanderPlas’ book, Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/). This book has free Python notebooks too, which you can download and start learning interactively from! You can reach out to me at a.narayanan@soton.ac.uk if you have any questions. I look forward to meeting you all and beginning our Python journey together!


### Course Schedule

|Session|Time|Date|Link|
|---|---|---|---|
|Session 1| 10am to 12pm| December 5th, 2023 | Webex link TBA|
|Session 2| 10am to 12pm| December 12th, 2023| Webex link TBA|
|Session 3| Time TBA    | Date TBA         | Webex link TBA|


