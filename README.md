# MFE230P: Data Science for Finance
**MASTERS OF FINANCIAL ENGINEERING \ UC BERKELEY**

MFE230P is a survey course covering the machine learning models and mathematical optimization methods pertaining to financial engineering and financial data. We will cover convexity, the fundamentals of mathematical optimization, and discuss convex programming using open source software [CVX](http://cvxr.com); unsupervised methods for clustering and dimension-reduction; supervised methods including regression, classification, and kernels; a brief overview of deep learning; portfolio optimization with transaction costs; and robust optimization.

The course will consist of semi-weekly lectures, a final examination that constitutes 40% of grade, and four homwework assignments—each constituting 15% of grade—that involve a written component and a programming component to be completed in [Python](https://www.python.org). Accordingly, we will use [Jupyter Notebook](http://jupyter.org) for assignment submissions as they support [LaTeX](https://www.latex-project.org) syntax for inline mathematical expressions (via [MathJax](https://www.mathjax.org)) and programming in Python, including [inline display of figures](http://jupyter-notebook.readthedocs.io/en/latest/notebook.html#plotting).

## Pre-requisites

Required:

1. Knowledge of linear algebra at the level of [Math 54](https://math.berkeley.edu/courses/choosing/lowerdivcourses/math54) (i.e. vectors, matrices, eigenvalues/eigenvectors, orthogonality)
2. Basic knowledge of multivariate statistics (i.e. covariance matrices, multivariate Gaussian distribution, etc.)
3. Basic familiarity with multivariable calculus. Namely, the [gradient vector](https://en.wikipedia.org/wiki/Gradient#Gradient_as_a_derivative), [Hessian matrix](https://en.wikipedia.org/wiki/Hessian_matrix), and [Taylor approximation](https://en.wikipedia.org/wiki/Taylor_series)
4. Basic programming experience with a mathematical or statistical language such as Matlab, R, or Python

Optional, but helpful:

1. Experience applying computational linear algebra at the level of [Math 221](https://people.eecs.berkeley.edu/~demmel/ma221_Spr16/)
2. Familiarity with numerical analysis at the level of [Math 128A](http://persson.berkeley.edu/128A/)
3. Familiarity with Probability and Mathematical Statistics at the level of [Stat 135](www.stat.berkeley.edu/~rice/Stat135/) or [Rice's textbook](https://www.amazon.com/Mathematical-Statistics-Analysis-Available-Enhanced/dp/0534399428)
4. Familiarity with convex programming at the level of [EE127](https://people.eecs.berkeley.edu/~elghaoui/Teaching/EE127/) or, better yet, [Boyd and Vandenberghe's textbook](http://stanford.edu/~boyd/cvxbook/)

## Course Schedule & Outline

The course runs from 5 June 2017 to 26 July 2017. [Professor El Ghaoui](http://www.eecs.berkeley.edu/~elghaoui/) will lecture 1-3PM on Mondays and Wednesdays in F320 and hold office hours on Wednesdays 3-4PM. [Mustafa](https://mustafaseisa.com) (teaching assistant) will lead discussion Monday 3-4PM and hold office hours Friday 8-9AM. A detailed course outline follows directly:

Week | 	Lecture No. | Date | Lecture Title | HW given |	HW due
:---: | :---: | ---: | --- | ---: |	---:
1 | 01 | 06/05/17 | Optimization models and convexity | |	
1 |	02 | 06/07/17 | k-means and clusterpath | 1 |
2 |	03 | 06/12/17 | Covariance estimation and PCA | |
2 |	04 | 06/14/17 | Generalized low rank models | |
3 |	05 | 06/19/17 | Feature engineering; CVX and numerical optimization
3 |	06 | 06/21/17 | LS/LAD regression and penalization | 2 | 1
4 |	07 | 06/26/17 | SVM and classification | |
4 |	08 | 06/28/17 | Kernels | |
5 |	09 | 07/03/17 | Deep learning and recent developments | |
5 | 10 | 07/05/17 | Compressive Sensing and Harmonic Regression | 3 | 2
6 |	11 | 07/10/17 |	Portfolio optimization and Markowitz | |	
6 | 12 | 07/12/17 |	Minimum variance, sharpe, and beyond | |	
7 |	13 | 07/17/17 | Incorporating transaction costs | |
7 | 14 | 07/19/17 | Robust Optimization	| 4	| 3
8 | 15 | 07/24/17 | Review | |
8 |  - | 07/26/17 | Final |  | 4

## Grading Policy

**Homework** is to be submitted electronically through [bCourses](https://bcourses.berkeley.edu) and is due exactly two weeks from the day it is assigned. You may submit homework as late as `11:59PM` on the day it is due. If you submit homework past the deadline, your score will be deducted by 5% for each hour of tardiness in excess of the deadline. For example, if you submit your homework anywhere between 12:00AM and 12:59AM, you will be deducted 5%; if you submit between 1:00AM and 1:59AM, you will be deducted 10%; and so forth. Students are encouraged to collaborate in groups of 3 or 4 to complete the homework, however each student must submit his or her own unique solution and name their collaborators.

There will be one **in-class exam** at the end of the course on 26 July 2017 from 1-3PM. The exam will be open note, but no calculators, cell phones, electronic dictionaries, laptops, tablets, or other electronic devices are allowed. If you are apprehended disobeying the aforementioned policies or collaborating with other students during the exam period, your exam will be destroyed and you will recieve no credit. If you are a student registered with the [Disabled Student Program](http://dsp.berkeley.edu) (DSP) and you require special arrangements during exams, you must provide the appropriate documentation and make arrangements at least 10 days prior to the exam, explaining the special arrangements you require.

<span style="color:red">**MAKEUP EXAMINATION WILL NOT BE OFFERED UNDER ANY CIRCUMSTANCES WHATSOEVER.**</span>

The grades for exams or quizzes will be changed only if there is a clear error on the part of the grader, such as adding up marks incorrectly. Grading errors must be brought to the attention of the teaching assistant _immediately_ after the homework/exam is returned.

## Contact Information

Title | Name | email address
:---: | :---: | :---:
Professor | [Laurent El Ghaoui](http://www.eecs.berkeley.edu/~elghaoui/) | `elghaoui` atsign `berkeley` dot `edu`
Teaching Assistant | [Mustafa S Eisa](http://mustafaseisa.com/) | `m` dot `eisa` atsign `berkeley` dot `edu`
MFE Program | — | `mfe` at `haas` dot `berkeley` dot `edu`