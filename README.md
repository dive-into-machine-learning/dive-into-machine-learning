# Dive into Machine Learning [![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

**Hi there! This guide is for you:**

* **You're new to [Machine Learning.](https://en.wikipedia.org/wiki/Machine_learning)**
* **You know Python.** (At least the basics! If you want to learn more Python, [try this](https://github.com/hangtwenty/python-is-for-lovers))

I learned Python by hacking first, and getting serious *later.* I wanted to do this with Machine Learning. If this is your style, join me in getting a bit ahead of yourself.

_Note:_ There are several fields within "Data" and Machine Learning is just one. It's good to know the context: [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)

# Get your feet wet!

I suggest you get your feet wet ASAP. You'll boost your confidence.

## Tools you'll need

- [Python](https://www.python.org/). Python 3 is the best option.
- [IPython and the Jupyter Notebook](http://ipython.org/). (FKA IPython and IPython Notebook.)
- Some scientific computing packages:
	- numpy
	- pandas
	- scikit-learn
	- matplotlib

You can install Python 3 and all of these packages in a few clicks with the [Anaconda Python distribution](https://www.continuum.io/downloads). Anaconda is popular in Data Science and Machine Learning communities.

If you're using Python 2.7, don't worry. You don't have to migrate to Python 3 just for this guide. Also, if you're using pip/virtualenv instead of Anaconda, that's alright too! And re: installing packages, this is a helpful doc: [conda vs. pip vs. virtualenv](https://conda.io/docs/commands.html#conda-vs-pip-vs-virtualenv-commands)

## Let's go!

**[Learn how to use IPython Notebook](http://opentechschool.github.io/python-data-intro/core/notebook.html) (5-10 minutes).** (You can [learn by screencast](https://www.youtube.com/watch?v=qb7FT68tcA8) instead.)

Now, follow along with this brief exercise (10 minutes): **[An introduction to machine learning with scikit-learn](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)**. Do it in `ipython` or IPython Notebook. It'll really boost your confidence.

[![I'll wait.](https://user-images.githubusercontent.com/2420688/29441281-00eff0c4-837f-11e7-9666-d653a1cd2372.jpeg)](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)

## What just happened?

You just classified some hand-written digits using [scikit-learn]. Neat huh?

[scikit-learn] is the go-to library for machine learning in Python. [Some recognizable logos use it, including Spotify and Evernote.](http://scikit-learn.org/stable/testimonials/testimonials.html) Machine learning is hard. You'll be glad your tools are easy to work with.

[scikit-learn]: http://scikit-learn.org/stable/index.html

I encourage you to look at the [scikit-learn] homepage  and spend about 5 minutes looking over the names of the strategies (Classification, Regression, etc.), and their applications. Don't click through yet! Just get a glimpse of the vocabulary.

# Dive in

## A Visual Introduction to Machine Learning

Let's learn a bit more about Machine Learning, and a couple of common ideas and concerns. Read ["A Visual Introduction to Machine Learning, Part 1"](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) by [Stephanie Yee](https://twitter.com/stephaniejyee) and [Tony Chu](https://twitter.com/tonyhschu/).

[![A Visual Introduction to Machine Learning, Part 1](https://user-images.githubusercontent.com/2420688/29441234-a2028c98-837e-11e7-88f2-1ca5a94684f6.gif)](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)

It won't take long. It's a beautiful introduction ... Try not to drool too much!

## A Few Useful Things to Know about Machine Learning

OK. Let's dive deeper.

Read **["A Few Useful Things to Know about Machine Learning"](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)** by Prof. Pedro Domingos. It's densely packed with valuable information, but not opaque. The author understands that there's a lot of "black art" and folk wisdom, and they invite you in.

Take your time with this one. Take notes. Don't worry if you don't understand it all yet.

The whole paper is packed with value, but I want to call out two points:

- **Data alone is not enough.** This is where science meets art in machine-learning. Quoting Domingos: "... the need for knowledge in learning should not be surprising. Machine learning is not magic; it can’t get something from nothing. What it does is get more from less. Programming, like all engineering, is a lot of work: we have to build everything from scratch. Learning is more like farming, which lets nature do most of the work. Farmers combine seeds with nutrients to grow crops. Learners combine knowledge with data to grow programs."
- **More data beats a cleverer algorithm.** Listen up, programmers. We like cool tools. Resist the temptation to reinvent the wheel, or to over-engineer solutions. Your starting point is to [Do the Simplest Thing that Could _Possibly_ Work](http://www.artima.com/intv/simplest3.html). Quoting Domingos: "Suppose you’ve constructed the best set of features you can, but the classifiers you’re getting are still not accurate enough. What can you do now? There are two main choices: design a better learning algorithm, or gather more data. [...] As a rule of thumb, a dumb algorithm with lots and lots of data beats a clever one with modest amounts of it. (After all, machine learning is all about letting data do the heavy lifting.)"

So  **knowledge** and **data** are critical. Focus your efforts on those, before fussing about algorithms. In practice, this means that unless you _have_ to increase complexity, you should continue to [Do Simple Things]; don't rush to neural networks just because they're cool. To improve your model, get more data  and use your knowledge of the problem to manipulate the data. You should spend most of your time on these steps. Only optimize your choice of algorithms after you've got enough data, and you've processed it well.

![What has the most impact in Machine Learning](https://user-images.githubusercontent.com/2420688/29441212-798d2bba-837e-11e7-90b1-21daaf8d7b73.png)

(Chart inspired by a slide from [Alex Pinto's talk, "Secure Because Math: A Deep-Dive on ML-Based Monitoring"](https://www.youtube.com/watch?v=TYVCVzEJhhQ).)

[Do Simple Things]: http://wiki.c2.com/?DoSimpleThings

## Just about time for a break...

Before you take a break, grab some podcasts. First, download [this podcast episode where _Knowledge Project_ interviews Prof. Domingos](https://www.farnamstreetblog.com/2016/09/pedro-domingos-artificial-intelligence/), who wrote [the paper we read earlier](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf).

Next, subscribe to _**[Talking Machines](http://www.thetalkingmachines.com/)**_, a podcast about machine learning. It's a great, low-effort way to learn more. Listen casually to these episodes, over time — no need to rush.

I suggest this listening order:

* Download the ["Starting Simple"](http://www.thetalkingmachines.com/blog/2015/4/23/starting-simple-and-machine-learning-in-meds) episode, and listen to that first. It supports what we read from Domingos. Ryan Adams talks about starting simple, as discussed above. Adams also stresses the importance of feature engineering. Feature engineering is an exercise of the "knowledge" Domingos writes about.
* Then, over time, you can listen to the entire podcast series (start from the beginning).

OK. Take a break, come back fresh.

----

## Play to learn

Next, pick **one or two** of these IPython Notebooks and play along.

- [Face Recognition on a subset of the Labeled Faces in the Wild](http://nbviewer.jupyter.org/github/ogrisel/notebooks/blob/master/Labeled%20Faces%20in%20the%20Wild%20recognition.ipynb)
- [Machine Learning from Disaster](http://agconti.github.io/kaggle-titanic/): Using Titanic data, "Demonstrates basic data munging, analysis, and visualization techniques. Shows examples of supervised machine learning techniques."
- [Election Forecasting](https://github.com/jseabold/538model): A replication of the model Nate Silver used to make [predictions about the 2012 US Presidential Election for the New York Times](https://fivethirtyeight.blogs.nytimes.com/fivethirtyeights-2012-forecast/))
- [An example Machine Learning notebook](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb): "let's pretend we're working for a startup that just got funded to create a smartphone app that automatically identifies species of flowers from pictures taken on the smartphone.  We've been tasked by our head of data science to create a demo machine learning model that takes four measurements from the flowers (sepal length, sepal width, petal length, and petal width) and identifies the species based on those measurements alone."
- ClickSecurity's "data hacking" series (thanks [hummus](https://github.com/hummus)!)
	- [Detect Algorithmically Generated Domains](http://nbviewer.jupyter.org/github/ClickSecurity/data_hacking/blob/master/dga_detection/DGA_Domain_Detection.ipynb)
	- [Detect SQL Injection](http://nbviewer.jupyter.org/github/ClickSecurity/data_hacking/blob/master/sql_injection/sql_injection.ipynb)
	- [Java Class File Analysis](http://nbviewer.jupyter.org/github/ClickSecurity/data_hacking/blob/master/java_classification/java_classification.ipynb): is this Java code malicious or benign?
- If you want more of a data science bent, pick a notebook from [this excellent list of Data Science ipython notebooks](https://github.com/donnemartin/data-science-ipython-notebooks). "Continually updated Data Science Python Notebooks: Spark, Hadoop MapReduce, HDFS, AWS, Kaggle, scikit-learn, matplotlib, pandas, NumPy, SciPy, and various command lines."
- Or more generic tutorials/overviews ...
	- [Tutorial introduction to machine learning with sklearn](http://amueller.github.io/sklearn_tutorial/)
	- [An Introduction to Supervised Learning via Scikit Learn](http://bugra.github.io/work/notes/2014-11-22/an-introduction-to-supervised-learning-scikit-learn/)
	- [An Introduction to Unsupervised Learning via Scikit Learn](http://bugra.github.io/work/notes/2014-11-16/an-introduction-to-unsupervised-learning-scikit-learn/)

There are more places to find great IPython Notebooks:

* [A Gallery of Interesting IPython notebooks (wiki page on GitHub): Statistics, Machine Learning and Data Science](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks#statistics-machine-learning-and-data-science)
* [Fabian Pedregosa's larger, automatic gallery](http://nb.bianp.net/sort/views/)

----

# Immerse yourself

Now you should be hooked, and hungry to learn more. Pick one of the courses below and start on your way.

## [Recommended course: Prof. Andrew Ng's _Machine Learning_ on Coursera](https://www.coursera.org/learn/machine-learning)

**[Prof. Andrew Ng's](http://www.andrewng.org/about/) [_Machine Learning_](https://www.coursera.org/learn/machine-learning) is a popular and esteemed free online course. I've seen it [recommended](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Cory-Hicks-1) [often.](https://www.coursetalk.com/providers/coursera/courses/machine-learning?page=1&sort=-content_rating#reviews) [And](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Xavier-Amatriain) [emphatically.](https://www.forbes.com/sites/anthonykosner/2013/12/29/why-is-machine-learning-cs-229-the-most-popular-course-at-stanford/)**

It's helpful if you decide on a pet project to play around with, as you go, so you have a way to apply your knowledge. You could use one of these [Awesome Public Datasets](https://github.com/caesar0301/awesome-public-datasets). And remember, IPython Notebook is your friend.

Also, you should grab an in-depth textbook to use as a reference. The two best options are [_Understanding Machine Learning_ ](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/copy.html) and _[Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)_. You'll see these recommended as reference textbooks. [You only need to use one of the two options as your main reference; here's some context/comparison to help you pick which one is right for you.](https://github.com/hangtwenty/dive-into-machine-learning/issues/29) You can download each book free as PDFs at those links - so grab them!

### Tips for studying

* Busy schedule? Read [Ray Li's review of Prof. Andrew Ng's course](https://rayli.net/blog/data/coursera-machine-learning-review/) for some helpful tips.
* Review some of the ["Learning How to Learn"](https://www.coursera.org/learn/learning-how-to-learn/) videos. This is just about how to study in general. In the course, they [advocate the learn-by-doing approach](https://www.coursera.org/learn/learning-how-to-learn/lecture/8IUbH/interview-with-dr-terrence-sejnowski), as we're doing here. You'll get various other tips that are easy to apply, but go a long way to make your time investment more effective.

## Other courses

Here are some other free online courses I've seen recommended. (Machine Learning, Data Science, and related topics.)

* [Prof. Pedro Domingos's introductory video series](https://homes.cs.washington.edu/~pedrod/). Domingos wrote the paper ["A Few Useful Things to Know About Machine Learning"](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf), recommended earlier in this guide.
* Kevin Markham's video series, [Intro to Machine Learning with scikit-learn](http://blog.kaggle.com/2015/04/08/new-video-series-introduction-to-machine-learning-with-scikit-learn/), starts with what we've already covered, then continues on at a comfortable place. After the videos you could do Markham's [General Assembly's Data Science course.](https://github.com/justmarkham/DAT8) Interactive. Markham's course is also offered in-person in Washington, DC.
* [UC Berkeley's Data 8: The Foundations of Data Science](http://data8.org/) course and the textbook [Computational and Inferential Thinking](https://www.inferentialthinking.com/) teaches critical concepts in Data Science.
    * The textbook also provides an academic definition of Data Science: **"Data Science is about drawing useful conclusions from large and diverse data sets through exploration, prediction, and inference".**
    * [Prof. Michael I. Jordan](https://people.eecs.berkeley.edu/~jordan/) (associated with Spark) talks about the design of the course in this [video](https://youtu.be/ggq7HiDO0OU?t=1227)
* Data science courses as IPython Notebooks:
	* [Practical Data Science](http://radimrehurek.com/data_science_python/)
	* [Learn Data Science (an entire self-directed course!)](http://learnds.com/)
	* Supplementary material: [donnemartin/data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks). "Continually updated Data Science Python Notebooks: Spark, Hadoop MapReduce, HDFS, AWS, Kaggle, scikit-learn, matplotlib, pandas, NumPy, SciPy, and various command lines."
* Prof. Mark A. Girolami's [Machine Learning Module (GitHub Mirror).](https://github.com/josephmisiti/machine-learning-module) Good for people with a strong mathematics background.
* Surveys of Data Science courseware (a bit more Choose Your Own Adventure)
	* Check out [Jack Golding's survey of Data Science courseware](https://www.quora.com/Is-it-worth-it-to-pay-9-*-49-for-a-data-science-specialization-on-Coursera/answer/Jack-Golding). Includes Coursera's [Data Science Specialization](https://www.coursera.org/specializations/jhu-data-science) with 9 courses in it. The Specialization certificate isn't free, but you can take the courses 1-by-1 for free if you don't care about the certificate. The survey also covers [Harvard CS109](http://cs109.github.io/2014/) which I've seen recommended elsewhere.
	* [Another epic Quora thread: How can I become a data scientist?](https://www.quora.com/How-can-I-become-a-data-scientist?redirected_qid=59455)
	* Data Science Weekly's [Big List of Data Science Resources](https://www.datascienceweekly.org/data-science-resources/the-big-list-of-data-science-resources) has a [List of Data Science MOOCs](https://www.datascienceweekly.org/data-science-resources/data-science-moocs)
* [Advanced Statistical Computing (Vanderbilt BIOS8366)](http://stronginference.com/Bios8366/lectures.html). Interactive (lots of IPython Notebook material)
* [Data Science (Harvard CS109)](http://cs109.github.io/2014/)


## Getting Help: Questions, Answers, Chats

Start with the support forums and chats related to the course(s) you're taking.

For now, the best StackExchange site is [stats.stackexchange.com – _machine-learning_.](https://stats.stackexchange.com/questions/tagged/machine-learning?sort=frequent&pageSize=15) (There's also [datascience.stackexchange.com](https://datascience.stackexchange.com/), but it's still in Beta.) And there's [/r/machinelearning](https://www.reddit.com/r/machinelearning). There are also many relevant discussions on Quora, for example: [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)

You should also [join the Gitter channel for scikit-learn!]( https://gitter.im/scikit-learn/scikit-learn)

For help and community in meatspace, seek out meetups. Data Science Weekly's [Big List of Data Science Resources](http://www.datascienceweekly.org/data-science-resources/the-big-list-of-data-science-resources) may help you.

## Supplement: Learning Pandas well

You'll want to get more familiar with Pandas.

* **Essential**: [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
* **Essential**: [Things in Pandas I Wish I'd Had Known Earlier](http://nbviewer.jupyter.org/github/rasbt/python_reference/blob/master/tutorials/things_in_pandas.ipynb) (IPython Notebook)
* Another helpful tutorial: [Real World Data Cleanup with Python and Pandas](https://trendct.org/2016/08/05/real-world-data-cleanup-with-python-and-pandas/)
* [Video series from Data School, about Pandas](https://www.youtube.com/playlist?list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y). "Reference guide to 30 common pandas tasks (plus 6 hours of supporting video)."
* [Useful Pandas Snippets](http://www.swegler.com/becky/blog/2014/08/06/useful-pandas-snippets/)
* Here are some docs I found especially helpful as I continued learning:
	* [Cookbook](http://pandas.pydata.org/pandas-docs/stable/cookbook.html)
	* [Data Structures](http://pandas.pydata.org/pandas-docs/stable/dsintro.html), esp. [DataFrame](http://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe) section
	* [Reshaping by pivoting DataFrames](http://pandas.pydata.org/pandas-docs/version/0.15.0/reshaping.html)
	* [Computational tools](http://pandas.pydata.org/pandas-docs/stable/computation.html) and [StackExchange thread: "What is covariance in plain language?"](https://stats.stackexchange.com/questions/29713/what-is-covariance-in-plain-language)
	* [Group By (split, apply, and combine DataFrames)](http://pandas.pydata.org/pandas-docs/stable/groupby.html)
	* [Visualizing your DataFrames](http://pandas.pydata.org/pandas-docs/version/0.15.0/visualization.html)
* You may also want to check out [the `odo` library](http://odo.readthedocs.io/). "Odo migrates between many formats. These include in-memory structures like `list`, `pd.DataFrame` [pandas `DataFrame`] and `np.ndarray` [NumPy `ndarray`] and also data outside of Python like CSV/JSON/HDF5 files, SQL databases, data on remote machines, and the Hadoop File System." Definitely a good thing to have in your toolbelt as you play with different data sources.

## Supplement: Cheat Sheets

Some good cheat sheets I've come across. (Please [submit a Pull Request](https://github.com/hangtwenty/dive-into-machine-learning/pulls) to add other useful cheat sheets.)

- [scikit-learn algorithm cheat sheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
- [Metacademy: a package manager for [machine learning] knowledge](http://hunch.net/?p=2714). A mind map of machine learning concepts, with great detail on each.
- [Matplotlib / Pandas / Python cheat sheets](https://drive.google.com/drive/folders/0ByIrJAE4KMTtaGhRcXkxNHhmY2M).

# Assorted Opinions and Other Resources

## More Data Science materials

I'm not repeating the materials mentioned above, but here are some other Data Science resources:

* **Extremely accessible data science book: [_Data Smart_ by John Foreman](http://www.john-foreman.com/data-smart-book.html)**
* **[An entire self-directed course in Data Science, as a IPython Notebook](http://learnds.com/)**
* [Data Science Workflow: Overview and Challenges](https://cacm.acm.org/blogs/blog-cacm/169199-data-science-workflow-overview-and-challenges/fulltext) (read the article *and also* the comment by Joseph McCarthy)
* Fun little IPython Notebook: [Web Scraping Indeed.com for Key Data Science Job Skills](http://nbviewer.jupyter.org/github/jmsteinw/Notebooks/blob/master/IndeedJobs.ipynb)
* Swami Chandrasekaran's ["Becoming a Data Scientist"](http://nirvacana.com/thoughts/becoming-a-data-scientist/) is a concise, printable picture of a data science curriculum

## Bayesian Statistics and Machine Learning

From [the "Bayesian Machine Learning" overview on Metacademy](https://metacademy.org/roadmaps/rgrosse/bayesian_machine_learning):

> ... Bayesian ideas have had a big impact in machine learning in the past 20 years or so because of the flexibility they provide in building structured models of real world phenomena. Algorithmic advances and increasing computational resources have made it possible to fit rich, highly structured models which were previously considered intractable.

You can learn more by studying one of the following resources. Both resources use Python, [PyMC](https://github.com/pymc-devs/pymc), and Jupyter Notebooks.
* The **free book,** _[Probabilistic Programming and Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)._ Made with a "computation/understanding-first, mathematics-second point of view." It's available in print too!
* [Bayesian Modelling in Python](https://github.com/markdregan/Bayesian-Modelling-in-Python)

## Risks

"Machine learning systems automatically learn programs from
data." Pedro Domingos, in ["A Few Useful Things to Know about Machine Learning."](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) The programs you generate will require maintenance. Like any way of creating programs faster, you can rack up [technical debt](https://en.wikipedia.org/wiki/Technical_debt).

Here is the abstract of [Machine Learning: The High-Interest Credit Card of Technical Debt](https://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/43146.pdf):

> Machine learning offers a fantastically powerful toolkit for building complex systems quickly. This paper argues that it is dangerous to think of these quick wins as coming for free. Using the framework of technical debt, we note that it is remarkably easy to incur massive ongoing maintenance costs at the system level when applying machine learning. The goal of this paper is highlight several machine learning specific risk factors and design patterns to be avoided or refactored where possible. These include boundary erosion, entanglement, hidden feedback loops, undeclared consumers, data dependencies, changes in the external world, and a variety of system-level anti-patterns.

If you're following this guide, you should read that paper. You can also [listen to a podcast episode interviewing one of the authors of this paper](https://softwareengineeringdaily.com/2015/11/17/machine-learning-and-technical-debt-with-d-sculley/).

A few more articles on the challenges running ML-powered systems in Production:

- **["Rules of [Reliable] Machine Learning: Best Practices for ML Engineering,"](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)** by Martin Zinkevich, regarding ML engineering practices and patterns in production at Google. Optional: [accompanying video](http://cs.stanford.edu/~jsteinhardt/wildml2016nips/videos/1_2_Martin.wmv).
- [**"What’s your ML Test Score? A rubric for ML production systems"**](https://0586f9b3-a-62cb3a1a-s-sites.googlegroups.com/site/wildml2016nips/SculleyPaper1.pdf?attachauth=ANoY7crRjdpoElseeyOPu-wR0eV9Engf3Cm9LKs0PAB4j-nDQuw9gE426Ug2HM-0BZ7qJjtLHVtpgwbP6zfNYyE_2gWkU5ACKczAIuKCTHq9nT0JEGpEL5TCT3APmScXKkS8HTqhJz-wen6vbq9XeHh_M5Heg49ozxsIiGMzX7PvIKxpnvViDOBLNymVQOkxuvX0-xnQThxU9CjEWQH25vOwdpJi-VQl1w%3D%3D&attredirects=0) by Eric Breck, Shanqing Cai, Eric Nielsen, Michael Salib, D. Sculley, Google.
- **[Surviving Data Science "at the Speed of Hype"](http://www.john-foreman.com/blog/surviving-data-science-at-the-speed-of-hype)** by John Foreman, Data Scientist at MailChimp
- [The High Cost of Maintaining Machine Learning Systems](http://www.kdnuggets.com/2015/01/high-cost-machine-learning-technical-debt.html)
- [11 Clever Methods of Overfitting and How to Avoid Them](http://hunch.net/?p=22)
- [The Perilous World of Machine Learning for Fun and Profit: Pipeline Jungles and Hidden Feedback Loops](http://www.john-foreman.com/blog/the-perilous-world-of-machine-learning-for-fun-and-profit-pipeline-jungles-and-hidden-feedback-loops)


### Welcome to the Danger Zone

So you are dabbling with Machine Learning. You've got Hacking Skills. Maybe you've got some "knowledge" in Domingos' sense (some "Substantive Expertise" or "Domain Knowledge"). This diagram is modified slightly from Drew Conway's "Data Science Venn Diagram." It isn't a _perfect_ fit for us, but it may get the point across:

[![Drew Conway's Data Science Venn Diagram, modified slightly](https://user-images.githubusercontent.com/2420688/29441268-f429d88c-837e-11e7-83ff-30874d832c89.png)](http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram)

**Please** don't sell yourself as a Machine Learning expert while you're still in the Danger Zone. Don't build bad products or publish junk science. (Also please [don't be evil](https://arstechnica.co.uk/security/2016/02/the-nsas-skynet-program-may-be-killing-thousands-of-innocent-people/).) This guide can't tell you how you'll know you've "made it" into Machine Learning competence ... let alone expertise. It's hard to evaluate proficiency without schools or other institutions. This is a common problem for self-taught people.

#### Towards Expertise

You need **practice.** [On Hacker News, user olympus commented to say you could use competitions to practice and evaluate yourself](https://news.ycombinator.com/item?id=10508565). [Kaggle](https://www.kaggle.com/competitions) and [ChaLearn](http://www.chalearn.org/) are hubs for Machine Learning competitions. You can find some [examples of code for popular Kaggle competitions here](https://github.com/apeeyush/machine-learning). For smaller exercises, [try HackerRank](https://www.hackerrank.com/domains/ai/machine-learning/page/1).

You also need **understanding.** You should review what Kaggle competition winners say about their solutions, [for example, the "No Free Hunch" blog](http://blog.kaggle.com/). These might be over your head at first but once you're starting to understand and appreciate these, you know you're getting somewhere.

Competitions and challenges are just one way to practice. You shouldn't limit yourself, though - and you should also understand that [Machine Learning isn't **all** about Kaggle competitions](https://jvns.ca/blog/2014/06/19/machine-learning-isnt-kaggle-competitions).

Here's a complementary way to practice: **do practice studies.**

1. **Ask a question. Start your own study.** The ["most important thing in data science is the question"](https://github.com/DataScienceSpecialization/courses/blob/master/01_DataScientistToolbox/03_02_whatIsData/index.Rmd#the-data-is-the-second-most-important-thing) ([Dr. Jeff T. Leek](https://github.com/jtleek)). So start with a question. Then, find [real data](https://github.com/caesar0301/awesome-public-datasets). Analyze it. Then ...
2. **Communicate results.** When you have a novel finding, reach out for peer review.
3. **Fix issues.** Learn. Share what you learn.

And repeat. Re-phrasing this, it fits with the [scientific method](https://en.wikipedia.org/wiki/Scientific_method): formulate a question (or problem statement), create a hypothesis, gather data, analyze the data, and communicate results. (You should [watch this video about the scientific method in data science](http://101.datascience.community/2012/06/27/the-data-scientific-method/), and/or [read this article](http://customerthink.com/getting-insights-using-data-science-skills-and-the-scientific-method/).)

How can you come up with interesting questions? Here's one way. Every Sunday, [browse datasets](https://github.com/caesar0301/awesome-public-datasets) and write down some questions. Also, sign up for [Data is Plural](https://tinyletter.com/data-is-plural), a newsletter of interesting datasets; look at these, datasets, and write down questions. Stay curious. When a question inspires you, start a study.

This advice, to do practice studies and learn from peer review, is based on [a conversation](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-153934120) with [Dr. Randal S. Olson](http://www.randalolson.com/). Here's more advice from Olson, [quoted with permission:](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-154135498)

> I think the best advice is to tell people to always present their methods clearly and to avoid over-interpreting their results. Part of being an expert is knowing that there's rarely a clear answer, especially when you're working with real data.

As you repeat this process, your practice studies will become more scientific, interesting, and focused. The most important part of this process is peer review.

#### Ask for Peer Review

Here are some communities where you can reach out for peer review:

* [Cross-Validated: stats.stackexchange.com](https://stats.stackexchange.com/)
* [/r/DataIsBeautiful](https://reddit.com/r/DataIsBeautiful)
* [/r/DataScience](https://reddit.com/r/DataScience)
* [/r/MachineLearning](https://reddit.com/r/MachineLearning)
* [Hacker News: news.ycombinator.com](https://news.ycombinator.com). You'll probably want to submit as "Show HN"

Post to any of those, and ask for feedback. You'll get feedback. You'll learn a ton. As experts review your work you will learn a lot about the field. You'll also be practicing a crucial skill: accepting critical feedback.

When I read the feedback on my Pull Requests, first I repeat to myself, "I will not get defensive, I will not get defensive, I will not get defensive." You may want to do that before you read reviews of your Machine Learning work too.

----

## Collaborate with Domain Experts!

Machine Learning can be powerful, but it is not magic.

Whenever you apply Machine Learning to solve a problem, you are going to be working in some specific problem domain. To get good results, you or your team will need "substantive expertise" AKA "domain knowledge." Learn what you can, for yourself... But you should also **collaborate.** You'll have better results if you collaborate with domain experts. (What's a domain expert? See the [Wikipedia entry](https://en.wikipedia.org/wiki/Subject-matter_expert), or [c2 wiki's rather subjective but useful blurb](http://wiki.c2.com/?DomainExpert).)

### :bow: A note about Machine Learning and User Experience

Why pick out UX? Well, today we are [_surrounded_](https://en.wikipedia.org/wiki/Machine_learning#Applications) by software that utilizes Machine Learning. Often, the results are directly user-facing, and intended to enhance UX.

Before you start working ML into every aspect of _your_ software, you should get a better understanding of UX, as well as how ML and UX can relate. For some cursory overview, [start with Quora](https://www.quora.com/search?q=machine+learning+ux), which has some interesting, thoughtful discussions on the subject. Then, if you you know a coworker or friend who works in UX, take them out for coffee or lunch and pick their brain. I think they'll have words of encouragement as well as caution. _(Do you know good resources on this? Pull requests welcome for all parts of this guide, including this section!)_

By no means will that make you an expert in UX, but maybe it'll help you know if/when to reach out for help (hint: almost always — UX is really tricky and you should work with experts if you can!).

### :bow: A note about Machine Learning and Security (InfoSec, AppSec)

There was a great BlackHat webcast on this topic, [Secure Because Math: Understanding Machine Learning-Based Security Products.](https://www.blackhat.com/html/webcast/02192015-secure-because-math.html) Slides are [here](https://www.blackhat.com/html/webcast/02192015-secure-because-math.html), [video recording is here.](https://attendee.gotowebinar.com/recording/80449431422110210) If you're using ML to recommend some media, overfitting could be harmless. If you're relying on ML to protect from threats, overfitting could be downright dangerous. Check the full presentation if you are interested in this space.

If you want to explore this space more deeply, there is a _lot_ of reading material in the below links:

* [Security Data Science and Machine Learning Guide](http://www.covert.io/the-definitive-security-datascience-and-machinelearning-guide/)
* [Awesome ML for Cybersecurity](https://github.com/jivoi/awesome-ml-for-cybersecurity)
* [Awesome AI Security](https://github.com/RandomAdversary/Awesome-AI-Security)
* [Awesome Adversarial Machine Learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning)

----


## Deep Learning

In early editions of this guide, there was no specific "Deep Learning" section. I omitted it intentionally. I think it is not effective for us to jump too far ahead. I also know that if you become an expert in traditional Machine Learning, you'll be capable of moving onto advanced subjects like Deep Learning, whether or not I've put that in this guide. We're just trying to get you started here!

Maybe this is a way to check your progress: ask yourself, does Deep Learning seem like magic? If so, take that as a sign that you aren't ready to work with it professionally. Let the fascination motivate you to learn more. I have read some argue you can learn Deep Learning in isolation; I have read others recommend it's best to master traditional Machine Learning first. Why not start with traditional Machine Learning, and develop your reasoning and intuition there? You'll only have an easier time learning Deep Learning after that. After all of it, you'll able to tackle all sorts of interesting problems.

In any case, when you decide you're ready to dive into Deep Learning, here are some helpful resources.

* **["Have Fun With [Deep] Learning" by David Humphrey.](https://github.com/humphd/have-fun-with-machine-learning)** This is an excellent way to "get ahead of yourself" and hack-first. Then you will feel excited to move onto...
*  **[Prof. Andrew Ng's](https://www.andrewng.org/about/) [courses on Deep Learning](https://www.coursera.org/specializations/deep-learning)!** There five courses, as part of the [Deep Learning Specialization on Coursera](https://www.coursera.org/specializations/deep-learning). These courses are part of his new venture, [deeplearning.ai](https://www.deeplearning.ai)
* **[_Deep Learning_](http://www.deeplearningbook.org/), a free book published MIT Press.** By Ian Goodfellow, Yoshua Bengio and Aaron Courville
* [YerevaNN's Deep Learning Guide](http://yerevann.com/a-guide-to-deep-learning/)
* [Quora: "What are the best ways to pick up Deep Learning skills as an engineer?"](https://www.quora.com/What-are-the-best-ways-to-pick-up-Deep-Learning-skills-as-an-engineer) — answered by Greg Brockman (Co-Founder & CTO at OpenAI, previously CTO at Stripe)
* [Sonnet](https://github.com/deepmind/sonnet) - a python library built on top of TensorFlow for building complex neural networks. Made by Google DeepMind.

## "Big" Data?

Scaling data analysis is a familiar problem now, and there's no shortage of ways to address it. [Beware needless hype and companies selling you flashy, proprietary solutions.](http://www.john-foreman.com/blog/surviving-data-science-at-the-speed-of-hype) You can do it all with open-source tools. Even if "buy" instead of "build," you may want to buy from vendors who use known good stacks. No news here.

There are [other lists of Awesome Machine Learning tools](https://github.com/josephmisiti/awesome-machine-learning), so I won't re-do all that. But in the Big Data section, I would be remiss if I didn't mention...

* **[Apache Spark.](https://spark.apache.org/mllib/)** "MLlib is Apache Spark's scalable machine learning library."
	* Aside from the scalability, Spark has great APIs. And what's more, [Spark has DataFrames and easy co-operability with pandas!](https://databricks.com/blog/2015/02/17/introducing-dataframes-in-spark-for-large-scale-data-science.html)
	* Berkeley has [a course on Scalable Machine Learning, focusing on Apache Spark.](https://www.edx.org/course/scalable-machine-learning-uc-berkeleyx-cs190-1x#.VOC70VPF_lQ)

If you are working with data-intensive applications at all, I'll recommend this book:

* **[_Designing Data-Intensive Applications_](http://dataintensive.net)** by Martin Kleppman. (You can start reading it online, free, via Safari Books.) It's not specific to Machine Learning, but you can bridge that gap yourself.

Lastly, here are some other useful links regarding Big Data and ML.

* [10 things statistics taught us about big data analysis](https://simplystatistics.org/2014/05/22/10-things-statistics-taught-us-about-big-data-analysis/) (and some more food for thought: ["What Statisticians think about Data Scientists"](http://www.datasciencecentral.com/profiles/blogs/what-statisticians-think-about-data-scientists))
* ["Talking Machines" #12](http://www.thetalkingmachines.com/blog/2015/6/4/the-economic-impact-of-machine-learning-and-using-the-kernel-trick-to-dig-in-to-big-data): Interviews Prof. Andrew Ng (from [our main course, which has its own module on big data](https://www.coursera.org/learn/machine-learning)); this episode covers some problems relevant to _high-dimensional_ data
- ["Talking Machines" #15: "Really Really Big Data and Machine Learning in Business"](http://www.thetalkingmachines.com/blog/2015/7/16/really-really-big-data-and-machine-learning-in-business)
- Free eBook, [_Getting Data Right: Tackling the Challenges of
Big Data Volume and Variety_](https://www.tamr.com/landing-pages/getting-data-right/) by Michael Stonebraker, Tom Davenport, James Markarian, and others, published by O'Reilly. You can [listen to an accompanying podcast](http://radar.oreilly.com/2015/06/the-future-of-data-at-scale.html) too.

----

## Finding Open-Source Libraries

* Bookmark **[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)**, a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) Machine Learning libraries and software.
* Bookmark [Pythonidae](https://github.com/svaksha/pythonidae/blob/master/AI.md#machine-learning), a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) libraries and software in the Python language - with a section on Machine Learning.
* Bookmark [Julia.jl](https://github.com/svaksha/Julia.jl/blob/master/AI.md#machine-learning), a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) libraries and software in the Julia language - with a section on Machine Learning.
* [TensorFlow](https://www.tensorflow.org/) seems like a [really big deal.](https://news.ycombinator.com/item?id=10532957) People like you will do exciting things with TensorFlow. It's a framework. Frameworks can help you manage complexity. Just remember this rule of thumb: **"More data beats a cleverer algorithm"** (Domingos), no matter how cool your tools are. Also note, TensorFlow is not the only machine learning framework of its kind: **[Check this great, detailed comparison of TensorFlow, Torch, and Theano.](https://github.com/zer0n/deepframeworks)** See also [Newmu/Theano-Tutorials](https://github.com/Newmu/Theano-Tutorials) and  [nlintz/TensorFlow-Tutorials](https://github.com/nlintz/TensorFlow-Tutorials). See also the section on Deep Learning above.
* For Machine-Learning libraries that might not be on PyPI, GitHub, etc., there's [MLOSS (Machine Learning Open Source Software)](http://mloss.org/software/). Seems to feature many academic libraries.
* [CreativeAi.net](http://www.creativeai.net/). OK not exactly about _libraries_, but this is often intriguing, and worth subscribing to  ... warning, it's easy to get sucked in :)

----

## Alternative ways to "Dive into Machine Learning"

Here are some other guides to Machine Learning. They can be alternatives or complements to this guide.

* ["How would your curriculum for a machine learning beginner look like?"](https://sebastianraschka.com/faq/docs/ml-curriculum.html) by Sebastian Raschka. A selection of the core online courses and books for getting started with machine learning and gaining expert knowledge. It contextualizes Raschka's own book, [_Python Machine Learning_](https://github.com/rasbt/python-machine-learning-book) (which I would have linked to anyway!) See also [`pattern_classification` GitHub repository](https://github.com/rasbt/pattern_classification) maintained by the author, which contains IPython notebooks about various machine learning algorithms and various data science related resources.
* [Materials for Learning Machine Learning](http://jacksimpson.co/materials-for-learning-machine-learning/) by Jack Simpson
* [Machine Learning for Developers](http://xyclade.github.io/MachineLearning/) is another good introduction, perhaps better if you're more familiar with Java or Scala. It introduces machine learning for a developer audience using Smile, a machine learning library that can be used both in Java and Scala.
* [Machine Learning for Programmers [with caveats]](https://gist.github.com/hangtwenty/a15c8bed5b120eebf352): Pragmatic guide for developers, definitely worth a read. I've linked you to my own intro to it, explaining a few caveats. Taking it with a grain of salt, and these caveats in mind, I think some programmers will find it worth their time.
* [Example Machine Learning notebook, exercise, and guide](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb) by Dr. Randal S. Olson. Mentioned in Notebooks section as well, but it has a similar goal to this guide (introduce you, and show you where to go next). Rich "Further Reading" section.
* [Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers) by Nam Vu. It’s the top-down and results-first approach designed for software engineers.
* For some news sources to follow, check out [Sam DeBrule's list](https://machinelearnings.co/a-humans-guide-to-machine-learning-e179f43b67a0) here.
* [Your guide here]
