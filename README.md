# D-Lab's Python Web Scraping Workshop

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-Web-Scraping&urlpath=tree%2FPython-Web-Scraping%2F&branch=main)
[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-Web-Scraping/HEAD)

This repository contains the materials for D-Lab’s Python Web Scraping Workshop. Prior experience with Python Fundamentals and Python Data Wrangling is assumed.

## Workshop Goals

In this workshop, we cover how to extract data from the web using Python. We
focus on two approaches to extracting data from the web: leveraging application
programming interfaces (APIs) and web scraping.

APIs are often official services offered by companies and other entites, which
allow one to directly query their servers in order to retrieve their data. When
APIs are not available, one can turn to web scraping, which requires downloading
a webpage's source code and sifting through the material to extract the desired
data. This workshop demonstrates both approaches, their advantages and
disadvantages, and how to use both responsibly.

Basic familiarity with Python is assumed. Understanding the material in the [Python Fundamentals](https://github.com/dlab-berkeley/Python-Fundamentals) and [Python Data Wrangling](https://github.com/dlab-berkeley/Python-Data-Wrangling) workshops highly recommended. We additionally recommend a basic understanding of HTML and CSS.

## Installation Instructions

Anaconda is a useful package management software that allows you to run Python
and Jupyter notebooks very easily. Installing Anaconda is the easiest way to
make sure you have all the necessary software to run the materials for this
workshop. Complete the following steps:

1. [Download and install Anaconda (Python 3.8
   distribution)](https://www.anaconda.com/products/individual). Click
   "Download" and then click 64-bit "Graphical Installer" for your current
   operating system.

2. Download the [Python-Web-Scraping workshop
   materials](https://github.com/dlab-berkeley/Python-Web-Scraping):

* Click the green "Code" button in the top right of the repository information.
* Click "Download Zip".
* Extract this file to a folder on your computer where you can easily access it
  (we recommend Desktop).

3. Optional: if you're familiar with `git`, you can instead clone this
   repository by opening a terminal and entering `git clone
   git@github.com:dlab-berkeley/Python-Web-Scraping.git`.

## Is Python Not Working on Your Computer?

If you do not have Anaconda installed and the materials loaded on your workshop by the time it starts, we *strongly* recommend using the UC Berkeley Datahub to run the materials for these lessons. You can access the DataHub by clicking this button: 

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-Web-Scraping&urlpath=tree%2FPython-Web-Scraping%2F&branch=main)

The DataHub downloads this repository, along with any necessary packages, and allows you to run the materials in a Jupyter notebook that is stored on UC Berkeley's servers. No installation is necessary from your end - you only need an internet browser and a CalNet ID to log in. By using the DataHub, you can save your work and come back to it at any time. When you want to return to your saved work, just go straight to [DataHub](https://datahub.berkeley.edu), sign in, and you click on the `Python-Web-Scraping` folder.

If you don't have a Berkeley CalNet ID, you can still run these lessons in the cloud, by clicking this button:

[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-Web-Scraping/HEAD)

By using this button, however, you cannot save your work.

## Run the code

1. Open the Anaconda Navigator application. You should see the green snake logo appear on your screen. Note that this can take a few minutes to load up the first time. 

2. Click the "Launch" button under "Jupyter Notebooks" and navigate through your file system to the `Python-Web-Scraping` folder you downloaded above.

3. Open the `lessons` folder, and click `01_api.ipynb` to begin.

4. Press Shift + Enter (or Ctrl + Enter) to run a cell.

5. By default, the necessary packages for this workshop should already be installed. You can install them within the Jupyter notebook by running the following line in its own cell:

> ```!pip install -r requirements.txt```

Note that all of the above steps can be run from the terminal, if you're familiar with how to interact with Anaconda in that fashion. However, using Anaconda Navigator is the easiest way to get started if this is your first time working with Anaconda.

# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Other D-Lab Python Workshops

Here are other Python workshops offered by the D-Lab:

## Basic competency

* [Python Fundamentals](https://github.com/dlab-berkeley/python-fundamentals)
* [Introduction to Pandas](https://github.com/dlab-berkeley/introduction-to-pandas)
* [Geospatial Fundamentals in Python](https://github.com/dlab-berkeley/Geospatial-Fundamentals-in-Python)
* [Python Visualization](https://github.com/dlab-berkeley/Python-Data-Visualization)

## Intermediate/advanced competency

* [Computational Text Analysis in Python](https://github.com/dlab-berkeley/computational-text-analysis-spring-2019)
* [Introduction to Machine Learning in Python](https://github.com/dlab-berkeley/python-machine-learning)
* [Introduction to Artificial Neural Networks in Python](https://github.com/dlab-berkeley/ANN-Fundamentals)
* [Fairness and Bias in Machine Learning](https://github.com/dlab-berkeley/fairML)

# Contributors

* [Rochelle Terman](https://github.com/rochelleterman)
* [George McIntire](https://github.com/GeorgeMcIntire)
* [Pratik Sachdeva](https://github.com/pssachdeva)