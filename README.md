
# Replication package

This is a replication package of the paper titled "A Longitudinal Exploratory Study on Code Smells in Server Side Web Applications"

In this package you will find:

1. For every studied project, we provide the associated datasets including the LOC and code churn values for all smelly and non smelly files.

2. We provide in the folder ``Script``, the scripts we used to:
    - extract all files LOC, code churn, changes types, commits, and identify all bug-inducing commits related to every file. [``FindingFault-Inducing-CommitsAndFault-Fixing-Comits.py``](https://github.com/stilab-ets/CodeSmells_WebApps/blob/main/Scripts/FindingFault-Inducing-CommitsAndFault-Fixing-Comits.py)
    - the script to get all issues state and ID [``FindingIssuesStateAndID.java``](https://github.com/stilab-ets/CodeSmells_WebApps/blob/main/Scripts/FindingIssuesStateAndID.java).
    - the apriori algorithm implementation [``AprioriAlgorithm.py``](https://github.com/stilab-ets/CodeSmells_WebApps/blob/main/Scripts/AprioriAlgorithm.py)
    - the code smells occurrence frequency [``CodeSmellsOccurrenceFrequency.py``](https://github.com/stilab-ets/CodeSmells_WebApps/blob/main/Scripts/CodeSmellsOccurrenceFrequency.py)

3. The ``OccAllApp.csv`` contain all types of code smells found in each smelly file of the 400+ studied releases.

# How to cite?

Please, use the following bibtex entry:

```tex
@article{bessghaier2021longitudinal,
  title={A longitudinal exploratory study on code smells in server side web applications},
  author={Bessghaier, Narjes and Ouni, Ali and Mkaouer, Mohamed Wiem},
  journal={Software Quality Journal},
  volume={29},
  pages={901--941},
  year={2021},
  publisher={Springer}
}
```
