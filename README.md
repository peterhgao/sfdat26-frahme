## SF DAT 26 Course Repository

Course materials for General Assembly's Data Science course in San Francisco, CA (8/10/16 - 10/19/16).

**Instructors:** [Sinan Ozdemir](https://www.linkedin.com/in/sinan-ozdemir-10568534) 
**Teaching Assistants:**
[Peter Gao](https://www.linkedin.com/in/peterhgao) / [Cari Levay](https://www.linkedin.com/in/carilevay)

**Course Times**

Monday/Wednesday: 6:30pm - 9:30pm

**Office hours:** 

TBD

All courses / office hours will be held in the student center at GA, 225 Bush Street

**[Course Project Information](project.md)**

**[Course Project Examples](project-examples.md)**


Monday | Wednesday | Project Milestone | HW
--- | --- | --- | ---
No Class | 8/10: Introduction / Expectations / Intro to Data Science
8/15: Pandas | 8/17: APIs / Web Scraping 101 | | HW 1 Assigned (W)
8/22: Intro to Machine Learning / KNN | 8/24: Linear Regression / Model Evaluation | Three Potential Project Ideas (W) | 
8/29: Model Evaluation Con't / Logistic Regression | 8/31:  / Natural Language Processing ||HW 1 Due (W)
9/5: Labor Day (No Class) | 9/7: Naive Bayes Classification || 
9/12: Advanced Sklearn (Pipeline and Feaure Unions) | 9/14: Review | |HW 2 Assigned (W)
9/19: Decision Trees | 9/21: Ensembling Techniques | First Draft Due (W) | 
9/26: Dimension Reduction | 9/28: Clustering / Topic Modelling | Peer Review Due (M)
10/3: Neural Networks / Deep Learning | 10/5: Stochastic Gradient Descent | |HW 2 Due (W)
10/10: Recommendation Engines | 10/12: Web Development with Flask | |
10/17: Data Science in Practice / Projects | 10/19: Projects | Git Er Done | Git Er Done


### Installation and Setup
* Install the [Anaconda distribution](http://continuum.io/downloads) of Python 2.7x.
* Setup a [conda virtual environment](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/)
* Install [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and create a [GitHub](https://github.com/) account.
* Once you receive an email invitation from [Slack](https://slack.com/), join our "SFDAT26 team" and add your photo!

### Resources
* [PEP 8 - Style Guide for Python](http://www.python.org/dev/peps/pep-0008)
* [Learn How to Think Like a Computer Scientist](http://interactivepython.org/runestone/static/thinkcspy/toc.html#t-o-c)
* Potential book for course? [:)](https://www.amazon.com/Principles-Data-Science-Sinan-Ozdemir-ebook/dp/B01A8T8YNC)


##Introduction / Expectations / Intro to Data Science

Agenda

* Introduction to General Assembly [slides](slides/01_DAT_intro_deck.pdf)
* Course overview: our philosophy and expectations ([slides](slides/01_course_overview.pdf))
* Ice Breaker

Break -- [**Command Line Tutorial**](http://generalassembly.github.io/prework/cl)

* Figure out office hours
* Intro to Data Science: [slides](slides/01_intro_to_data_science.pdf)

Homework


* Setup a [conda virtual environment](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/)
* Install [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and create a [GitHub](https://github.com/) account.
	* Read my intro to [Git](slides/01_git.pdf) and be sure to come back on monday with your very own repository called "sfdat26-lastname"
* Once you receive an email invitation from [Slack](https://slack.com/), join our "SFDAT26 team" and add your photo!
* Introduction on how to read and write iPython notebooks [tutorial](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/intro_to_ipython_notebooks.ipynb)


### Class 2: Introduction to Pandas

####Goals

* Feel comfortable importing, manipulating, and graphing data using Python's Pandas
* Be able to find missing values and begin to have a sense of how to deal with them


####Agenda

* Don't forget to `git pull` in the sfdat26 repo in your command line
* Intro to Pandas walkthrough [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/02_pandas.ipynb)
	* [Pandas Lab 2](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/labs/02_pandas_lab.ipynb)

####Homework
* Go through the python class/lab work and finish any exercise you weren't able to in class
* Make sure you have all of the repos cloned and ready to go
	* You should have both "sfdat26" and "sfdat26_work"
* Read Greg Reda's [Intro to Pandas](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/)
* Take a look at Kaggle's [Titanic competition](https://www.kaggle.com/c/titanic)
* I will be using a module called `tweepy` next time. 
	* To install please type into your console `conda install tweepy` 
		* OR if that does not work, `pip install tweepy`

#### Resources:
* Another Git tutorial [here](http://try.github.io)
* In depth Git/Github tutorial series made by a GA_DC  Data Science Instructor [here](https://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD)
* [Another Intro to Pandas](http://nbviewer.ipython.org/gist/wesm/4757075/PandasTour.ipynb) (Written by Wes McKinney and is adapted from his book)
	* [Here](https://vimeo.com/59324550) is a video of Wes McKinney going through his ipython notebook!
* Examples of [joins in Pandas](http://www.gregreda.com/2013/10/26/working-with-pandas-dataframes/#joining)
* For more on Pandas plotting, read the [visualization page](http://pandas.pydata.org/pandas-docs/stable/visualization.html) from the official Pandas documentation.

#### Next Time on SFDAT26...

* Maria finds out that Sancho has been cheating on her with her.. mother!
* We will use python to programatically obtain data via open sources on the internet
	* We will be scraping the [National UFO reporting center](http://nuforc.org/)
	* We will be collecting tweets regarding Donald Trump and Hilary Clinton
	* We will be examining What people are really looking for in a data scientist..
	
* We will continue to use pandas to investigate missing values in data and have a sense of how to deal with them


### Class 3: APIs / Web Scraping 101

####Agenda

* To install tweepy please type into your console `conda install tweepy` 
	* OR if that does not work, `pip install tweepy`
* Slides on Getting Data [here](slides/03_getting_data.pdf)
* Intro to Regular Expressions [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/03_regex_example.ipynb)
* Getting Data from the open web [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/03_getting_data_from_web.ipynb)
* Getting Data from an API [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/03_getting_data_from_api.ipynb)
* LAB on getting data [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/labs/03_getting_data_lab.ipynb)

####Homework
* The first homework will be assigned by tomorrow morning (in a homework folder) and it is due in two Wednesdays (8/31)
	* It is a combo of pandas question with a bit of API/scraping
	* Please push your completed work to your sfdat26_work repo for grading
* Your [first project milestone](project.md) is due next Wednesday. It is the first three ideas you have for your project. Think about potential interesting sources of data you would like to work with. This can come from work, hobby, or elsewhere!

####Resources:

* [Mashape](https://www.mashape.com/) allows you to explore tons of different APIs. Alternatively, a Python API wrapper is available for many popular APIs.
* [The Data Science Toolkit](http://www.datasciencetoolkit.org/) is a collection of location-based and text-related APIs.
* [API Integration in Python](https://realpython.com/blog/python/api-integration-in-python/) provides a very readable introduction to REST APIs.
* [Microsoft's Face Detection API](https://www.microsoft.com/cognitive-services/en-us/face-api#detection), which powers [How-Old.net](https://how-old.net/), is a great example of how a machine learning API can be leveraged to produce a compelling web application.
Web Scraping Resources:
* For a much longer web scraping tutorial covering Beautiful Soup, lxml, XPath, and Selenium, watch [Web Scraping with Python](https://www.youtube.com/watch?v=p1iX0uxM1w8) (3 hours 23 minutes) from PyCon 2014. The slides and code are also available.
* [import.io](https://www.import.io/) and [Kimono](https://www.kimonolabs.com/) claim to allow you to scrape websites without writing any code. Its alrighhhtttttt
* [How a Math Genius Hacked OkCupid](http://www.wired.com/2014/01/how-to-hack-okcupid/all/) to Find True Love and [How Netflix Reverse Engineered](http://www.theatlantic.com/technology/archive/2014/01/how-netflix-reverse-engineered-hollywood/282679/?single_page=true) Hollywood are two fun examples of how web scraping has been used to build interesting datasets.

### Class 4: Intro to Machine Learning / KNN

####Agenda

* Iris pre-work [code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/04_iris_prework.ipynb)
	* Using numpy to investigate the iris dataset further
	* Understanding how humans learn so that we can teach the machine!
	* If nedded, read intro to numpy [code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/04_numpy_ref.ipynb)
		* Numerical Python, code adapted from tutorial [here](http://www.engr.ucsb.edu/~shell/che210d/numpy.pdf)
		* Special attention to the idea of the np.array

* Intro to Machine Learning and KNN [slides](slides/04_ml_knn.pdf)
	* Supervised vs Unsupervised Learning
	* Regression vs. Classification

* [Lab](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/labs/04_knn_lab.ipynb) to use KNN models to investigate accelerometer data


####Homework

* The one page project milestone as well as the pandas homework! [See requirements here](project.md)
* Read this excellent article, [Understanding the Bias-Variance Tradeoff](http://scott.fortmann-roe.com/docs/BiasVariance.html), and be prepared to discuss it in class on Wednesday. (You can ignore sections 4.2 and 4.3.) Here are some questions to think about while you read:
    * In the Party Registration example, what are the features? What is the response? Is this a regression or classification problem?
    * In the interactive visualization, try using different values for K across different sets of training data. What value of K do you think is "best"? How do you define "best"?
    * In the visualization, what do the lighter colors versus the darker colors mean? How is the darkness calculated?
    * How does the choice of K affect model bias? How about variance?
    * As you experiment with K and generate new training data, how can you "see" high versus low variance? How can you "see" high versus low bias?
    * Why should we care about variance at all? Shouldn't we just minimize bias and ignore variance?
    * Does a high value for K cause over-fitting or under-fitting?
* For our talk on linear regression, read:
	* This [explanation](http://blog.minitab.com/blog/adventures-in-statistics/how-to-correctly-interpret-p-values) of p values
	* [Correlation does not imply Causation](http://tylervigen.com/spurious-correlations)
	* [P-values can't always be trusted](http://fivethirtyeight.com/features/science-isnt-broken/#part2)
	
    
**Resources:**

* For a more in-depth look at machine learning, read section 2.1 (14 pages) of Hastie and Tibshirani's excellent book, [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/). (It's a free PDF download!)
* Stackoverflow article on the difference between generative and discriminative models [here](http://stackoverflow.com/questions/879432/what-is-the-difference-between-a-generative-and-discriminative-algorithm)




### Class 5: Model Evaluation Procedures / Linear Regression

**Agenda**

* Discusss with people at your table about your three potential ideas.
	* Try to figure out which kinds of machine learning would be appropiate
		* supervised
		* unsupervised
* Model evaluation procedures ([slides](slides/05_model_evaluation_procedures.pdf), [code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/05_model_evaluation.ipynb))
* Linear regression ([notebook](http://nbviewer.ipython.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/05_linear_regression.ipynb))
	* To run this, I use a module called "seaborn" 
	* To install to anywhere in your terminal (git bash) and type in `sudo pip install seaborn`
	* In depth slides [here](slides/05_linear_regression.pdf)
* LAB -- Yelp dataset [here](labs/05_yelp_reviews.md) with the [Yelp reviews data](data/yelp.csv). It is not required but your next homework will involve this dataset so it would be helpful to take a look now!
* Discuss the [article](http://scott.fortmann-roe.com/docs/BiasVariance.html) on the bias-variance tradeoff
* Look as some [code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/05_bias_variance_tradeoff.ipynb) on the bias variace tradeoff
	


**Homework:**

* Please upload your three potential ideas for your final project to your personal sfdat26_work repo
	* [Here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) is a markdown cheatsheet for making your very own markdown files
	* I recommend [Macdown](http://macdown.uranusjr.com/) editor for mac users and [MarkPad](http://code52.org/DownmarkerWPF/) for windows users
* Watch these videos on [probability](https://www.youtube.com/watch?v=o4QmoNfW3bI) and [odds](https://www.youtube.com/watch?v=GxbXQjX7fC0) (8 minutes) if you're not familiar with either of those terms.
* Read these excellent articles from BetterExplained: [An Intuitive Guide To Exponential Functions & e](http://betterexplained.com/articles/an-intuitive-guide-to-exponential-functions-e/) and [Demystifying the Natural Logarithm (ln)](http://betterexplained.com/articles/demystifying-the-natural-logarithm-ln/).
* [Homework 1](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/hw/hw1.ipynb) is due in **7 days**!

**Resources:**

* [Correlation does not imply Causation](http://tylervigen.com/spurious-correlations)
* [P-values can't always be trusted](http://fivethirtyeight.com/features/science-isnt-broken/#part2)
* Setosa has an excellent [interactive visualization](http://setosa.io/ev/ordinary-least-squares-regression/) of linear regression.
* To go much more in-depth on linear regression, read Chapter 3 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), from which this lesson was adapted. Alternatively, watch the [related videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) or read my [quick reference guide](http://www.dataschool.io/applying-and-interpreting-linear-regression/) to the key points in that chapter.
* To learn more about Statsmodels and how to interpret the output, DataRobot has some decent posts on [simple linear regression](http://www.datarobot.com/blog/ordinary-least-squares-in-python/) and [multiple linear regression](http://www.datarobot.com/blog/multiple-regression-using-statsmodels/).
* This [introduction to linear regression](http://people.duke.edu/~rnau/regintro.htm) is much more detailed and mathematically thorough, and includes lots of good advice.
* This is a relatively quick post on the [assumptions of linear regression](http://pareonline.net/getvn.asp?n=2&v=8).
* John Rauser's talk on [Statistics Without the Agonizing Pain](https://www.youtube.com/watch?v=5Dnw46eC-0o) (12 minutes) gives a great explanation of how the null hypothesis is rejected.
* A major scientific journal recently banned the use of p-values:
    * Scientific American has a nice [summary](http://www.scientificamerican.com/article/scientists-perturbed-by-loss-of-stat-tools-to-sift-research-fudge-from-fact/) of the ban.
    * This [response](http://www.nature.com/news/statistics-p-values-are-just-the-tip-of-the-iceberg-1.17412) to the ban in Nature argues that "decisions that are made earlier in data analysis have a much greater impact on results".
    * Andrew Gelman has a readable [paper](http://www.stat.columbia.edu/~gelman/research/unpublished/p_hacking.pdf) in which he argues that "it's easy to find a p < .05 comparison even if nothing is going on, if you look hard enough".
* An article on ["P Hacking"](http://www.dailydot.com/geek/data-manipulation-tool-science-p-hacking/) the idea that you can alter data in order to achieve good p values
* Here's a great [30-second explanation of overfitting](http://www.quora.com/What-is-an-intuitive-explanation-of-overfitting/answer/Jessica-Su).
* For more on today's topics, these videos from Hastie and Tibshirani are useful: [overfitting and train/test split](https://www.youtube.com/watch?v=_2ij6eaaSl0) (14 minutes), [cross-validation](https://www.youtube.com/watch?v=nZAM5OXrktY) (14 minutes). (Note that they use the terminology "validation set" instead of "test set".)
    * Alternatively, read section 5.1 (12 pages) of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), which covers the same content as the videos.
* This video from Caltech's machine learning course presents an [excellent, simple example of the bias-variance tradeoff](http://work.caltech.edu/library/081.html) (15 minutes) that may help you to visualize bias and variance.