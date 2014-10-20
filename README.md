<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-50532302-3', 'auto');
  ga('send', 'pageview');

</script>

##Data Science Resources

This repo is intended to provide open source resources to facilitate learning or point practicing/aspiring data scientists in the right direction.  Truth be told it exists so that I can keep track of resources that were helpful to me at a given time.  

I aim to cover the full spectrum of data science and to hopefully include topics of data science that aren't either actively covered or easy to find in the open-source world. I haven't focused on in-depth machine learning theory since that is well covered.  If you are looking for ML theory I would look to some of the online courses, books or bootcamps. There is a lot of theory information available online, some is linked lower on this page [here](#other-open-source-data-science-content), [here](#data-science-courses) and many purchasable books. 

This is a constant work in progress. If you have anything to add, any feedback, or would like to be a contributor - please reach out.  If there are any mistakes or typos, be patient with me but please let me know.      

Lastly, I would add that a large portion of data science is exploratory data analysis and properly cleaning your data to implement the tools and theory necessary to solve the problem at hand.  For each problem there are many different ways and tools to execute a successful solution - so if one method isn't working re-evaluate, re-work the problem, try another approach or reach out to the community for support.  Good luck and I hope this repo is helpful!

#Table Of Contents
1. [Data Science Getting Started](#data-science-getting-started)   
  * [Data Science Courses](#data-science-courses)  
  
1. [Data Pipeline & Tools](#data-pipeline--tools) 
  * [Python](#python)  
  * [Stats/Engineering Libraries](#statsengineering-libraries)  
  * [Databases/Frameworks](#databasesframeworks)  
  * [Data Acquisition](#data-acquisition)  
  * [Processing & EDA](#processing--exploratory-data-analysis)  
  * [Machine Learning](#machine-learning)  
  ** [Feature Engineering](#feature-engineering)  
  * [Data Visualization](#data-visualization)  
  * [ipython Notebook Tutorials](#ipython-notebook-tutorials)  
  * [Additional Tools or Processes](#additional-tools-or-processes)  
  * [Data Sources](#data-sources)  
  * [New Data Tools](#new-data-tools) 

1. [Product](#product)
  * [Product Metrics](#product-metrics)     

1. [Career Resources](#career-resources)
  * [Data Science Career Path](#data-science-career-path)    
  * [Types of Data Scientists](#types-of-data-scientists)  
  * [Data Science Applications/Use Cases](#data-science-applicationsuse-cases)  
  * [Data Science Websites/Books](#data-science-websitesbooks)  
  * [Data Science Meetups in the Bay Area](#data-science-meetups-in-the-bay-area)  
  * [Data Science Blogs](#data-science-blogs)  
  * [Design Blogs](#design-blogs)  
  * [Data Science Conferences](#data-science-conferences)  
  * [Data Science Presentations](#data-science-presentations)
  * [Relevant Business Processes](#relevent-business-processes)  

1. [Open Source Data Science Resources](#open-source-data-science-resources)
  * [Additional Open Source Content](#other-open-source-data-science-content)  

1. [About Me](#about-me)

Section of the data pipeline & resources:

## Data Science Getting Started
Data Science is a multidisciplinary field covering at the very minimum - statistics, programming, machine learning.  These topics are covered throughout this repo.  I find the best way to learn a topic is to get my hands dirty quickly -- with that in mind I would probably get to work in python and then implement different tools or theory into my toolkit as I understand each element.  If you haven't used python before I would strongly urge you to use the codecademy course to familiarize yourself with the content and how to program.  Good luck and have fun.
 
### Starting  
* [Data Science Pipeline](http://machinelearningmastery.com/wp-content/uploads/2014/05/Overview-of-the-Applied-Machine-Learning-Process.png=1000x100) - Detailed overview of data pipeline from MachineLearningMastery.com
* [Intro to ipython](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks/_edit#entire-books-or-other-large-collections-of-notebooks-on-a-topic) - A curation of Ipython Notebooks great for introductory level to python, programming, comp sci, data science and other topics.    
* [How do I Become a Data Scientist?](http://www.quora.com/How-do-I-become-a-data-scientist) - Some more great starting points from William Chen.  

### Data Science Courses:
* [Coursera](https://www.coursera.org/specialization/jhudatascience/1) - Data Science Specialization at Coursera - many other courses available as well.   
* [Udacity](https://www.udacity.com/courses#!/data-science) - Online MOOCs that are the Data Science related courses 
* [Data Science Bootcamps](http://yet-another-data-blog.blogspot.com/2014/04/data-science-bootcamp-landscape-full.html) - List of all bootcamps currently on the market as of April 5, 2014  
* [Coursera Machine Learning Course](https://www.coursera.org/course/ml) - Coursera pinnacle Machine Learning course.   
* [Edx](https://www.edx.org/course/mitx/mitx-6-00-2x-introduction-computational-2836#.VEANx9TF-tw) - EDX courses related to data science.

## Data Pipeline & Tools 

###Python 
Python is my workhorse language specifically as it has many data science and statistic library, the ability to work in production environments, and work on other problems outside of data science.  There are many other languages that could be useful but are not covered here: Julia, R, Cython, Pig, Scala, Java, etc.

* [Python @ Codecademy](http://www.codecademy.com/en/tracks/python) - If you have never used Python, right this way..  
* [The Python Wiki](https://wiki.python.org/moin/FrontPage) - Good resource with lots of info about Python  
* [Python for Data Science Tutorial - Kaggle](https://www.kaggle.com/wiki/GettingStartedWithPythonForDataScience) - Stepping into Data Science with Kaggle and installing some libraries   
* [Introduction to Data Processing with Python](http://opentechschool.github.io/python-data-intro/) - Just as the name says - some introductory level information and exercises.  
* [Git tutorial](https://try.github.io/levels/1/challenges/1) - Git for Version Control.  Simple tutorial for Git from Github.  

####Stats/Engineering Libraries
A collection of workhorse libraries that are elemental for any python data scientist.  
* [Pandas](http://pandas.pydata.org/) Pandas for EDA on small to medium sized data sets when you don't want to put the infrastructure for SQL or when it isn't necessary.  It has many other great applications other than just better than SQL on small to medium data sets.  
** [Numpy/Pandas/Scipy Cheatsheet](https://s3.amazonaws.com/quandl-static-content/Documents/Quandl+-+Pandas,+SciPy,+NumPy+Cheat+Sheet.pdf) - self explanatory   
* [SciPy](http://www.scipy.org/) - Open-source software for mathematics, science and engineering.  
* [NumPy](http://www.numpy.org/) - Fundamental package for scientific computing with Python.  
* [StatsModels](http://statsmodels.sourceforge.net/) - Module that allows users to explore data, estimate statistical models and perform statistical tests.  
* [PyMC](https://pypi.python.org/pypi/pymc) - Bayesian estimation useful for Markov chain Monte Carlo analysis (among other things)
* [Probalistic Programming and Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - Github Repo all about the namesake.  
* [The only probability Cheatsheet you'll ever need](https://bayesrule.files.wordpress.com/2014/07/probability_cheatsheet_140718.pdf) - Self explanatory - (thanks William Chen @ http://datastories.quora.com/) for pointing me this sweet cheat sheet out - wish I had that back at college.  

####Data Acquisition
Libraries that are very helpful for abstracting away some of the complications of scraping or working with HTTP.   
* [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) - a python library to make web-scraping HTML easier  
** [Beautiful Soup Cheat Sheet](http://youkilljohnny.blogspot.com/2014/03/beautifulsoup-cheat-sheet-parse-html-by.html)  
* [Requests](http://docs.python-requests.org/en/latest/) - HTTP for Humans - python library that makes working with http and api's more effortless  

####Processing & Exploratory Data Analysis
A collection of documents explaining some of the ways to do processing & EDA.  
* [Unix for Processing](http://www.theunixschool.com/p/awk-sed.html) - sed & awk for data processing  
* [Pandas](http://pandas.pydata.org/) - Already mentioned is great for data processing - cleaning, filtering and getting rid of nan's, normalizing, scaling, replacing values, etc  
* [SciKit Learn for Preprocessing](http://scikit-learn.org/stable/modules/preprocessing.html#preprocessing) - Docstring on sklearn's preprocessing methods.  
* [Regular Expressions](http://www.zytrax.com/tech/web/regex.htm) - Regex explained.  

###Databases/Frameworks
A collection of databases & frameworks that are helpful for data management and are the industry standard.  
* [SQL](http://www.postgresql.org/) -- SQL Database - I linked to Postgres since that is the version I use. 
* [Psycopg](http://initd.org/psycopg/) -- Pyton <> Postgres.  Able to adapt PostgreSQL for the python environment   
** [SQL Cheet Sheet](http://www.sql-tutorial.net/sql-cheat-sheet.pdf)   
** [SQLZoo](http://sqlzoo.net/wiki/Main_Page) - Develop your skills  
** [SQLSchool](http://sqlschool.modeanalytics.com/) - Develop your skills  
[MongoDB](http://www.mongodb.org/) - NoSQL database  
* [PyMongo](http://api.mongodb.org/python/current/tutorial.html) - Python Mongo Driver.  
** [MongoDB - cheatsheet](https://blog.codecentric.de/files/2012/12/MongoDB-CheatSheet-v1_0.pdf) - Cheat sheet for MongoDB    
* [Apache Hive](https://hive.apache.org/) - Uses Hive Query Language (HQL) - similar to SQL for data at scale.     
** [Hive Cheatsheet](http://hortonworks.com/wp-content/uploads/downloads/2013/08/Hortonworks.CheatSheet.SQLtoHive.pdf) - Self Explanatory.  
* [ElasticSearch](http://www.elasticsearch.org/) - For scalable, fast text search/analysis  
* [Neo4j](http://www.neo4j.org/) - Leading graph database    
* [Redis](http://redis.io/) - Key-value open source data structure server  
* [Redshift](http://aws.amazon.com/redshift/) - AWS petabyte-scale data warehouse solution.  
* [Hadoop - the definitive guide](http://ce.sysu.edu.cn/hope/UploadFiles/Education/2011/10/201110221516245419.pdf) - Hadoop ecosystem.  
* [Spark](https://spark.apache.org/) - Lightening fast cluster computing.

###Machine Learning
There is a lot of information available online about the theory, mathematical intuition, tuning for this discipline.  I am not trying to cover it in that depth, at least not at this current time.  These are some high level knowledge posts and toolkits.    
* [SciKit-Learn](http://scikit-learn.org/stable/) - Simple and efficient machine learning tools for data mining and data analysis    
* [NLTK](http://www.nltk.org/) - Natural Language Toolkit to work with human languages data.  
* [Tour of Machine Learning Algorithms](http://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/) - Blog post about some of the high level ML methods
* [VIDEO - How to get started w/mL](https://www.youtube.com/watch?v=uBorfxosVYs) - Melanie Warrick @ PyCon 2014  
* [Some ML methods classified](http://nyghtowlblog.files.wordpress.com/2014/04/ml_algorithms.png?w=535&h=311) - Classification for some sample ML algorithms.  
* [SciKit-image](http://scikit-image.org/) - Algorithms for image processing.  
* [Deeplearning4j](http://deeplearning4j.org/) - Deep Learning in Java.  
* [Machine Learning CheatSheet](https://github.com/soulmachine/machine-learning-cheat-sheet) - I would actually say this is more than just a cheat sheet given that there are > 100 pages of notes. 

####Model Selection
Resources about how to decide on your model.  
* [SciKit Learn Flow Chart for Model Selection](http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html) - A helpful for a starting point selecting SKlearn algorithms.

####Model Evaluation
Resources to help with understanding model evaluation.  
* [Evaluating ML Algorithms](http://machinelearningmastery.com/how-to-evaluate-machine-learning-algorithms/) - Blog Post from MachineLearningMastery about how to evaluate your performance.
* [Cross-Validation](http://robjhyndman.com/hyndsight/crossvalidation/) - Critical concept to evaluate the performance of your models.  
** [K-fold & Grid Search in Scikitlearn](http://randomforests.wordpress.com/2014/02/02/basics-of-k-fold-cross-validation-and-gridsearchcv-in-scikit-learn/) - Demo on how to implement kfold cross validation and grid-search using scikit-learn.  
** [Scikit-learn Cross Validation doc](http://scikit-learn.org/stable/modules/cross_validation.html) - Self explanatory title.  

####Feature Engineering
A critical element of Data Science to improve your performance but minimally talked about.   
* [Ipython Notebook for Feature engineering](http://nbviewer.ipython.org/urls/raw2.github.com/yhat/DataGotham2013/master/notebooks/7%20-%20Feature%20Engineering.ipynb?create=1) - Some discussion about Feature Engineering
* [CS Princeton Course](http://www.cs.princeton.edu/courses/archive/spring10/cos424/slides/18-feat.pdf) - Course content on Feature Engineering.  
* [Blog Post about Feature Engineering / Data Exploration](http://deblivingdata.net/machine-learning-tricks/) - Blog post about topic.   

### Additional Tools or Processes
Resources on other topics that are very helpful for data scientists and product.  
* [A/B Testing](http://conversionxl.com/how-to-build-a-strong-ab-testing-plan-that-gets-results/#.) - Blog about A/B testing
* [A/B Testing](http://unbounce.com/a-b-testing/5-ways-youre-screwing-up-your-a-b-testing/) - And how you are screwing it up.  
* [Bloom Filters](http://nbviewer.ipython.org/github/ctb/2013-pycon-awesome-big-data-algorithms/blob/master/04-bloom-filters.ipynb)  - Python notebook about bloom filters
* [Bloom filters](http://billmill.org/bloomfilter-tutorial/)  - Bloom Filters   
* [Reservoir Sampling](http://blog.cloudera.com/blog/2013/04/hadoop-stratified-randosampling-algorithm/) - A primer on Reservoir Sampling  
* [Reservoir Sampling Again](http://www.geeksforgeeks.org/reservoir-sampling/)  
* [Monte Carlo for the Monty Hall Problem](http://slantedwindows.com/monty-hall-meet-mr-monte-carlo/) - Hyon puts on a good explanation to MC for the Monty Hall Problem.  
* [Markov Chain Monte Carlo](http://nbviewer.ipython.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter3_MCMC/IntroMCMC.ipynb) - Opening the black box of MCMC.
* [Multithreading and Queues](http://pymotw.com/2/Queue/) - How to build multithreading and queues.   
* [Basics of Multithreading and queses](http://www.troyfawkes.com/learn-python-multithreading-queues-basics/)  - More about multithreading.
* [Building a Recommender System](http://www.quora.com/How-can-I-start-building-a-recommendation-engine) - Quora answer to this question.  Helpful starting point.
* [Hash Tables]() - [PLACEHOLDER]

### Data Visualization
Collection of the best libraries that I know for easy and powerful data visualizations.
* [ggplot](http://ggplot.yhathq.com/) - ggplot for python ported by the team at yhat  
* [matplotlib](http://matplotlib.org/) - awesome plotting library for python.  
* [d3](http://d3js.org/) - De facto gold standard for polished visualization - in js, steep learning curve but beautiful outcomes.
* [bokeh](http://bokeh.pydata.org/) - interactive visualization library.  
* [d3py](https://github.com/mikedewar/d3py) - another library for data viz 
* [vincent](http://vincent.readthedocs.org/en/latest/)  - help with python for d3
* [seaborn](http://web.stanford.edu/~mwaskom/software/seaborn/) - Clean statistical data visualization library.  

Design Theory -- [PLACE HOLDER]
The importance of design theory in data visualization and presentations could not be understated though many people pay no heed (probably through a lack of understanding than anything else).  I will try and find some good resources to fill this.

### Ipython Notebook Tutorials
Collection of ipython notebooks that are helpful as examples to either using tools or to explain certain topics.
* [Pandas Tutorial](http://nbviewer.ipython.org/github/twiecki/financial-analysis-python-tutorial/blob/master/1.%20Pandas%20Basics.ipynb) - Basic intro to Pandas in notebook form.  
* [Scipy Tutorial](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-3-Scipy.ipynb) - Basic Scipy Tutorial 
* [Numpy Tutorial](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-2-Numpy.ipynb) - Basic Numpy Tutorial 
* [Multiple Regressions using Statsmodels](http://nbviewer.ipython.org/urls/s3.amazonaws.com/datarobotblog/notebooks/multiple_regression_in_python.ipynb) - Using statsmodels for regression  
* [Intro to PyMC](http://nbviewer.ipython.org/github/fonnesbeck/Bios366/blob/master/notebooks/Section4_3-Introduction-to-PyMC.ipynb) - Intro to PyMC 
* [More on PyMC](http://nbviewer.ipython.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter2_MorePyMC/MorePyMC.ipynb) - More PyMC  
* [Kaggle Titanic Comp Tutorial](http://nbviewer.ipython.org/github/agconti/kaggle-titanic/blob/master/Titanic.ipynb) - Kaggle Titanic Tutorial using RandomForests
* [Psycopg2 tutorial in Python](https://wiki.postgresql.org/wiki/Psycopg2_Tutorial) - How to use Psycopg2     
* [SQL in iPython](http://nbviewer.ipython.org/gist/catherinedevlin/6588378) - SQL in Python   
* [Mongo in Python](http://api.mongodb.org/python/current/tutorial.html) - Mongo in Python   
* [Beautiful Soup Tutorial](http://nbviewer.ipython.org/github/kcranston/2013-08-ku/blob/master/beautifulsoup/notebooks/00-BeautifulSoup.ipynb) - Beautiful Soup! 
* [Sci-Kit Learn Basics](http://nbviewer.ipython.org/urls/raw2.github.com/yhat/DataGotham2013/master/notebooks/4%20-%20scikit-learn%20basics.ipynb?create=1)  - Machine Learning Basics with scikit-learn.
* [MatPlotLib](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb) - Some of the possibilities of data-viz with MatPlotLib.
* [Choosing the right priors - Bayesian](http://nbviewer.ipython.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter6_Priorities/Priors.ipynb) - Bayesian statistics and prior selection.  
* [Some Basic Data Analysis in Python](http://nbviewer.ipython.org/github/jvns/talks/blob/master/pyconca2013/pistes-cyclables.ipynb) - Basic data analysis with python.  
* [Crash Course in Python for Scientists](http://nbviewer.ipython.org/gist/rpmuller/5920182) - Ipython Notebook for Scientists!   
* [Regular Expressions](http://nbviewer.ipython.org/gist/rjweiss/7577022) - Regex to match patterns in strings - very powerful.  
* [MapReduce](http://nbviewer.ipython.org/github/cs109/content/blob/master/labs/lab8/lab8_mapreduce.ipynb) - Classes, inheritance and map-reduce exercises.  
* [Recursion](http://nbviewer.ipython.org/github/gumption/Motivating_and_Visualizing_Recursion_in_Python/blob/master/Motivating_and_Visualizing_Recursion_in_Python.ipynb)  Notebook visualization recursion "The single most powerful idea in algorithms"  
* [Recursion](http://anandology.com/python-practice-book/functional-programming.html) More about Recursion and Functional Programming  

### Data Sources
Collection of sites to access data if you want to build out a project or just use some of the tools for EDA.  
* [Data.Gov](https://www.data.gov/) - The US government portal to open data.  
* [California Water Resources](http://www.water.ca.gov/data_home.cfm) - California's water resource data.
* [Data for Cool DS projects](http://101.datascience.community/2014/10/17/data-sources-for-cool-data-science-projects-part-1-guest-post/)
* [Academic Torrents](http://academictorrents.com/) - Sharing Data is hard, torrents make it easier for academics.  
* [Data Basin](http://databasin.org/) - Science based mapping and analytics platform.
* [Open Energy Data Initiative](http://en.openei.org/wiki/Main_Page) - Over 800 data sets covering energy issues.   
* [UCI Machine Learning Datasets](https://archive.ics.uci.edu/ml/datasets.html) - Data for machine learning - lots of labeled data and description of the problem types.   

## Product Resources  

###Product Metrics  
Understanding product, user behavior, and product metrics is helpful for data scientists in industry. Being able to help your product manager and team execute on strategies by understanding the problem, metrics and what they understand facilitates a more fruitful relationship.   
* [Actionable Metrics](http://practicetrumpstheory.com/3-rules-to-actionable-metrics/) - Funnel reports, cohort analysis, actionable metrics.  
* [Analytics for Product Managers](http://www.mindtheproduct.com/2013/02/everything-a-product-manager-needs-to-know-about-analytics/) - Everything a PM needs to know about analytics - or the minimum amount your PM should know about analytics as a Data Scientist.  
* [Startups, you are doing data science wrong!](https://gigaom.com/2013/09/28/notice-to-startups-you-are-doing-data-science-wrong/) - High level explanation about how to use data science in a start-up company.  
* [Product Psychology](http://www.productpsychology.com/category/user-behavior/)  - Understanding user behavior.  
* [Salesforce](http://www.salesforce.com) - Salesforce for Customer Relationship Management (CRM) software.  
* [Infer](http://www.infer.com) - Predictive lead scoring for sales & marketing.  

## Career Resources

### Data Science Career Path
* [Data Science @ Google](http://www.quora.com/What-is-the-Quant-Data-Science-Career-ladder-at-Google) - Quora answer about Data Science career trajectory @ google.  

### Types of Data Scientists
Not all Data Scientists are the same and it's critical for organizations to understand what it is they need, and how best to fill those roles or complement the skills of their team.  Finding the organizational structure that enables the data scientists/data engineerings within the organization and generates better results is also crucial.  It should be given thorough consideration.      
* [Kind's of Data Scientist](http://radar.oreilly.com/2013/06/theres-more-than-one-kind-of-data-scientist.html) - O'Reilly's classification of 4 different data scientists.
* [Data Science For Startups](http://tomtunguz.com/data-science-types/) - Which of the Five Types of DS does your startup need?  Different classification from O'Reilly.
* [My own blog post about DS Types][PLACEHOLDER]
* [Building Data Science Teams](http://radar.oreilly.com/2011/09/building-data-science-teams.html) - posted from 2011 about how to build data science teams.
* [Data Science Team Building - The Power of Collaborative Analytics](http://www.experfy.com/blog/data-science-team-building-power-collaborative-analytics/) - Post post about different team org structures,  difference between DS & BI.
 
### Data Science Applications/Use Cases
Data Science has so many different applications and use cases within industry - many are continuously discovered.  These resources provide some potential ideas.
* [Kaggle Data Science Use Cases](https://www.kaggle.com/wiki/DataScienceUseCases) - Helpful to generate ideas for new uses in different industries
* [Data Science for each Industry](http://www.mastersindatascience.org/industry/) - description of uses for different industries.  
* [Big Data Analytics News - use Cases](http://bigdataanalyticsnews.com/big-data-use-cases/) - for Big Data but that's almost synonymous with Data Science.

### New Data Tools
Aim to keep track of developing trends and new tech that is helpful for the practicing Data Scientist.  New might be a misnomer.
* [BigML](https://bigml.com/) - machine learning for the everyday user, also useful for EDA.   
* [GraphLab](http://graphlab.com/) - graph-based, high performance, distributed computation framework.  They just implemented deep learning onto their platform.
* [ModeAnalytics](https://modeanalytics.com/) - platform to share analysis/data science.    
* [Apache Mahout](https://mahout.apache.org/) - Scalable machine learning library.  Not in python.  
* [Apache Hadoop](http://hadoop.apache.org/) - Open-source software for reliable, scalable, distributed computing.   

### Data Science Websites/Books
More resources for community based information or hard copy books.  
* [Data Science Handbook](https://medium.com/@pericarus/introducing-the-data-science-handbook-b2bfa216bf4b) - Not yet released but should be interesting providing stories from academia and industry about data science - go read the post for a better description!
* [CrossValidated](http://stats.stackexchange.com/) - a question and answer site for people interested in statistics, machine learning, data analysis, data mining, and data visualization.    
* [StackOverflow](stackoverflow.com) - language-independent collaboratively edited question and answer site for programmers.   
* [Kaggle](http://www.kaggle.com) - Model building competition and great resources for training and data.  
* [O'Reilly Media](http://shop.oreilly.com/category/get/data-science-kit.do) -They have a lot of content rich books available for Data Science and using the tools for excellent data science.    
* [Quora](http://www.quora.com/) - Question and Answer site - lots of Data Science Content.  

### Data Science Meetups in the Bay Area
A great way to meet other Data Scientist and keep up to date with best practices.  
* [SF Data Science](http://www.meetup.com/SF-Data-Science/)  
* [Data Science for Sustainability](http://www.meetup.com/Data-Science-for-Sustainability/)  
* [Python Meetup Group](http://www.meetup.com/sfpython/)  
* [USF Seminar Series in Analytics](http://www.meetup.com/USF-Seminar-Series-in-Analytics/http://www.meetup.com/USF-Seminar-Series-in-Analytics/http://www.meetup.com/USF-Seminar-Series-in-Analytics/http://www.meetup.com/USF-Seminar-Series-in-Analytics/)  
* [DataKindSF](http://www.meetup.com/DataKind-SF-Bay-Area/)  
* [SF Bayarea Machine Learning](http://www.meetup.com/SF-Bayarea-Machine-Learning/)  
* [AirBnB Tech Talks](http://nerds.airbnb.com/tech-talks/)     

### Data Science Blogs
The name say's it all.  
* [Data Stories @ Quroa](http://datastories.quora.com/) - William Chen's (DS@Quora) blog about data science.  
* [FastML](http://fastml.com/)  
* [FiveThirtyEight Blog](http://fivethirtyeight.com/) - Nate Silver's blog
* [](http://www.datasciencehandbook.me/) - Data Science Handbook Project (not quite a blog but it fits here)  
* [Simply Statistics Blog](http://simplystatistics.org/)  
* [All The Things Tech](http://nyghtowl.io/)  
* [Musings in Data Science](http://deblivingdata.net/)  
* [Zipfian Data Science Blog](http://www.zipfianacademy.com/blog/)  
* [Machine Learning Mastery](http://machinelearningmastery.com/) 
* [DataTau](http://datatau.com) - Hackernews for Data Science
* [HackerNews](https://news.ycombinator.com/) 
* [Quora](http://quora.com) - Q&A site with lots of information about Data Science.

### Design Blogs
* [ThreeStoryBlog](http://blog.threestory.com/)

### Data Science Conferences
* [Strata](http://strataconf.com/) - Conference and a TON of old videos from previous conferences - great resource.  
* [GraphLab](http://graphlab.com/events/conference14.html) - Another solid conference.  

### Data Science Presentations
* [Strata Collection of Presentations](http://strataconf.com/strata2014/public/schedule/proceedings) - Most of their conference presentations available online.

### Relevant Business Processes
* [Lean Startup](http://theleanstartup.com/principles) - A method to develop product and businesses.
* [Agile Development](http://en.wikipedia.org/wiki/Agile_software_development) - group of software development methods to optimize for self-organizational and cross-functional teams.
* [Scrum](http://en.wikipedia.org/wiki/Scrum_(software_development)) - an interative and incremental agile software development framework for managing product development.  

##Open Source Data Science Resources
While the name might sound redundant this section represents other sites or repos that have aggregated information covering similar topics.  Tons of great content on these sites - definitely go check them out.  

### Other Open Source Data Science Content
There are some really great resources linked within this section covering all of Data Science, the entire data pipeline, machine-learning, statistics, python, etc.  Go check them out.  
* [Open Data Science Masters](http://datasciencemasters.org/) - Open Source online blog/github with lots of resources available for data science.  
* [A Practical Intro to Data Science](http://www.zipfianacademy.com/blog/post/46864003608/a-practical-intro-to-data-science) - List of excellent resources available  
* [LearnDataScience](https://github.com/nborwankar/LearnDataScience) - IpythonNotebooks for Linear Regression, Logistic Regression, Random Forests, K-Means Clustering  
* [FreeDataScienceBooks](https://github.com/chaconnewu/free-data-science-books/blob/master/free-data-science-books.md) - Free open sourced online data science books.  
* [Gallery of Ipython Notebooks](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks) - Introduction to Python, Data Science, Economics, Comp Sci, Linguistics, and much more.  
* [Data Science 45 Min Intros](https://github.com/DrSkippy/Data-Science-45min-Intros) - The team @ Gnip have a collection of repos to introduce data science topics in roughly 45 minutes per topic.  

### Other Content
* [Markable](http://markable.in/editor/) - Let's me visualize my Markdown 
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)  - Self explanatory.  
* [LightPaper](http://www.ashokgelal.com/lightpaper-for-mac/) - Markdown editor that I use  
* [iterm2](http://iterm2.com/) - Terminal application for Mac  
* [Oh My Zsh](http://ohmyz.sh/) - Framework for managing your ZSH config.  Awesome.  
* [Sublime Text Editor](http://www.sublimetext.com/) - For all your scripting needs.  

## ABOUT ME

I acquired my skills through programming in an on-the-job environment and then taking three months off to learn and put into practice my data science skills @ Zipfian Academy.  For me taking that time off to learn, run the daily/weekly sprints, and be in a collective learning environment at Zipfian was irreplaceable.  Even if Zipfian resources were open source, without taking the time off work and having the drive to learn all the necessary material would be next to impossible.  I am always interested to hear what other data scientists are doing and using for tools. I am interested in a wide range of different open source &/or private projects - feel free to reach out on Twitter [@sf_oak](http://bit.ly/1FefepA) or [LinkedIn](http://linkd.in/1vp57dk).