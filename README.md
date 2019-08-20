# Microservice Dataset
Microservice Dependency Graph Dataset


# The Technical Debt Dataset

This is the official repository of the "Microservice Dataset" [1]. 

The current release is 1.0 [download here](https://github.com/clowee/The-Technical-Debt-Dataset/releases/tag/1.0)



## Table of contents
* **[What is it](#What-is-it)**
* **[How to cite the Technical Debt Dataset](#how-to-cite)**
* **[How to contribute](#how-to-contribute)**
* **[References](#references)**

## What is it

Technical Debt Dataset is a curated dataset containing measurement data from four tools executed on all commits to enable researchers to work on a common set of data and thus compare their results.

The dataset was built by extracting the projects' data and analyzing all the commit using several tools. To get the data, the projects' GitHub repositories were cloned, commit information was collected from the git log using [PyDriller](https://github.com/ishepard/pydriller), refactorings were classified using [Refatoring Miner](https://github.com/tsantalis/RefactoringMiner), and issue information was obtained by extracting issues from the Jira issue tracker. After that, code quality was inspected using two tools: Technical Debt items were analyzed with [SonarQube](https://www.sonarqube.org/), and code smells [2] and anti-patterns [3] with [Ptidej](http://www.ptidej.net/). In addition, the fault-inducing and -fixing commits were identified by applying [our implementation](https://github.com/clowee/OpenSZZ) of the SZZ algorithm [4].


## How to cite 

Please, cite as "The Microservice Dataset, Version 1.0 [1]"

[1] ..., Davide Taibi. The Microservice Dataset. Proceedings of the joint Summer School on Software Evolution and Software Quality and Bug Prediction with Machine Learning. CEUR-WS.  Tampere, 2019 
```
@INPROCEEDINGS{Lenarduzzi2019,
  author = {Lenarduzzi, Valentina and Saarim{\"a}ki, Nyyti and Taibi, Davide},
  title = {The Technical Debt Dataset},
  booktitle={15th Conference on Predictive Models and Data Analytics in Software Engineering}, 
  year={2019}, 
  month={January},
  }
```

## How to contribute
If you have analyzed a project with SonarQube and you are interested to share your data in our dataset, please send us an email ( davide [dot] taibi [ at ] tuni [ dot ] fi )

To integrate your analysis please, report the following information 
* sonarqube_version
* project_name
* development_language
* github_url
* analyzed branch
* jira url 

We will run the SZZ tool and refactoring miner 1.0.0 on your repository and integrate your data in a new release of the dataset. 

We are also looking for contributors to automate the analysis pipeline. If you are interested to contribute, send us a message. 

## License
The Technical Debt Dataset has been developed only for research purposes. It includes the historical analysis of each public repository, including commit messages, timestamps, author names, and email addresses. Information from GitHub is stored in accordance with GitHub Terms of Service (GHTS), which explicitly allow extracting and redistributing public information for research purposes ([GitHub Terms of Service](goo.gl/yeZh1E) Accessed: May 2019). 

The _Technical Debt Dataset_ is licensed under a Creative Commons Attribution-NonCommercial- ShareAlike 4.0 International license.

 ## Empirical studies based on the Technical Debt Dataset
The _Technical Debt Dataset_ has been used in different works: 

* Nyyti Saarimäki, Valentina Lenarduzzi, and Davide Taibi. 2019. On the diffuseness of code technical debt in open source projects of the Apache Ecosystem. International Conference on Technical Debt (TechDebt 2019) 2019.

* Valentina Lenarduzzi, Antonio Martini, Davide Taibi, and Damian Andrew Tamburri. 2019. Towards Surgically-Precise Technical Debt Estimation: Early Results and Research Roadmap. In2019 IEEE Workshop on Machine Learning Techniques for Software Quality Evaluation (MaLTeSQuE)

* Valentina Lenarduzzi, Francesco Lomio, Davide Taibi, and Heikki Huttunen. 2019.On the Fault Proneness of SonarQube Technical Debt Violations: A comparison of eight Machine Learning Techniques.  arXiv:1907.00376


 ## References
[1] Valentina Lenarduzzi, Nyyti Saarimäki, and Davide Taibi. 2019. The Technical Debt Dataset. In 15th Conference on Predictive Models and Data Analytics in Software Engineering, 2019.

[2] Fowler, Martin. Refactoring: improving the design of existing code. Addison-Wesley Professional, 2018.

[3] Brown, William H., et al. AntiPatterns: refactoring software, architectures, and projects in crisis. John Wiley & Sons, Inc., 1998.

[4] Śliwerski, Jacek, Thomas Zimmermann, and Andreas Zeller. "When do changes induce fixes?." ACM sigsoft software engineering notes. Vol. 30. No. 4. ACM, 2005.







| Project Name                             | GIthub URL            | Number of microservices | Total Size (Lines of Code) | Dependency Graph |
|------------------------------------------|-----------------------|-------------------------|------------------|----------|
| Microservice Architecture for blog post  | http://bit.ly/2OKY29v | 9                       |    <a href="https://github.com/clowee/MicroDepGraph/raw/master/resultGraphs/ftgo-application-master.png" download="ftgo-application-master.svg">View</a>              | |
| E-Commerce App                           | http://bit.ly/2yLqTPW | 7                       |                  | |
| Consul demo                              | http://bit.ly/2KsGzx6 | 5                       |                  | |
| EnterprisePlanner                        | http://bit.ly/2ZPK7je | 5                       |                  | |
| eShopOnContainers                        | http://bit.ly/2YGSkJB | 25                      |                  | |
| FTGO - Restaurant Management             | http://bit.ly/2M7f8fm | 13                      |                  | |
| Lakeside Mutual Insurance Company        | http://bit.ly/33iJSiU | 8                       |                  | |
| Microservices book                       | http://bit.ly/2TeSbI2 | 6                       |                  | |
| spring-cloud-netflix-example             | http://bit.ly/2YOUJxJ | 9                       |                  | |
| Pitstop - Garage Management System       | http://bit.ly/2Td7NLY | 13                      |                  | |
| Robot Shop                               | http://bit.ly/2ZFbHQm | 12                      |                  | |
| Share bike (Chinese)                     | http://bit.ly/2YMJgmb | 9                       |                  | |
| Spring Cloud Microservice Example        | http://bit.ly/2GS2ywt | 10                      |                  | |
| Spring PetClinic                         | http://bit.ly/2YMVbAC | 8                       |                  | |
| Tap-And-Eat (Spring Cloud)               | http://bit.ly/2yIjXmC | 5                       |                  | |
| Vehicle tracking                         | http://bit.ly/31i5aLM | 8                       |                  | |
| Lelylan - Open Source Internet of Things | http://bit.ly/2TdDfd3 | 14                      |                  | |
| Spinnaker                                | http://bit.ly/2YQA2S7 | 10                      |                  | |
| Open-loyalty                             | http://bit.ly/2ZApXtA | 5                       |                  | |
| CQRS microservice application            | http://bit.ly/2YtbtiF | 7                       |                  | |
