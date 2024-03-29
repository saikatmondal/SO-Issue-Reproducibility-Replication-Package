# The Reproducibility of Programming-Related Issues in Stack Overflow Questions

**Abstract:** Software developers often look for solutions to their code-level problems on the Stack Overflow Q&A website. Hence, they frequently submit questions containing sample code segments and issue descriptions. Unfortunately, it is not always possible to reproduce their reported issues from the code segments provided. This phenomenon might prevent questions from receiving prompt and appropriate solutions. We conducted an exploratory study on the reproducibility of the issues discussed in 800 Stack Overflow questions (400 Java + 400 Python). We parse, compile, execute, and carefully examine the code segments from these questions, and attempt to reproduce their reported programming issues. We spent a total of 300 person-hours, and the outcomes of our study are three-fold. First, we found that we can reproduce the issues reported by developers for approximately 68% of Java and 71% of Python code segments, whereas we were unable to reproduce the issues for approximately 22% of Java code segments and 19% of Python code segments. Of the issues that were reproducible, approximately 67% of the Java code segments and 20% of the Python code segments required minor or major modifications to reproduce the issues. Second, we also carefully investigated why programming issues could not be reproduced and provide evidence-based guidelines to write effective code examples for Stack Overflow questions. Third, we investigated the correlation between the issue reproducibility status of questions and the corresponding answer meta-data, such as the presence of an accepted answer. According to our analysis, a question that is reproducible has at least a two times higher chance of receiving an accepted answer than a question that is irreproducible.

## Accepted Paper

    Saikat Mondal, M. Masudur Rahman and Chanchal K. Roy "Can Issues Reported at Stack Overflow Questions be Reproduced?
    An Exploratory Study", In Proceeding of The 16th IEEE International Conference on Mining Software Repositories (MSR 2019),
    pp. 479--489, Montreal, QC, Canada, May 2019.

**Download this paper:** [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8816784)

## Materials Included

### Manually Analyzed Dataset

***EMSE-Dataset*** 

* `Java.csv` & `Python.csv` contain manually investigated 800 questions (400 Java and 400 Python) of Stack Overflow with their reproducibility status (`reproducible without modification`, `reproducible with minor modification`, `reproducible with major modification`, `irreproducible`, `inaccurate claim` and `ill-defined issue`).

* `JavaQuestionsWithAllFields.csv` & `PythonQuestionsWithAllFields.csv` contain all the attributes of our manually analyzed questions. 

* `Java-Reproducibility-Challenges.csv` & `Python-Reproducibility-Challenges.csv` contain the challenges that prevent the reproducibility of issues reported in the questions.

* `Java-Modifications.csv` & `Python-Modifications.csv` enlisted the editing actions of the code segments that were required to reproduce the issues.

***MSR2019-Dataset***

* `Java.csv` contains manually investigated 400 Java questions of Stack Overflow with their reproducibility status (`reproducible without modification`, `reproducible with minor modification`, `reproducible with major modification`, `irreproducible`, `inaccurate claim` and `ill-defined issue`), published in MSR 2019.


