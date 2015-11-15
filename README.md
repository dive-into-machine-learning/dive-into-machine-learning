# Dive into Machine Learning [![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

**Hi there! This guide is for you:**

* **You're new to Machine Learning.**
* **You know Python.** (At least the basics! If you want to learn Python, try [Dive Into Python.](http://www.diveintopython.net/))

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

You can install Python 3 and all of these packages in a few clicks with the [Anaconda Python distribution](https://www.continuum.io/downloads). Anaconda is popular in the Data Science and Machine Learning communities.

If you're using Python 2.7, don't worry. You don't have to migrate to Python 3 just for this guide. Also, if you're using pip/virtualenv instead of Anaconda, that's alright too! Confer [conda vs. pip vs. virtualenv](http://conda.pydata.org/docs/_downloads/conda-pip-virtualenv-translator.html) if you're curious.

## Let's go!

**[Learn how to use IPython Notebook](http://opentechschool.github.io/python-data-intro/core/notebook.html) (5-10 minutes).** (You can [learn by screencast](https://www.youtube.com/watch?v=qb7FT68tcA8) instead.

Now, follow along with this brief exercise (10 minutes): **[An introduction to machine learning with scikit-learn](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)**. Do it in `ipython` or IPython Notebook. It'll really boost your confidence.

[![I'll wait.](http://i.imgur.com/nqn3pVV.jpg)](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)

## What just happened?

You just classified some hand-written digits using [scikit-learn]. Neat huh?

[scikit-learn] is the go-to library for machine learning in Python. [Some recognizable logos use it, including Spotify and Evernote.](http://scikit-learn.org/stable/testimonials/testimonials.html) Machine learning is hard. You'll be glad your tools are easy to work with.

[scikit-learn]: http://scikit-learn.org/stable/index.html

I encourage you to look at the [scikit-learn] homepage and spend about 5 minutes looking over the names of the strategies (Classification, Regression, etc.), and their applications. Don't click through yet! Just get a glimpse of the vocabulary.

# Dive in

## A Visual Introduction to Machine Learning

Let's learn a bit more about Machine Learning, and a couple of common ideas and concerns. Read ["A Visual Introduction to Machine Learning, Part 1"](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) by [Stephanie Yee](https://twitter.com/stephaniejyee) and [Tony Chu](https://twitter.com/tonyhschu/).

[![A Visual Introduction to Machine Learning, Part 1](http://i.imgur.com/j5fiTBv.gif)](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)

It won't take long. It's a beautiful introduction ... Try not to drool too much!

## A Few Useful Things to Know about Machine Learning

OK. Let's dive deeper.

Read **["A Few Useful Things to Know about Machine Learning"](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)** by Pedro Domingos. It's densely packed with valuable information, but not opaque. The author understands that there's a lot of "black art" and folk wisdom, and they invite you in.

Take your time with this one. Take notes. Don't worry if you don't understand it all yet.

The whole paper is packed with value, but I want to call out two points:

- **Data alone is not enough.** This is where science meets art in machine-learning. Quoting Domingos: "... the need for knowledge in learning should not be surprising. Machine learning is not magic; it can’t get something from nothing. What it does is get more from less. Programming, like all engineering, is a lot of work: we have to build everything from scratch. Learning is more like farming, which lets nature do most of the work. Farmers combine seeds with nutrients to grow crops. Learners combine knowledge with data to grow programs."
- **More data beats a cleverer algorithm.** Listen up, programmers. We like cool tools. Resist the temptation to reinvent the wheel, or to over-engineer solutions. Your starting point is to [Do the Simplest Thing that Could _Possibly_ Work](http://www.artima.com/intv/simplest3.html). Quoting Domingos: "Suppose you’ve constructed the best set of features you can, but the classifiers you’re getting are still not accurate enough. What can you do now? There are two main choices: design a better learning algorithm, or gather more data. [...] As a rule of thumb, a dumb algorithm with lots and lots of data beats a clever one with modest amounts of it. (After all, machine learning is all about letting data do the heavy lifting.)"

So  **knowledge** and **data** are critical. Focus your efforts on those, before fussing about algorithms. In practice, this means that unless you _have_ to increase complexity, you should continue to [Do Simple Things]; don't rush to neural networks just because they're cool. To improve your model, get more data  and use your knowledge of the problem to manipulate the data. You should spend most of your time on these steps. Only optimize your choice of algorithms after you've got enough data, and you've processed it well.

![What has the most impact in Machine Learning](http://i1381.photobucket.com/albums/ah240/hangtwenty/Screen%20Shot%202015-03-05%20at%2010.08.10%20PM_zpsqnljkqt5.png)

(Chart inspired by a slide from [Alex Pinto's talk, "Secure Because Math: A Deep-Dive on ML-Based Monitoring"](https://www.youtube.com/watch?v=TYVCVzEJhhQ).)

[Do Simple Things]: http://c2.com/cgi/wiki?DoSimpleThings

## Talking Machines

Subscribe to **[Talking Machines](http://www.thetalkingmachines.com/)**, a podcast about machine learning. It's great. It's a low-effort, high-yield way to learn more.

I suggest this listening order:

* Start with the ["Starting Simple"](http://www.thetalkingmachines.com/blog/2015/4/23/starting-simple-and-machine-learning-in-meds) episode. It supports what we read from Domingos. Ryan Adams talks about starting simple, as discussed above. Adams also stresses the importance of feature engineering. Feature engineering is an exercise of the "knowledge" Domingos writes about.
* Then, start over from the first episode.

## Play to learn

Pick **one or two** of these IPython Notebooks and play along.

- [Face Recognition on a subset of the Labeled Faces in the Wild](http://nbviewer.ipython.org/github/ogrisel/notebooks/blob/master/Labeled%20Faces%20in%20the%20Wild%20recognition.ipynb)
- [Machine Learning from Disaster](http://agconti.github.io/kaggle-titanic/): Using Titanic data, "Demonstrates basic data munging, analysis, and visualization techniques. Shows examples of supervised machine learning techniques."
- [Election Forecasting](https://github.com/jseabold/538model): A replication of the model Nate Silver used to make [predictions about the 2012 US Presidential Election for the New York Times](http://fivethirtyeight.blogs.nytimes.com/fivethirtyeights-2012-forecast/))
- [An example Machine Learning notebook](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb): "let's pretend we're working for a startup that just got funded to create a smartphone app that automatically identifies species of flowers from pictures taken on the smartphone.  We've been tasked by our head of data science to create a demo machine learning model that takes four measurements from the flowers (sepal length, sepal width, petal length, and petal width) and identifies the species based on those measurements alone."
- ClickSecurity's "data hacking" series (thanks [hummus](https://github.com/hummus)!)
	- [Detect Algorithmically Generated Domains](http://nbviewer.ipython.org/github/ClickSecurity/data_hacking/blob/master/dga_detection/DGA_Domain_Detection.ipynb).
	- [Detect SQL Injection](http://nbviewer.ipython.org/github/ClickSecurity/data_hacking/blob/master/sql_injection/sql_injection.ipynb).
	- [Java Class File Analysis](http://nbviewer.ipython.org/github/ClickSecurity/data_hacking/blob/master/java_classification/java_classification.ipynb): is this Java code malicious or benign?
- If you want more of a data science bent, pick a notebook from [this excellent list of Data Science ipython notebooks](https://github.com/donnemartin/data-science-ipython-notebooks). "Continually updated Data Science Python Notebooks: Spark, Hadoop MapReduce, HDFS, AWS, Kaggle, scikit-learn, matplotlib, pandas, NumPy, SciPy, and various command lines."
- Or more generic tutorials/overviews ...
	- [Tutorial introduction to machine learning with sklearn](http://amueller.github.io/sklearn_tutorial/).
	- [An Introduction to Supervised Learning via Scikit Learn](http://bugra.github.io/work/notes/2014-11-22/an-introduction-to-supervised-learning-scikit-learn/).
	- [An Introduction to Unsupervised Learning via Scikit Learn](http://bugra.github.io/work/notes/2014-11-16/an-introduction-to-unsupervised-learning-scikit-learn/).

There are more places to find great IPython Notebooks:

* [A Gallery of Interesting IPython notebooks (wiki page on GitHub): Statistics, Machine Learning and Data Science](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks#statistics-machine-learning-and-data-science).
* [Fabian Pedregosa's larger, automatic gallery](http://nb.bianp.net/sort/views/).

# Immerse yourself

Pick one of the courses below and do the whole thing.

## Recommended course

**[Prof. Andrew Ng's online course _Machine Learning_]( https://www.coursera.org/learn/machine-learning) is a free online course I've [seen](https://docs.google.com/document/d/1YN6BVdReNAYc8B0fjQ84yzDflqmeEPj7S0Xc-9_26R0/) [recommended](http://www.forbes.com/sites/anthonykosner/2013/12/29/why-is-machine-learning-cs-229-the-most-popular-course-at-stanford/) [often.](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Cory-Hicks-1) [And](https://www.quora.com/How-do-I-learn-machine-learning-1/answers/5673) [emphatically.](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Xavier-Amatriain)**

It's helpful if you decide on a pet project to play around with, as you go, so you have a way to apply your knowledge. You could use one of these [Awesome Public Datasets](https://github.com/caesar0301/awesome-public-datasets) or pick one of these [OpenData](https://github.com/svaksha/pythonidae/blob/master/Open-Data.md)sets. And remember, IPython Notebook is your friend.

Also, the book _[Elements of Statistical Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/)_ comes up frequently, but is usually referred to as a "reference" not an introduction. It's free, so download or bookmark it!

## Other courses

Here are some other free online courses I've seen recommended. (Machine Learning, Data Science, and related topics.)

* [Machine Learning](https://www.coursera.org/course/machlearning) by Prof. Pedro Domingos of the University of Washington. Domingos wrote the paper ["A Few Useful Things to Know About Machine Learning"](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) quoted earlier in this guide. (Thanks to [Hacker News user, paperwork.](https://news.ycombinator.com/item?id=9563501))
* Data science courses as IPython Notebooks:
	- [Practical Data Science](http://radimrehurek.com/data_science_python/)
	- [Learn Data Science (an entire self-directed course!)](http://learnds.com/)
	- Supplementary material: [donnemartin/data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks). "Continually updated Data Science Python Notebooks: Spark, Hadoop MapReduce, HDFS, AWS, Kaggle, scikit-learn, matplotlib, pandas, NumPy, SciPy, and various command lines."
* General Assembly's [DAT5](https://github.com/justmarkham/DAT5) (revision of [DAT4](https://github.com/justmarkham/DAT4) and  [DAT3](https://github.com/justmarkham/DAT3)). Interactive.
* Surveys of Data Science courseware (a bit more Choose Your Own Adventure)
	* Check out [Jack Golding's survey of Data Science courseware](https://www.quora.com/Is-it-worth-it-to-pay-9-*-49-for-a-data-science-specialization-on-Coursera/answer/Jack-Golding). Includes Coursera's [Data Science Specialization](https://www.coursera.org/specializations/jhudatascience) with 9 courses in it. The Specialization certificate isn't free, but you can take the courses 1-by-1 for free if you don't care about the certificate. The survey also covers [Harvard CS109](http://cs109.github.io/2014/) which I've seen recommended elsewhere.
	* [Another epic Quora thread: How can I become a data scientist?](https://www.quora.com/How-can-I-become-a-data-scientist?redirected_qid=59455)
	* Data Science Weekly's [Big List of Data Science Resources](http://www.datascienceweekly.org/data-science-resources/the-big-list-of-data-science-resources) has a [List of Data Science MOOCs](http://www.datascienceweekly.org/data-science-resources/data-science-moocs)
* [Data Science (Harvard CS109)](http://cs109.github.io/2014/).
* [Advanced Statistical Computing (Vanderbilt BIOS8366)](http://stronginference.com/Bios8366/lectures.html) -- great option, interactive (lots of IPython Notebook material)

## Learn Pandas well

If you're focusing on Python, you should get more familiar with Pandas.

* **Essential**: [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html).
* **Essential**: [Things in Pandas I Wish I'd Had Known Earlier](http://nbviewer.ipython.org/github/rasbt/python_reference/blob/master/tutorials/things_in_pandas.ipynb) (IPython Notebook)
* [Useful Pandas Snippets](http://www.swegler.com/becky/blog/2014/08/06/useful-pandas-snippets/)
* Here are some docs I found especially helpful as I continued learning:
	* [Cookbook](http://pandas.pydata.org/pandas-docs/stable/cookbook.html)
	* [Data Structures](http://pandas.pydata.org/pandas-docs/stable/dsintro.html), esp. [DataFrame](http://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe) section.
	* [Reshaping by pivoting DataFrames](http://pandas.pydata.org/pandas-docs/version/0.15.0/reshaping.html).
	* [Computational tools](http://pandas.pydata.org/pandas-docs/stable/computation.html) and [StackExchange thread: "What is covariance in plain language?"](http://stats.stackexchange.com/questions/29713/what-is-covariance-in-plain-language).
	* [Group By (split, apply, and combine DataFrames)](http://pandas.pydata.org/pandas-docs/stable/groupby.html).
	* [Visualizing your DataFrames](http://pandas.pydata.org/pandas-docs/version/0.15.0/visualization.html).


## Cheat sheets

Bookmark these cheat sheets:

- [scikit-learn algorithm cheat sheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/).
- [Metacademy: a package manager for [machine learning] knowledge](http://hunch.net/?p=2714). A mind map of machine learning concepts, with great detail on each.
- [Matplotlib / Pandas / Python cheat sheets](https://drive.google.com/folderview?id=0ByIrJAE4KMTtaGhRcXkxNHhmY2M). By [@Mark_Graph](https://twitter.com/Mark_Graph).

## More topics

### More Data Science materials

Not repeating the materials mentioned above, here are some more Data Science resources:

* **Extremely accessible data science book: [_Data Smart_ by John Foreman](http://www.john-foreman.com/data-smart-book.html)**
* **[An entire self-directed course in Data Science, as a IPython Notebook](http://learnds.com/)**
* [Data Science Workflow: Overview and Challenges](http://cacm.acm.org/blogs/blog-cacm/169199-data-science-workflow-overview-and-challenges/fulltext) (read the article & the comment by Joseph McCarthy).
* Fun little IPython Notebook: [Web Scraping Indeed.com for Key Data Science Job Skills](http://nbviewer.ipython.org/github/jmsteinw/Notebooks/blob/master/IndeedJobs.ipynb).


### Many more specialized topics

Check out [Gideon Wulfsohn](http://gwulfs.github.io/)'s [**excellent** introduction to Machine Learning](https://docs.google.com/document/d/1YN6BVdReNAYc8B0fjQ84yzDflqmeEPj7S0Xc-9_26R0) for specialized knowledge on many topics... including [Ensemble Methods](http://www.quora.com/How-do-random-forests-work-in-laymans-terms), [Apache Spark](https://spark.apache.org/examples.html), [Neural Networks](https://www.coursera.org/course/neuralnets), [Reinforcement Learning](http://pybrain.org/), [Natural Language Processing](https://nltk.org) ([RNN](https://github.com/IndicoDataSolutions/Passage), [LDA](http://bugra.github.io/work/notes/2015-02-21/topic-modeling-for-the-uninitiated/), [Word2Vec](http://rare-technologies.com/word2vec-tutorial/)), [Structured Prediction](https://pystruct.github.io/), [Deep Learning](https://www.youtube.com/watch?v=S75EdAcXHKk), [Distributed Systems (Hadoop Ecosystem)](http://web.stanford.edu/class/cs246/), Graphical Models ([Hidden Markov Models](http://www.autonlab.org/tutorials/hmm.html)), [Hyper Parameter Optimization](https://github.com/hyperopt/hyperopt), [GPU Acceleration (Theano)](http://deeplearning.net/software/theano/tutorial/using_gpu.html), [Computer Vision](http://deeplearning.net/tutorial/lenet.html), Internet of Things, and Visualization.

Here's an IPython Notebook book about [Probabilistic Programming and Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/): "An intro to Bayesian methods and probabilistic programming from a computation/understanding-first, mathematics-second point of view."

## Questions, answers, chats

For now, the best StackExchange site is  [stats.stackexchange.com – _machine-learning_.](http://stats.stackexchange.com/questions/tagged/machine-learning?sort=frequent&pageSize=15). There's also [datascience.stackexchange.com](http://datascience.stackexchange.com/), but it's still in Beta.) and there is [/r/machinelearning](https://www.reddit.com/r/machinelearning). There are also many relevant discussions on Quora, for example: [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1).

You should also [join the Gitter channel for scikit-learn!]( https://gitter.im/scikit-learn/scikit-learn)

For help and community in meatspace, seek out meetups. Data Science Weekly's [Big List of Data Science Resources](http://www.datascienceweekly.org/data-science-resources/the-big-list-of-data-science-resources) may help you.

# Assorted Opinions and Other Resources

The rest of the stuff that might not be structured enough for a course, but seems important to know.

## Risks

"Machine learning systems automatically learn programs from data." Pedro Domingos, in ["A Few Useful Things to Know about Machine Learning."](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) The programs you generate will require maintenance. Like any way of creating programs faster, you can rack up technical debt.

Really essential:

- **[Surviving Data Science "at the Speed of Hype"](http://www.john-foreman.com/blog/surviving-data-science-at-the-speed-of-hype)** by John Foreman, Data Scientist at MailChimp
- [11 Clever Methods of Overfitting and How to Avoid Them](http://hunch.net/?p=22)

A worthwhile paper: [Machine Learning: The High-Interest Credit Card of Technical Debt.](https://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/43146.pdf) Here's the abstract:

> Machine learning offers a fantastically powerful toolkit for building complex systems quickly. This paper argues that it is dangerous to think of these quick wins as coming for free. Using the framework of technical debt, we note that it is remarkably easy to incur massive ongoing maintenance costs at the system level when applying machine learning. The goal of this paper is highlight several machine learning specific risk factors and design patterns to be avoided or refactored where possible. These include boundary erosion, entanglement, hidden feedback loops, undeclared consumers, data dependencies, changes in the external world, and a variety of system-level anti-patterns.

And a few more articles:

- [The Perilous World of Machine Learning for Fun and Profit: Pipeline Jungles and Hidden Feedback Loops](http://www.john-foreman.com/blog/the-perilous-world-of-machine-learning-for-fun-and-profit-pipeline-jungles-and-hidden-feedback-loops)
- [The High Cost of Maintaining Machine Learning Systems](http://www.kdnuggets.com/2015/01/high-cost-machine-learning-technical-debt.html)

### Welcome to the Danger Zone

So you are dabbling with Machine Learning. You've got Hacking Skills. Maybe you've got some "knowledge" in Domingos' sense (some "Substantive Expertise" or "Domain Knowledge"). This diagram isn't a perfect fit for us, but may get the point across:

[![Drew Conway's Data Science Venn Diagram, modified slightly](http://i.imgur.com/cH5Rkko.png)](http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram)

**Please** don't sell yourself as a Machine Learning expert while you're still in the Danger Zone. Don't build bad products or publish junk science. This guide can't tell you how you'll know you've "made it" into Machine Learning competence ... let alone  expertise. It's hard to evaluate proficiency without schools or other institutions. This is a common problem for self-taught people.

#### Towards Expertise

[Hacker News user, olympus commented to say you could use competitions to practice and evaluate yourself](https://news.ycombinator.com/item?id=10508565). [Kaggle](http://www.kaggle.com/competitions) and [ChaLearn](http://www.chalearn.org/) are hubs for Machine Learning competitions. Review what the winners had to say about their solutions, for example, [the "No Free Hunch" blog](http://blog.kaggle.com/). These might be over your head at first but once you're starting to understand and appreciate these, you know you're getting somewhere. And if you compete, get a solution on the leaderboard, or even win — bravo! You may be an expert.

But not everybody thinks this is the best approach.

Here's another approach: do practice projects, yes, but do them on your own, and focus on community and feedback. Specifically:

1. Practice a lot with real data. Work with datasets that interest you.
2. When you have a novel finding, reach out for review (see below).
3. Fix issues. Learn. Share what you learn.

And repeat. This advice comes via [Dr. Randal S. Olson](http://www.randalolson.com/). [Quoted with permission:](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-154135498)

> I think the best advice is to tell people to always present their methods clearly and to avoid over-interpreting their results. Part of being an expert is knowing that there's rarely a clear answer, especially when you're working with real data.

At some point, you'll know you are becoming an expert. Or someone will be able to tell you!

#### Ask for Peer Review

Here are some communities where you can reach out for review:

* [Cross-Validated: stats.stackexchange.com](https://stats.stackexchange.com/)
* [/r/DataIsBeautiful](https://reddit.com/r/DataIsBeautiful)
* [/r/DataScience](https://reddit.com/r/DataScience)
* [/r/MachineLearning](https://reddit.com/r/MachineLearning)
* [Hacker News: news.ycombinator.com](https://news.ycombinator.com). You'll probably want to submit as "Show HN".

Post to any of those, and ask for feedback. You'll get feedback. You'll learn a ton. As experts review your work you will learn a lot about the field. You'll also be practicing the skill of accepting critical feedback.

When I read the feedback on my Pull Requests, first I repeat to myself, "I will not get defensive, I will not get defensive, I will not get defensive." You may want to do that before you read reviews of your Machine Learning work too.

### An Anecdote About User Experience

If you create software for users, and you want to use machine learning to benefit your users, *you must understand your users.* I won't get into a whole user experience lesson here, but in short, you must think about user experience.

I have a friend who worked at `<Redacted>` Music Streaming Service. This company used machine learning in their recommendation and radio services. He complained about the way the company scored the radio feature's performance. There was disagreement about what should be scored. They used a metric, "no song skips." But why? Sure that indicates the recommendation wasn't *awful*, what if you want to measure engagement? Other metrics could measure positive engagement: "favorites," shares, listening time, or whether the listener returns to the radio station later. Measuring "no skips" might work for the passive listener, but the engaged listener is different. Perhaps the engaged listener will skip 5 songs, but find 20 songs they love and come back to the service later.

**My takeaway:** user experience matters just as much as ever. You must understand *which kind* of user you're trying to benefit with your machine learning techniques. (Write user stories!) You must come up with measurements and ways to evaluate success for those users. You must be able to measure before you can optimize.

This has to do with knowledge of the domain, but also may benefit from UX expertise. Work with UX experts if you can.

### Machine Learning in Internet Security

There was a great BlackHat webcast on this topic, [Secure Because Math: Understanding Machine Learning-Based Security Products.](https://www.blackhat.com/html/webcast/02192015-secure-because-math.html). Slides are [there](https://www.blackhat.com/html/webcast/02192015-secure-because-math.html), [video recording is here](https://attendee.gotowebinar.com/recording/80449431422110210). Equally relevant to InfoSec and AppSec.

## Big Data?

Scaling data analysis is a familiar problem now, and there's no shortage of ways to address it. [Beware needless hype and companies that want to sell you flashy, proprietary solutions](http://www.john-foreman.com/blog/surviving-data-science-at-the-speed-of-hype). You can do it all with open-source tools. Even if you contract it, you consider looking for contractors who use known good stacks. No news here.

Here are some tools to reach for:

* **[Apache Spark.](https://spark.apache.org/)**
	* I mean, hell, [Spark has DataFrames and easy co-operability with pandas!](https://databricks.com/blog/2015/02/17/introducing-dataframes-in-spark-for-large-scale-data-science.html)
	* Berkeley has [a course on Scalable Machine Learning, focusing on Apache Spark.](https://www.edx.org/course/scalable-machine-learning-uc-berkeleyx-cs190-1x#.VOC70VPF_lQ)
* [NetflixOSS](http://netflix.github.io/#repo) (see "Big Data Tools").
	* [Netflix: Surus and ScorePMML](http://techblog.netflix.com/2015/01/introducing-surus-and-scorepmml.html)
	* ["big data" on the NetflixOSS blog](http://techblog.netflix.com/search/label/big%20data)

Also: [10 things statistics taught us about big data analysis](http://simplystatistics.org/2014/05/22/10-things-statistics-taught-us-about-big-data-analysis/).

## Finding Open-Source Libraries

* Bookmark **[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)**, a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) Machine Learning libraries and software.
* Bookmark **[Julia.jl](https://github.com/svaksha/Julia.jl/blob/master/AI.md#machine-learning)**, a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) libraries and software in the Julia language.
* Bookmark **[Pythonidae](https://github.com/svaksha/pythonidae/blob/master/AI.md#machine-learning)**, a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) libraries and software in the Python language.
* For Machine-Learning libraries that might not be on PyPI, GitHub, etc., there's [MLOSS (Machine Learning Open Source Software)](http://mloss.org/software/). Seems to feature many academic libraries.
* **[TensorFlow](http://tensorflow.org/)** seems like a *[really big deal.](https://news.ycombinator.com/item?id=10532957)* It has to have its own bullet point. Now, it's still not magic. But it seems incredibly useful! You can bet people will do exciting things with it in the coming months and years.

## Et cetera

[Kaggle](https://www.kaggle.com/) has really exciting [competitions](https://www.kaggle.com/competitions) and a [data science job board](https://www.kaggle.com/jobs).

Lastly, here are other guides to Machine Learning:

* [Machine Learning for Developers](http://xyclade.github.io/MachineLearning/) is another good introduction. It introduces machine learning for a developer audience using Smile, a machine learning library that can be used both in Java and Scala.
* [Materials for Learning Machine Learning](http://www.jacksimpson.co/2015/06/07/materials-for-learning-machine-learning/) by Jack Simpson.
* [How to Machine Learn](https://docs.google.com/document/d/1YN6BVdReNAYc8B0fjQ84yzDflqmeEPj7S0Xc-9_26R0/edit) by [Gideon Wulfsohn](http://gwulfs.github.io/).
* [Example Machine Learning notebook, exercise, and guide](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb) by Dr. Randal S. Olson. Mentioned in Notebooks section as well, but it has a similar goal to this guide (introduce you, and show you where to go next). Rich "Further Reading" section.
* [Your guide here].
