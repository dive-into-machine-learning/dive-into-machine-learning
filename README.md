# Dive into Machine Learning [![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Hi there! This guide is for you if:

* You know Python or [you're learning it](https://nbviewer.org/github/jakevdp/WhirlwindTourOfPython/blob/master/Index.ipynb) :snake:
* You're new to [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning)
* You care about [the ethics of ML](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines)
  * **[8 Responsible Machine Learning Principles](https://ethical.institute/principles.html)**
  * [Open Ethics Canvas](https://openethics.ai/canvas/)
* You learn by doing

If that's you, join me in getting a bit ahead of yourself, and see if you want to learn more about the field. (For alternatives, [jump to the end](https://github.com/hangtwenty/dive-into-machine-learning#more-ways-to-dive-into-machine-learning) or [check out Nam Vu's guide, Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers).)

Of course, there is no easy path to expertise. Also, _I'm not an expert!_ I just want to connect you with some great resources _from_ experts. Applications of ML are all around us. I think it's in the public interest that more of us learn more about ML.

Whatever motivates _you_ to dive into machine learning, if you know a bit of Python, these days you can get hands-on with a machine learning _"Hello World!"_ in less than an hour.

# Let's get started

## Tools you'll need

### If you prefer local installation

* [Python](https://www.python.org/). Python 3 is the best option.
* [Jupyter Notebook](https://jupyter.org/). (Formerly known as IPython Notebook.)
* Some scientific computing packages:
  * numpy
  * pandas
  * scikit-learn
  * matplotlib

You can install Python 3 and all of these packages in a few clicks with the [Anaconda Python distribution](https://www.anaconda.com/download/). Anaconda is popular in Data Science and Machine Learning communities. (Use whichever tool you want.)

### Cloud-based options

Some options you can use from your browser:

- **[Binder](https://mybinder.org/) is Jupyter Notebook's official choice to [try JupyterLab](https://jupyter.org/try)**
- [Deepnote](https://deepnote.com/) allows for real-time collaboration
- [Google Colab](https://colab.research.google.com/) provides "free" GPUs

For other options, see:

- [markusschanta/awesome-jupyter, "Hosted Notebook Solutions"](https://github.com/markusschanta/awesome-jupyter#hosted-notebook-solutions)
- [ml-tooling/best-of-jupyter, "Notebook Environments"](https://github.com/ml-tooling/best-of-jupyter)

## Let's go!

**[Learn how to use Jupyter Notebook](http://opentechschool.github.io/python-data-intro/core/notebook.html) (5-10 minutes).** (You can [learn by screencast](https://www.youtube.com/watch?v=qb7FT68tcA8) instead.)

Now, follow along with this brief exercise: **[An introduction to machine learning with scikit-learn](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)**. Do it in `ipython` or a Notebook, it'll really boost your confidence.

[![I'll wait.](https://user-images.githubusercontent.com/2420688/29441281-00eff0c4-837f-11e7-9666-d653a1cd2372.jpeg)](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)

## What just happened?

You just classified some hand-written digits using [scikit-learn](http://scikit-learn.org/stable/index.html). Neat huh?

# Dive in

## A Visual Introduction to Machine Learning

Let's learn a bit more about Machine Learning, and a couple of common ideas and concerns. Read ["A Visual Introduction to Machine Learning, Part 1"](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) by [Stephanie Yee](https://twitter.com/stephaniejyee) and [Tony Chu](https://twitter.com/tonyhschu/).

[![A Visual Introduction to Machine Learning, Part 1](https://user-images.githubusercontent.com/2420688/29441234-a2028c98-837e-11e7-88f2-1ca5a94684f6.gif)](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)

It won't take long. It's a beautiful introduction ... Try not to drool too much!

## A Few Useful Things to Know about Machine Learning

OK. Let's dive deeper.

Read **["A Few Useful Things to Know about Machine Learning"](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)** by [Prof. Pedro Domingos](https://homes.cs.washington.edu/~pedrod/). It's densely packed with valuable information, but not opaque.

Take a little time with this one. Take notes. Don't worry if you don't understand it all yet.

The whole paper is packed with value, but I want to call out two points:

- **Data alone is not enough.** This is where science meets art in machine-learning. Quoting Domingos: "... the need for knowledge in learning should not be surprising. Machine learning is not magic; it can’t get something from nothing. What it does is get more from less. Programming, like all engineering, is a lot of work: we have to build everything from scratch. Learning is more like farming, which lets nature do most of the work. Farmers combine seeds with nutrients to grow crops. Learners combine knowledge with data to grow programs."
- **More data can beat a cleverer algorithm.** Listen up, programmers. We like cool tools. Resist the temptation to reinvent the wheel, or to over-engineer solutions. Your starting point is to [Do the Simplest Thing that Could _Possibly_ Work](http://www.artima.com/intv/simplest3.html). Quoting Domingos: "Suppose you’ve constructed the best set of features you can, but the classifiers you’re getting are still not accurate enough. What can you do now? There are two main choices: design a better learning algorithm, or gather more data. [...] As a rule of thumb, a dumb algorithm with lots and lots of data beats a clever one with modest amounts of it. (After all, machine learning is all about letting data do the heavy lifting.)"

When you work on a real Machine Learning problem, you should focus your efforts on your **domain knowledge** and **data** before optimizing your choice of algorithms. Prefer to do simple things until you _have_ to increase complexity. You should not rush into neural networks because you think they're cool. To improve your model, **get more data.** Then use your knowledge of the problem to [explore and process](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning) the data. You should only optimize the choice of algorithms after you have gathered enough data, and you've processed it well.

## Jargon note

* [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)
* Another handy term: ["Data Engineering."](https://www.coursera.org/articles/what-does-a-data-engineer-do-and-how-do-i-become-one)
  * ["MLOps"](https://ml-ops.org/) overlaps with Data Eng, and there's [an introductory MLOps section later in this guide](#production-deployment-mlops).

## Just about time for a break...

<details><summary>Totally optional: some podcast episodes of note</summary>

First, download [an interview with Prof. Domingos on the _Data Skeptic_podcast](https://dataskeptic.com/blog/episodes/2018/the-master-algorithm) (2018). Prof. Domingos wrote [the paper we read earlier](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf).
You might also start reading his book, [_The Master Algorithm_ by Prof. Pedro Domingos](https://www.goodreads.com/book/show/24612233-the-master-algorithm), a clear and accessible overview of machine learning. (It's available as an audiobook too.)

Next, subscribe to more machine learning and data science podcasts! These are great, low-effort resources that you can casually learn more from. To [learn effectively](https://www.coursera.org/learn/learning-how-to-learn), listen over time, with plenty of headspace. [By the way, don't speed up technical podcasts, that can hinder your comprehension.](https://www.theringer.com/2017/8/2/16095364/inefficiency-week-podcasts-speed-comprehension-f0ea43949e42)

Subscribe to _**[Talking Machines](http://www.thetalkingmachines.com/)**_.

I suggest this listening order:

* **Download the ["Starting Simple"](http://www.thetalkingmachines.com/episodes/starting-simple-and-machine-learning-meds) episode, and listen to that soon.** It supports what we read from Domingos. [Ryan Adams](http://people.seas.harvard.edu/~rpa/) talks about starting simple, as we discussed above. Adams also stresses the importance of feature engineering. Feature engineering is an exercise of the "knowledge" Domingos writes about. In a later episode, [they share many concrete tips for feature engineering](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning).
* Then, over time, you can listen to the entire podcast series (start from the beginning).

Want to subscribe to more podcasts? Here's [a good listicle](https://towardsdatascience.com/5-data-science-ai-and-machine-learning-podcasts-to-listen-to-now-e5078b18d184) of suggestions, [and another](https://mty.ai/blog/the-best-ai-podcasts/).

</details>

OK! Take a break, come back refreshed.

----

## Play to learn

Next, play along from **one or more** of notebooks.

- [Dr. Randal Olson's Example Machine Learning notebook](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb): "let's pretend we're working for a startup that just got funded to create a smartphone app that automatically identifies species of flowers from pictures taken on the smartphone.  We've been tasked by our head of data science to create a demo machine learning model that takes four measurements from the flowers (sepal length, sepal width, petal length, and petal width) and identifies the species based on those measurements alone."
	- [Launch in Binder, no installation steps required](https://mybinder.org/v2/gh/rhiever/Data-Analysis-and-Machine-Learning-Projects/master?filepath=example-data-science-notebook%2FExample%20Machine%20Learning%20Notebook.ipynb)
- Various notebooks by topic:
    - [trekhleb/machine-learning-experiments](https://github.com/trekhleb/machine-learning-experiments) - "This is a collection of interactive machine-learning experiments. Each experiment consists of 🏋️ Jupyter/Colab notebook (to see how a model was trained) and 🎨 demo page"
    - [trekhleb/homemade-machine-learning](https://github.com/trekhleb/homemade-machine-learning)
- Notebooks in a series:
    - [ageron/handson-ml2](https://github.com/ageron/handson-ml2) - "Jupyter notebooks that walk you through the fundamentals of Machine Learning and Deep Learning in Python." Scikit-Learn, Keras, TensorFlow 2.

Find more great Jupyter Notebooks when you're ready:

* **[Jupyter's official Gallery of Interesting Jupyter Notebooks: Statistics, Machine Learning and Data Science](https://github.com/jupyter/jupyter/wiki)** ([permalink](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks/ae03c01ed25024aa06a4479ea600895d59b38bc4))

----

# Immerse yourself

Pick one of the courses below and start on your way.

## [Recommended course: Prof. Andrew Ng's _Machine Learning_ on Coursera](https://www.coursera.org/learn/machine-learning)

**[Prof. Andrew Ng's](https://hai.stanford.edu/people/andrew-ng) [_Machine Learning_](https://www.coursera.org/learn/machine-learning) is a popular and esteemed free online course. I've seen it [recommended](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Cory-Hicks-1) [often.](https://www.coursetalk.com/providers/coursera/courses/machine-learning?page=1&sort=-content_rating#reviews) [And](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Xavier-Amatriain) [emphatically.](https://www.forbes.com/sites/anthonykosner/2013/12/29/why-is-machine-learning-cs-229-the-most-popular-course-at-stanford/)**

You might like to have a pet project to play with, on the side. When you are ready for that, you could explore one of these [Awesome Public Datasets](https://github.com/caesar0301/awesome-public-datasets). If you're like me, you might also have fun with [`arxiv-public-datasets`, "scripts to grab public datasets from resources related to arXiv"](https://github.com/mattbierbaum/arxiv-public-datasets) ([arXiv](https://arxiv.org/abs/1905.00075)).

Also, it's recommended to grab a textbook to use as an in-depth reference. The two I saw recommended most often were _[Understanding Machine Learning](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/copy.html)_ and _[Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)_. [You only need to use one of the two options as your main reference; here's some context/comparison to help you pick which one is right for you.](https://github.com/hangtwenty/dive-into-machine-learning/issues/29) You can download each book free as PDFs at those links - so grab them!

### Tips for this course

* [Study tips for Prof. Andrew Ng's course, by Ray Li](https://rayli.net/blog/data/coursera-machine-learning-review/)
* If you're wondering, _Is it still a relevant course?_ or trying to figure out if it fits for you personally, check out these reviews:
    * [Review: Andrew Ng's Machine Learning Course](https://towardsdatascience.com/review-andrew-ngs-machine-learning-course-b905aafdb7d9)
    * [The user reviews on Coursera](https://www.coursera.org/learn/machine-learning/reviews) or [here](https://www.coursetalk.com/providers/coursera/courses/machine-learning?page=1&sort=-content_rating#reviews)

### Tips for studying on a busy schedule

It's hard to make time available every week. So, you can try to study more _effectively_ within the time you have available. Here are some ways to do that:

* ["Learning How to Learn" by Barbara Oakley](https://www.coursera.org/learn/learning-how-to-learn/) by Barbara Oakley, a free video course on Coursera.
* Prefer book/audiobook? These are great options:
  * [Barbara Oakley's book _A Mind for Numbers: How to Excel at Math and Science_](https://barbaraoakley.com/books/a-mind-for-numbers) ([reviews](https://www.goodreads.com/book/show/18693655-a-mind-for-numbers)) — "We all have what it takes to excel in areas that don't seem to come naturally to us at first"
  * [_Make It Stick: the Science of Successful Learning_](https://www.retrievalpractice.org/make-it-stick) ([reviews](https://www.goodreads.com/book/show/18770267-make-it-stick))

### Take my tips with a [grain of salt](https://english.stackexchange.com/questions/21912/origin-of-take-this-question-with-a-grain-of-salt)

I work as a software developer, and I am not a machine learning expert. Ultimately I decided not to pursue specializing in ML, and instead it's a side interest. I am glad I've learned what I have.

## Other courses

<details>
<summary>Here are some other free online courses I've seen recommended. (Machine Learning, Data Science, and related topics.)</summary>

* **Data science courses as Jupyter Notebooks:**
  * [Practical Data Science](http://radimrehurek.com/data_science_python/)
  * [Python Data Science Handbook, as Jupyter Notebooks](https://jakevdp.github.io/PythonDataScienceHandbook/)
* [Prof. Pedro Domingos's introductory video series](https://www.youtube.com/playlist?list=PLTPQEx-31JXgtDaC6-3HxWcp7fq4N8YGr). [Prof. Pedro Domingos](https://homes.cs.washington.edu/~pedrod/) wrote the paper ["A Few Useful Things to Know About Machine Learning"](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf), recommended earlier in this guide.
* [🆕 [2021]](https://dev.to/azure/free-data-science-for-beginners-curriculum-on-github-1hme) [`microsoft/Data-Science-For-Beginners`](https://github.com/microsoft/Data-Science-For-Beginners) — "Azure Cloud Advocates at Microsoft are pleased to offer a 10-week, 20-lesson curriculum all about Data Science. Each lesson includes pre-lesson and post-lesson quizzes, written instructions to complete the lesson, a solution, and an assignment. Our project-based pedagogy allows you to learn while building, a proven way for new skills to 'stick'."
* Coursera's [Data Science Specialization](https://www.coursera.org/specializations/jhu-data-science)
* [Stanford CS229: Machine Learning](https://github.com/afshinea/stanford-cs-229-machine-learning)
* [Harvard CS109: Data Science](https://cs109.github.io/2015/)
* [Advanced Statistical Computing (Vanderbilt BIOS8366)](http://stronginference.com/Bios8366/lectures.html). Interactive.
* Kevin Markham's video series, [Intro to Machine Learning with scikit-learn](http://blog.kaggle.com/2015/04/08/new-video-series-introduction-to-machine-learning-with-scikit-learn/), starts with what we've already covered, then continues on at a comfortable place.
* [UC Berkeley's Data 8: The Foundations of Data Science](http://data8.org/) course and the textbook [Computational and Inferential Thinking](https://www.inferentialthinking.com/) teaches critical concepts in Data Science.
* Prof. Mark A. Girolami's [Machine Learning Module (GitHub Mirror).](https://github.com/josephmisiti/machine-learning-module) Good for people with a strong mathematics background.
* [An epic Quora thread: How can I become a data scientist?](https://www.quora.com/How-can-I-become-a-data-scientist?redirected_qid=59455)
* There are more alternatives linked [at the bottom of this guide](#more-ways-to-dive-into-machine-learning)

</details>

## Getting Help: Questions, Answers, Chats

Start with the support forums and chats related to the course(s) you're taking.

Check out [datascience.stackexchange.com](https://datascience.stackexchange.com/) and [stats.stackexchange.com – such as the tag, _machine-learning_.](https://stats.stackexchange.com/questions/tagged/machine-learning?sort=frequent&pageSize=15) There are some subreddits, like [/r/LearningMachineLearning](https://www.reddit.com/r/learningmachinelearning) and [/r/MachineLearning](https://www.reddit.com/r/machinelearning).

Don't forget about meetups. Also, nowadays there are many active and helpful online communities around the ML ecosystem. Look for chat invitations on project pages and so on.

## Supplement: Learning Pandas well

You'll want to get more familiar with Pandas.

* **Essential**: [Things in Pandas I Wish I'd Had Known Earlier](http://nbviewer.jupyter.org/github/rasbt/python_reference/blob/master/tutorials/things_in_pandas.ipynb) (as a Jupyter Notebook)
* **Essential**: [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
* Another helpful tutorial: [Real World Data Cleanup with Python and Pandas](https://trendct.org/2016/08/05/real-world-data-cleanup-with-python-and-pandas/)
* [Video series from Data School, about Pandas](https://www.youtube.com/playlist?list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y). "Reference guide to 30 common pandas tasks (plus 6 hours of supporting video)."
* Here are some docs I found especially helpful as I continued learning:
  * [Cookbook](http://pandas.pydata.org/pandas-docs/stable/cookbook.html)
  * [Data Structures](http://pandas.pydata.org/pandas-docs/stable/dsintro.html), esp. [DataFrame](http://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe) section
  * [Reshaping by pivoting DataFrames](https://pandas.pydata.org/pandas-docs/stable/user_guide/reshaping.html)
  * [Computational tools](http://pandas.pydata.org/pandas-docs/stable/computation.html) and [StackExchange thread: "What is covariance in plain language?"](https://stats.stackexchange.com/questions/29713/what-is-covariance-in-plain-language)
  * [Group By (split, apply, and combine DataFrames)](http://pandas.pydata.org/pandas-docs/stable/groupby.html)
  * [Visualizing your DataFrames](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html)
* Bookmarks for scaling `pandas` and alternatives
  * [`dask`](https://dask.org/): A Pandas-like interface, but for larger-than-memory data and "under the hood" parallelism.
  * [`vaex`](https://vaex.io)
    * "Out-of-Core hybrid Apache Arrow/NumPy DataFrame for Python, ML, visualize and explore big tabular data at a billion rows per second" 
    * "It calculates statistics such as mean, sum, count, standard deviation etc, on an N-dimensional grid for more than a billion (10^9) samples/rows per second. Visualization is done using histograms, density plots and 3d volume rendering, allowing interactive exploration of big data. Vaex uses memory mapping, zero memory copy policy and lazy computations for best performance (no memory wasted)."
  * See also: the MLOps section [later in this guide](#production-deployment-mlops).

## Supplement: Cheat Sheets

Some good cheat sheets I've come across. (Please [submit a Pull Request](https://github.com/hangtwenty/dive-into-machine-learning/pulls) to add other useful cheat sheets.)

* [scikit-learn algorithm cheat sheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
* [Stanford CS 229](https://github.com/afshinea/stanford-cs-229-machine-learning) [cheat sheets](https://stanford.edu/~shervine/teaching/cs-229/), available on the web and [as PDFs](https://github.com/afshinea/stanford-cs-229-machine-learning/tree/master/en)
  * [Supervised learning cheat sheet](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-supervised-learning)
  * [Unsupervised learning cheat sheet](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-unsupervised-learning)
  * [Deep learning cheatsheet](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-deep-learning) [(more)](https://stanford.edu/~shervine/teaching/cs-230/)
  * [Probabilities and statistics refresher](https://stanford.edu/~shervine/teaching/cs-229/refresher-probabilities-statistics)
  * [Linear algebra and calculus refresher](https://stanford.edu/~shervine/teaching/cs-229/refresher-algebra-calculus)
  * [Machine Learning tips and tricks cheat sheet](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-machine-learning-tips-and-tricks)

# Assorted Tips and Resources

## Risks

"Machine learning systems automatically learn programs from data." Pedro Domingos, in ["A Few Useful Things to Know about Machine Learning."](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) The programs you generate will require maintenance. Like any way of creating programs faster, you can rack up [technical debt](https://en.wikipedia.org/wiki/Technical_debt).

Here is the abstract of [Machine Learning: The High-Interest Credit Card of Technical Debt](https://research.google/pubs/pub43146/):

> Machine learning offers a fantastically powerful toolkit for building complex systems quickly. This paper argues that it is dangerous to think of these quick wins as coming for free. Using the framework of technical debt, we note that it is remarkably easy to incur massive ongoing maintenance costs at the system level when applying machine learning. The goal of this paper is highlight several machine learning specific risk factors and design patterns to be avoided or refactored where possible. These include boundary erosion, entanglement, hidden feedback loops, undeclared consumers, data dependencies, changes in the external world, and a variety of system-level anti-patterns.

If you're following this guide, you should read that paper. You can also [listen to a podcast episode interviewing one of the authors of this paper](https://softwareengineeringdaily.com/2015/11/17/machine-learning-and-technical-debt-with-d-sculley/).

* **[Awesome Production Machine Learning](https://github.com/EthicalML/awesome-production-machine-learning), "a curated list of awesome open source libraries to deploy, monitor, version and scale your machine learning."** It includes a section about [privacy-preserving ML](https://github.com/EthicalML/awesome-production-machine-learning#privacy-preserving-machine-learning), by the way!
* **["Rules of Machine Learning: Best Practices for [Reliable] ML Engineering,"](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)** by Martin Zinkevich, regarding ML engineering practices.
* [The High Cost of Maintaining Machine Learning Systems](http://www.kdnuggets.com/2015/01/high-cost-machine-learning-technical-debt.html)
* [Overfitting vs. Underfitting: A Conceptual Explanation](https://towardsdatascience.com/overfitting-vs-underfitting-a-conceptual-explanation-d94ee20ca7f9)
* [11 Clever Methods of Overfitting and How to Avoid Them](http://hunch.net/?p=22)
* ["So, you want to build an ethical algorithm?" An interactive tool to prompt discussions](https://cdt.info/ddtool/) [(source)](https://github.com/numfocus/algorithm-ethics)

That's not a comprehensive list, only a collection of starting-points to learn more.

## Skilling up

What are some ways to practice?

<details>
<summary><strong>One way:</strong> competitions and challenges</summary>

You need **practice.** [On Hacker News, user olympus commented to say you could use competitions to practice and evaluate yourself](https://news.ycombinator.com/item?id=10508565). [Kaggle](https://www.kaggle.com/competitions) and [ChaLearn](http://www.chalearn.org/) are hubs for Machine Learning competitions. (You can find more competitions [here](https://github.com/paperswithcode/releasing-research-code#results-leaderboards) or [here](https://towardsdatascience.com/12-data-science-ai-competitions-to-advance-your-skills-in-2021-32e3fcb95d8c).)

You also need **understanding.** You should review what Kaggle competition winners say about their solutions, [for example, the "No Free Hunch" blog](http://blog.kaggle.com/). These might be over your head at first but once you're starting to understand and appreciate these, you know you're getting somewhere.
	
Competitions and challenges are just one way to practice! [Machine Learning isn't just about Kaggle competitions](https://jvns.ca/blog/2014/06/19/machine-learning-isnt-kaggle-competitions).
	
</details>

<details>
<summary><strong>Another way:</strong> try doing some practice studies</summary>

Here's a complementary way to practice: **do practice studies.**

1. **Ask a question. Start exploring some data.** The ["most important thing in data science is the question"](https://github.com/DataScienceSpecialization/courses/blob/master/01_DataScientistToolbox/03_02_whatIsData/index.Rmd#the-data-is-the-second-most-important-thing) ([Dr. Jeff T. Leek](https://github.com/jtleek)). So start with a question. Then, find [real data](https://github.com/caesar0301/awesome-public-datasets). Analyze it. Then ...
2. **Communicate results.** When you think you have a novel finding, ask for review. When you're still learning, ask in informal communities (some are [linked below](#some-communities-to-know-about)).
3. **Learn from feedback.** Consider [learning in public](https://www.swyx.io/learn-in-public/), it works great for some folks. (Don't pressure yourself though! Do what works for you.) 

How can you come up with interesting questions? Here's one way. Pick a day each week to [look for public datasets](https://github.com/caesar0301/awesome-public-datasets) and write down some questions that come to mind. Also, sign up for [Data is Plural](https://tinyletter.com/data-is-plural), a newsletter of interesting datasets. When a question inspires you, try exploring it with the skills you're learning.

This advice, to do practice studies and learn from review, is based on [a conversation](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-153934120) with [Dr. Randal S. Olson](http://www.randalolson.com/). Here's more advice from Olson, [quoted with permission:](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-154135498)

> I think the best advice is to tell people to always present their methods clearly and to avoid over-interpreting their results. Part of being an expert is knowing that there's rarely a clear answer, especially when you're working with real data.

As you repeat this process, your practice studies will become more scientific, interesting, and focused. Also, [here's a video about the scientific method in data science.](https://101.datascience.community/2012/06/27/the-data-scientific-method/))

</details>

<details>
<summary>More machine learning career advice</summary>

* ["Advice on building a machine learning career and reading research papers by Prof. Andrew Ng"](https://www.kdnuggets.com/2019/09/advice-building-machine-learning-career-research-papers-andrew-ng.html)
	
</details>

#### Some communities to know about

Great places to ask for feedback informally, and while you are learning:
* [/r/LearnMachineLearning](https://www.reddit.com/r/learnmachinelearning/)
* [/r/DataIsBeautiful](https://reddit.com/r/DataIsBeautiful)
* [/r/DataScience](https://reddit.com/r/DataScience)
* [/r/MachineLearning](https://reddit.com/r/MachineLearning)
* [Cross-Validated: stats.stackexchange.com](https://stats.stackexchange.com/)

### Peer review

**[OpenReview.net](https://openreview.net/about)** "aims to promote openness in scientific communication, particularly the peer review process."

> * **Open Peer Review:** We provide a configurable platform for peer review that generalizes over many subtle gradations of openness, allowing conference organizers, journals, and other "reviewing entities" to configure the specific policy of their choice. We intend to act as a testbed for different policies, to help scientific communities experiment with open scholarship while addressing legitimate concerns regarding confidentiality, attribution, and bias.
> * **Open Publishing:** Track submissions, coordinate the efforts of editors, reviewers and authors, and host… Sharded and distributed for speed and reliability.
> * **Open Access:** Free access to papers for all, free paper submissions. No fees.

<details>
<summary><em>More about OpenReview.net</em></summary>

> * **Open Discussion:** Hosting of accepted papers, with their reviews, comments. Continued discussion forum associated with the paper post acceptance. Publication venue chairs/editors can control structure of review/comment forms, read/write access, and its timing.
> * **Open Directory:** Collection of people, with conflict-of-interest information, including institutions and relations, such as co-authors, co-PIs, co-workers, advisors/advisees, and family connections.
> * **Open Recommendations:** Models of scientific topics and expertise. Directory of people includes scientific expertise. Reviewer-paper matching for conferences with thousands of submissions, incorporating expertise, bidding, constraints, and reviewer balancing of various sorts. Paper recommendation to users.
> * **Open API:** We provide a simple REST API [...]
> * **Open Source:** We are committed to open source. Many parts of OpenReview are already in the [OpenReview organization on GitHub](https://github.com/openreview). Some further releases are pending a professional security review of the codebase.

> * [OpenReview.net](https://openreview.net/) is created by Andrew McCallum’s Information Extraction and Synthesis Laboratory in the College of Information and Computer Sciences at University of Massachusetts Amherst
>
> * [OpenReview.net](https://openreview.net/) is built over an earlier version described in the paper [Open Scholarship and Peer Review: a Time for Experimentation](https://openreview.net/forum?id=xf0zSBd2iufMg) published in the [ICML 2013 Peer Review Workshop](https://openreview.net/group?id=ICML.cc/2013/PeerReview).
>
> * OpenReview is a long-term project to advance science through improved peer review, with legal nonprofit status through Code for Science & Society. We gratefully acknowledge the support of the great diversity of [OpenReview Sponsors](https://openreview.net/sponsors)––scientific peer review is sacrosanct, and should not be owned by any one sponsor.

</details>

### Production, Deployment, [MLOps](https://ml-ops.org/)

If you are learning about MLOps but find it overwhelming, these resources might help you get your bearings:

* [MLOps Stack Template](https://valohai.com/blog/the-mlops-stack/) by Henrik Skogström
* [Lessons on ML Platforms from Netflix, DoorDash, Spotify, and more](https://towardsdatascience.com/lessons-on-ml-platforms-from-netflix-doordash-spotify-and-more-f455400115c7) by Ernest Chan in *Towards Data Science*
* [MLOps Stack Canvas](https://ml-ops.org/content/mlops-stack-canvas) at [ml-ops.org](https://ml-ops.org/)

Recommended awesomelists to save/star/watch:

* **[EthicalML/awesome-artificial-intelligence-guidelines](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines)**
* **[EthicalML/awesome-production-machine-learning](https://github.com/EthicalML/awesome-production-machine-learning#privacy-preserving-machine-learning)**
* **[visenger/awesome-ml-model-governance](https://github.com/visenger/Awesome-ML-Model-Governance)**
* **[visenger/awesome-MLOps](https://github.com/visenger/awesome-mlops)**

----

## Deep Learning

In early editions of this guide, there was no specific "Deep Learning" section. There are experts in the field who warn against jumping too far ahead.

In any case, when you're ready to dive into Deep Learning, here are some helpful resources.

* **[Dive into Deep Learning](https://d2l.ai/) - An interactive book about deep learning**
  * "Interactive deep learning book with code, math, and discussions"
  * "Implemented with NumPy/MXNet, PyTorch, and TensorFlow"
  * "Adopted at 200 universities from 50 countries"
* **[labmlai/annotated_deep_learning_paper_implementations](https://github.com/labmlai/annotated_deep_learning_paper_implementations)** - "Deep learning papers implemented, with side-by-side notes" - "We are actively maintaining this repo and adding new implementations almost weekly."
* **["Have Fun With [Deep] Learning" by David Humphrey.](https://github.com/humphd/have-fun-with-machine-learning)** This is an excellent way to "get ahead of yourself" and hack-first. Then you will feel excited to move onto...
* **[Prof. Andrew Ng's](https://scholar.google.com/citations?user=mG4imMEAAAAJ&hl=en) [courses on Deep Learning](https://www.coursera.org/specializations/deep-learning)!** There five courses, as part of the [Deep Learning Specialization on Coursera](https://www.coursera.org/specializations/deep-learning). These courses are part of his new venture, [deeplearning.ai](https://www.deeplearning.ai)
* **[_Deep Learning_](https://www.deeplearningbook.org/), a free book published MIT Press.** By Ian Goodfellow, Yoshua Bengio and Aaron Courville
* [Quora: "What are the best ways to pick up Deep Learning skills as an engineer?"](https://www.quora.com/What-are-the-best-ways-to-pick-up-Deep-Learning-skills-as-an-engineer) — answered by Greg Brockman (Co-Founder & CTO at OpenAI, previously CTO at Stripe)
* [Distill.pub](https://distill.pub/about/) publishes explorable explanations that are really great.
  * ["Feature Visualization: How neural networks build up their understanding of images"](https://distill.pub/2017/feature-visualization/)
* [`explosion/thinc`](https://github.com/explosion/thinc), "A refreshing functional take on deep learning, compatible with your favorite libraries"
* [Creative Applications of Deep Learning with Tensorflow](https://github.com/pkmital/CADL)

### Easier sharing of deep learning models and demos

* **[Replicate](https://replicate.com) "makes it easy to share a running machine learning model"**
  * Easily try out deep learning models from your browser
  * The demos link to papers/code on GitHub, if you want to dig in and see how something works
  * The models run in containers built by [`cog`](https://github.com/replicate/cog), "containers for machine learning." It's an open-source tool for putting models into reproducible Docker containers.

----

## Collaborate with Domain Experts

Machine Learning can be powerful, but it is not magic.

Whenever you apply Machine Learning to solve a problem, you are going to be working in some specific problem domain. To get good results, you or your team will need "substantive expertise" (to re-use a phrase from earlier), which is related to "domain knowledge." Learn what you can, for yourself... But you should also **collaborate with experts.** You'll have better results if you collaborate with [subject-matter experts and domain experts](https://en.wikipedia.org/wiki/Subject-matter_expert#Domain_expert_(software)).

### Machine Learning and User Experience (UX)

I couldn't say it better:

> **Machine learning won’t figure out what problems to solve.** If you aren’t aligned with a human need, you’re just going to build a very powerful system to address a very small—or perhaps nonexistent—problem.

That quote is from ["The UX of AI" by Josh Lovejoy](https://design.google/library/ux-ai/). In other words, **[You Are Not The User](https://www.nngroup.com/articles/false-consensus/).** Suggested reading: [Martin Zinkevich's "Rules of ML Engineering", Rule #23: "You are not a typical end user"](https://developers.google.com/machine-learning/guides/rules-of-ml/#human_analysis_of_the_system)

---

## Big data

<details>
<summary>Here are some useful links regarding Big Data and ML.
</summary>

* [10 things statistics taught us about big data analysis](https://www.kdnuggets.com/2015/02/10-things-statistics-big-data-analysis.html) (and some more food for thought: ["What Statisticians think about Data Scientists"](https://www.datasciencecentral.com/profiles/blogs/what-statisticians-think-about-data-scientists))
* ["Talking Machines" #12](https://www.thetalkingmachines.com/episodes/economic-impact-machine-learning-and-using-kernel-trick-big-data): Interviews Prof. Andrew Ng (from [his course, which has its own module on big data](https://www.coursera.org/learn/machine-learning)); this episode covers some problems relevant to _high-dimensional_ data
* ["Talking Machines" #15: "Really Really Big Data and Machine Learning in Business"](https://www.thetalkingmachines.com/episodes/really-really-big-data-and-machine-learning-business)
* [0xnr/awesome-bigdata](https://github.com/0xnr/awesome-bigdata)

See also: [the MLOps section!](#production-deployment-mlops)

</details>

If you are working with data-intensive applications at all, I'll recommend this book:

* **[_Designing Data-Intensive Applications_](http://dataintensive.net)** by Martin Kleppman. (You can start reading it online, free, via Safari Books.) It's not specific to Machine Learning, but you can bridge that gap yourself.

## More Data Science materials

Here are some additional Data Science resources:

* **[Python Data Science Handbook, as Jupyter Notebooks](https://jakevdp.github.io/PythonDataScienceHandbook/)**
* Accessible data science book, no coding experience required: [_Data Smart_ by John Foreman](https://www.goodreads.com/book/show/17682206-data-smart)
* [Data Science Workflow: Overview and Challenges](https://cacm.acm.org/blogs/blog-cacm/169199-data-science-workflow-overview-and-challenges/fulltext) (read the article *and also* the comment by Joseph McCarthy)

### Aside: Bayesian Statistics and Machine Learning

From [the "Bayesian Machine Learning" overview on Metacademy](https://metacademy.org/roadmaps/rgrosse/bayesian_machine_learning):

> ... Bayesian ideas have had a big impact in machine learning in the past 20 years or so because of the flexibility they provide in building structured models of real world phenomena. Algorithmic advances and increasing computational resources have made it possible to fit rich, highly structured models which were previously considered intractable.

<details>
<summary>Here are some awesome resources for learning Bayesian methods.</summary>

* The **free book** _[Probabilistic Programming and Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)_. Made with a "computation/understanding-first, mathematics-second point of view." Uses [PyMC](https://github.com/pymc-devs/pymc). It's available in print too!
* Like learning by playing? Me too. Try [19 Questions](https://github.com/fulldecent/19-questions), "a machine learning game which asks you questions and guesses an object you are thinking about," and **explains which Bayesian statistics techniques it's using!**
* [_Time Series Forecasting with Bayesian Modeling by Michael Grogan_](https://www.manning.com/liveprojectseries/time-series-forecasting-with-bayesian-modeling), a 5-project series - paid but the first project is free.
* [Bayesian Modelling in Python](https://github.com/markdregan/Bayesian-Modelling-in-Python). Uses [PyMC](https://github.com/pymc-devs/pymc) as well.

</details>

[(↑ Back to top)](#dive-into-machine-learning--)

----

## Finding Open-Source Libraries

* Bookmark **[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)**, a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) Machine Learning libraries and software.
* Bookmark [Pythonidae](https://github.com/svaksha/pythonidae/blob/master/AI.md#machine-learning), a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) libraries and software in the Python language - with a section on Machine Learning.
* For Machine-Learning libraries that might not be on PyPI, GitHub, etc., there's [MLOSS (Machine Learning Open Source Software)](http://mloss.org/software/). Seems to feature many academic libraries.
* Julia: [Julia.jl](https://github.com/svaksha/Julia.jl/blob/master/AI.md#machine-learning), a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) libraries and software in the Julia language - with a section on Machine Learning.

### Natural Language Processing (NLP)

This is just a small 

* [spaCy: Industrial-strength NLP](https://github.com/explosion/spaCy) - "spaCy is a library for advanced Natural Language Processing in Python and Cython."
  * [Advanced NLP with spaCy: A free online course](https://github.com/ines/spacy-course)
  * [spaCy projects](https://spacy.io/usage/projects) - "End-to-end NLP workflows from prototype to production"
* There are lots of NLP-related links in [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)
* [keon/awesome-nlp](https://github.com/keon/awesome-nlp)

### Non-sequitur

These next two links are not related to ML. But since you're here, I have a hunch you might find them interesting too:

* Maggie Appleton's ["A Brief History & Ethos of the Digital Garden"](https://maggieappleton.com/garden-history)
* Shawn Wang's ["Digital Garden Terms of Service"](https://www.swyx.io/digital-garden-tos/)

----

## More ways to "Dive into Machine Learning"

Here are some other guides to learning Machine Learning. They can be alternatives or supplements to this guide.

* [Example Machine Learning notebook, exercise, and guide](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb) by Dr. Randal S. Olson. Mentioned in Notebooks section as well, but it has a similar goal to this guide (introduce you, and show you where to go next). Rich "Further Reading" section.
* Courses by cloud vendors (might be specific to their tools/platforms)
  * [microsoft/ML-For-Beginners](https://github.com/microsoft/ML-For-Beginners), [microsoft/Data-Science-For-Beginners](https://github.com/microsoft/Data-Science-For-Beginners)
  * [Machine Learning Crash Course from Google](https://developers.google.com/machine-learning/crash-course/) with TensorFlow APIs.
  * [Amazon AWS](https://aws.amazon.com/training/learn-about/machine-learning/) Amazon have open up their internal training to the public and also offer certification.
* [Machine Learning for Developers](http://xyclade.github.io/MachineLearning/) is good for people who are more familiar with Java or Scala than Python.
* [ageron/handson-ml2](https://github.com/ageron/handson-ml2) aka [_Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow_ by Aurélien Geron](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
* [rasbt/python-machine-learning-book-3rd-edition](https://github.com/rasbt/python-machine-learning-book-3rd-edition) aka [_Python Machine Learning: Machine Learning and Deep Learning with Python, scikit-learn, and TensorFlow 2_ by Sebastian Raschka and Vahid Mirjalili](https://www.goodreads.com/book/show/25545994-python-machine-learning)
* [Machine Learning for Software Engineers, by Nam Vu](https://github.com/ZuzooVn/machine-learning-for-software-engineers). In their words, it's a "top-down and results-first approach designed for software engineers." Definitely bookmark and use it, as well - it can answer lots of questions and connect you with great resources.

[(↑ Back to top)](#dive-into-machine-learning--)
