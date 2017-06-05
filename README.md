# MFE230P: Data Science for Finance
###### MASTERS OF FINANCIAL ENGINEERING \ UC BERKELEY

_Data Science for Finance_ is a survey course on the machine learning models and mathematical optimization methods pertaining to financial engineering and financial data. We spend roughly 2/3 of the course discussing machine learning and the remaining 1/3 discussing portfolio optimization. Specifically, we will cover convexity, the fundamentals of mathematical optimization, and discuss convex programming using open source software [CVX](http://cvxpy.org); unsupervised methods for clustering and dimension-reduction as well as kernels; supervised methods including regression, classification, and their kernel variants; a brief overview of deep learning; portfolio optimization with transaction costs and induced sparsity; and robust optimization. Unlike a traditional machine learning course, however, we will give special attention to financial applications—such as index-tracking and sector segmentation—and the challenges faced when working with financial data—such as leptokurtic or asymmetric market returns and non-stationary environments.

The course will consist of semi-weekly lectures, a final examination that constitutes 40% of grade, and four homwework assignments—each constituting 15% of grade—that involve a written component and a programming component to be completed in [Python](https://www.python.org). Accordingly, we will use [Jupyter Notebook](http://jupyter.org) for assignment submissions as they support [LaTeX](https://www.latex-project.org) syntax for inline mathematical expressions (via [MathJax](https://www.mathjax.org)) and programming in Python, including [inline display of figures](http://jupyter-notebook.readthedocs.io/en/latest/notebook.html#plotting).

## Pre-requisites

Required:

1. Knowledge of linear algebra at the level of [Math 54](https://math.berkeley.edu/courses/choosing/lowerdivcourses/math54) (i.e. vectors, matrices, eigenvalues/eigenvectors, orthogonality)
2. Basic knowledge of multivariate statistics (i.e. covariance matrices, multivariate Gaussian distribution, etc.) and multivariate calculus (i.e. [gradient vector](https://en.wikipedia.org/wiki/Gradient#Gradient_as_a_derivative), [Hessian matrix](https://en.wikipedia.org/wiki/Hessian_matrix), and [Taylor approximation](https://en.wikipedia.org/wiki/Taylor_series))
3. Practical knowledge of finance and economics; measures of risk, random walks, utility maximization, etc.
4. Basic programming experience with a mathematical or statistical language such as Matlab, R, or Python
5. Some experience working with time series data (autocorrelation, stationarity, ARIMA, etc.)

Optional, but helpful:

1. Experience applying computational linear algebra at the level of [EE127](https://people.eecs.berkeley.edu/~elghaoui/Teaching/EE127/) or [Math 221](https://people.eecs.berkeley.edu/~demmel/ma221_Spr16/)
2. Familiarity with numerical analysis at the level of [Math 128A](http://persson.berkeley.edu/128A/)
3. Familiarity with Probability and Mathematical Statistics at the level of [Stat 135](http://www.stat.berkeley.edu/~rice/Stat135/) or [Rice's textbook](https://www.amazon.com/Mathematical-Statistics-Analysis-Available-Enhanced/dp/0534399428)
4. Familiarity with convex programming at the level of [Boyd and Vandenberghe's textbook](http://stanford.edu/~boyd/cvxbook/)

## Course Schedule & Outline

The course runs from 5 June 2017 to 26 July 2017 with the final examination scheduled for 2 August 2017 from 1-4PM. [Professor El Ghaoui](http://www.eecs.berkeley.edu/~elghaoui/) will lecture 1-3PM on Mondays and Wednesdays in F320 with the exception of 12 June and 14 June, which will be held in C135 and Andersen, respectively. Professor office hours will be held 3-4PM directly following Wednesday lecture. [Mustafa](https://mustafaseisa.com) will lead discussion Monday 3-4PM in F320, with the exception of 12 June, which will be held in the [Innovation Lab](https://haas.berkeley.edu/haas/innovation.html). Assistant office hours will be held Friday 4-5PM in S276. A detailed lecture outline follows directly:

Week | 	Lecture No. | Date | Lecture Title | HW given |	HW due
:---: | :---: | :---: | --- | ---: |	---:
1 | 01 | 06/05/17 | Optimization models and convexity | |	
1 |	02 | 06/07/17 | k-means and [clusterpath](https://www.di.ens.fr/~fbach/419_icmlpaper.pdf) | 1 |
2 |	03 | 06/12/17 | Covariance estimation and PCA | |
2 |	04 | 06/14/17 | [Generalized low rank models](https://arxiv.org/abs/1410.0342) and [Matrix Completion](https://statweb.stanford.edu/~candes/papers/MatrixCompletion.pdf) | |
3 |	05 | 06/19/17 | LS/LAD regression and penalization | |
3 |	06 | 06/21/17 | SVM and classification | 2 | 1
4 |	07 | 06/26/17 | Kernel Methods | |
4 |	08 | 06/28/17 | Feature engineering and encoding | |
5 |	09 | 07/03/17 | Deep learning and recent developments | |
5 |10 | 07/05/17 | Time Series Decomposition and Harmonic Regression | 3 | 2
6 |	11 | 07/10/17 |	Portfolio optimization: Markowitz, Sharpe, and beyond | |
6 | 12 | 07/12/17 |	Constraints and [Sparsity on the Simplex](https://people.eecs.berkeley.edu/~elghaoui/Pubs/pilanciNips12.pdf) | |
7 |	13 | 07/17/17 | Robust Optimization I | |
7 | 14 | 07/19/17 | Robust Optimization II | 4	| 3
8 | 15 | 07/24/17 | (Optional) Review I | |
8 |  16 | 07/26/17 | (Optional) Review II |  | 
9 | — | 08/02/17 | Final | | 4

## Reference Texts

While a textbook is not required for this course, we provide the following collection of references to supplement the lectures.

* [**Optimization Models.**](http://www.cambridge.org/us/academic/subjects/engineering/control-systems-and-optimization/optimization-models?format=HB&isbn=9781107050877#M70W2lvoAjMyDmly.97) Calafiore and El Ghaoui (2014).
* [**Elements of Statistical Learning.**](https://statweb.stanford.edu/~tibs/ElemStatLearn/) Hastie, Tibshirani, and Friedman (2009).
* [**Optimization Methods in Finance.**](https://www.researchgate.net/publication/227390397_Optimization_Methods_in_Finance) Cornuejols and Tütüncü (2007).
* [**Convex Optimization.**](http://stanford.edu/~boyd/cvxbook/) Boyd and Vandenberghe (2004).
* [**Deep Learning.**](http://www.deeplearningbook.org) Goodfellow, Bengio, and Courville (2016).

## Grading Policy

**Homework** is to be submitted electronically through [bCourses](https://bcourses.berkeley.edu) and is due exactly two weeks from the day it is assigned. You may submit homework as late as 11:59PM on the day it is due. If you submit homework past the deadline, your score will be deducted by 5% for each hour of tardiness in excess of the deadline. For example, if you submit your homework anywhere between 12:00AM and 12:59AM, you will be deducted 5%; if you submit between 1:00AM and 1:59AM, you will be deducted 10%; and so forth. Students are encouraged to collaborate in groups of (no more than) four to complete the homework, however each student must submit his or her own unique solution and state their collaborators.

There will be one **in-class exam** at the end of the course on 2 August 2017 from 1-4PM. The exam will be open note, but no calculators, cell phones, electronic dictionaries, laptops, tablets, or other electronic devices are allowed. If you are apprehended disobeying the aforementioned policies or collaborating with other students during the exam period, your exam will be destroyed and you will recieve no credit. If you are a student registered with the [Disabled Student Program](http://dsp.berkeley.edu) (DSP) and you require special arrangements during exams, you must provide the appropriate documentation and make arrangements at least 10 days prior to the exam, detailing the special arrangements you require.

<span style="color:red">**MAKEUP EXAMINATION WILL NOT BE OFFERED UNDER ANY CIRCUMSTANCES WHATSOEVER.**</span>

The grades for homeworks and exams will be changed only if there is a clear error on the part of the grader, such as adding up marks incorrectly. Grading errors must be brought to Mustafa's attention _immediately_ after the homework/exam is returned.

## Contact Information

Title | Name | Email Address
:---: | :---: | :---:
Professor | [Laurent El Ghaoui](http://www.eecs.berkeley.edu/~elghaoui/) | `elghaoui@berkeley.edu`
Assistant | [Mustafa S Eisa](http://mustafaseisa.com/) | `m.eisa@berkeley.edu`
MFE Program | — | `mfe@haas.berkeley.edu`