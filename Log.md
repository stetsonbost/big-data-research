# Research Log

This is a log of my progress for my big data research with Professor Weiqing Gu at Harvey Mudd College during Summer 2017. The format of these log entries may change over time as I settle on a comforable style for them.

## Tuesday, May 16
For this research, it is essential that I (re)learn core concepts of big data. As such, I am spending the first part of the research studying these. 

Today I set up my account on the Pittsburgh Supercomputing Center (PSC) server for the XSEDE big data workshop that is taking place on Thursday and Friday. I also looked at the main slides they will be using on Thursday ([Intro to Big Data](https://www.psc.edu/images/xsedetraining/BigDataFebruary2017/Intro_To_Big_Data.pdf), [Hadoop](https://www.psc.edu/images/xsedetraining/BigDataFebruary2017/BigData_Hadoop_110116.pdf), and [Spark](https://www.psc.edu/images/xsedetraining/BigDataFebruary2017/BigData_Hadoop_110116.pdf)). While these gave me a good idea of what would be covered in the workshop, it's obvious that it will be a very hands-on workshop that will teach me how to use popular computational tools like Hadoop and Spark for big data analytics.

In addition to preparing for the workshop, I also started studying material from Andrew Ng's course [CS 229: Machine Learning](http://cs229.stanford.edu/materials.html), taught at Stanford. I am beginning with his [first set of notes](http://cs229.stanford.edu/notes/cs229-notes1.pdf). It starts with an introduction to supervised learning, followed by a large section on linear regression. One thing he does is introduce the least-squares cost function, although I think several other cost functions could also be effective for linear regression. Ng talks about the least means squares (LMS) (aka Widrow-Hoff) learning rule, which makes updates to the weights of feature based on the current weight, error term, and the learning rate. An algorithm that does this is *batch gradient descent*, which works best if there is only one global optimum and no local optima. Another algorithm *stochastic (incremental) gradient descent*, which makes more frequent updates to the weights and can get to an optimum faster than batch gradient descent, making it better for larger training sets.
The next part is more about how to deal with matrices and vectors, including least squares with matrices. This leads up to the normal equation, which will be very important.

Tomorrow I'll continue through these notes. The next section is on probabilistic approaches, which should line up well with where Prof. Gu will be in her big data lecture tomorrow evening.


