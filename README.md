# The Microservice Dependency Graph Dataset

This is the official repository of the "Microservice Dataset". 

The current release is 1.0 [download here](https://github.com/clowee/MicroserviceDataset/archive/1.0.zip)

The dataset contains the dependency analysis of a set of microservices-based projects. 
For each project, the directlry "MicroDepGraphDataset" contains as GraphML file with all the dependencies, and a svg files graphically representing it.

Please note that all the services are represented in the svg files with the same symbols. Databases, message buses, and all the other services are represented with an oval shape. 
The figure below shows an example of graphical representation of the dependencies in one project (ftgo)

![FTGO example (svg)](https://github.com/clowee/MicroDepGraph/raw/master/resultGraphs/ftgo-application-master.png)


## Table of contents
* **[What is it](#What-is-it)**
* **[How to cite the Microservice Dependency Graph Dataset](#how-to-cite)**
* **[How to contribute](#how-to-contribute)**

## What is it

Microservice Dependency Graph Dataset is a curated dataset containing dependency graph of 20 microservice projects. It includes the GraphML file and also the SVG file of the dependency graph.

The dataset was built by analyzing the projects by SLOCcount and [MicroDepGraph](https://github.com/clowee/MicroDepGraph). To generateGraphML file we used Apache TinkerPop graph computing framework. TheGraphML  file  is  easy  to  use  xml  based  file  where  we  can  specify  directed  or undirected graphs and different attributes to the graph. Moreover we can import the GraphML file in different graph visualization platforms like Gephi. In this kind of graph visualization tools we can then apply different graph algorithms  for further analyzing the graph. We also get SVG image as output so that it can be easily used for further processing.

A complete description of the dataset is available [here](https://arxiv.org/pdf/1909.03249.pdf).

## How to cite 

Please, cite as "The Microservice Dataset, Version 1.0 [1]"

[1] Mohammad Imranur Rahman, Sebastiano Panichella, Davide Taibi. A curated Dataset of Microservices-Based Systems. Joint Proceedings of the Summer School on Software Maintenance and Evolution. Tampere, 2019 
```
@INPROCEEDINGS{Rahman2019,
  author = {Rahman, MI.and Taibi, Davide},
  title = {A curated Dataset of Microservices-Based Systems},
  booktitle={Joint Proceedings of the Summer School on Software Maintenance and Evolution}, 
  year={2019}, 
  month={September},
  publisher    = {CEUR-WS}
  location = {Tampere, Finland}
  }
```

## How to contribute
If you have analyzed a project with MicroDepGraph and you are interested to share your data in our dataset, please send us an email ( davide [dot] taibi [ at ] tuni [ dot ] fi )

To integrate your analysis please, report the following information 
* project_name
* development_language
* github_url
* GraphML file
* SVG file

## License
The Microservice Dependency Graph Dataset has been developed only for research purposes. It includes the number of lines code of each public repository, GraphML file and SVG file of dependency graph. Information from GitHub is stored in accordance with GitHub Terms of Service (GHTS), which explicitly allow extracting and redistributing public information for research purposes ([GitHub Terms of Service](goo.gl/yeZh1E) Accessed: May 2019). 

The _Microservice Dependency Graph Dataset_ is licensed under a Creative Commons Attribution-NonCommercial- ShareAlike 4.0 International license.

 
# List of project analyzed for Microservice Dataset

| Project Name                             | GIthub URL            | Number of microservices | Total Size (Lines of Code) | Dependency Graph |

|------------------------------------------|-----------------------|-------------------------|------------------|
| Microservice Architecture for blog post  | http://bit.ly/2OKY29v | 9                       |         1536     | 
| E-Commerce App                           | http://bit.ly/2yLqTPW | 7                       |          967     | 
| Consul demo                              | http://bit.ly/2KsGzx6 | 5                       |         2343     |
| EnterprisePlanner                        | http://bit.ly/2ZPK7je | 5                       |         4264     |
| eShopOnContainers                        | http://bit.ly/2YGSkJB | 25                      |        69874     |
| FTGO - Restaurant Management             | http://bit.ly/2M7f8fm | 13                      |         9366     |
| Lakeside Mutual Insurance Company        | http://bit.ly/33iJSiU | 8                       |        19363     |
| Microservices book                       | http://bit.ly/2TeSbI2 | 6                       |         2417     |
| spring-cloud-netflix-example             | http://bit.ly/2YOUJxJ | 9                       |          419     |
| Pitstop - Garage Management System       | http://bit.ly/2Td7NLY | 13                      |        34625     |
| Robot Shop                               | http://bit.ly/2ZFbHQm | 12                      |         2523     |
| Share bike (Chinese)                     | http://bit.ly/2YMJgmb | 9                       |          302     |
| Spring Cloud Microservice Example        | http://bit.ly/2GS2ywt | 10                      |         2333     |
| Spring PetClinic                         | http://bit.ly/2YMVbAC | 8                       |         2475     |
| Tap-And-Eat (Spring Cloud)               | http://bit.ly/2yIjXmC | 5                       |         1418     |
| Vehicle tracking                         | http://bit.ly/31i5aLM | 8                       |         5462     |
| Lelylan - Open Source Internet of Things | http://bit.ly/2TdDfd3 | 14                      |         7763     |
| Spinnaker                                | http://bit.ly/2YQA2S7 | 10                      |        33822     |
| Open-loyalty                             | http://bit.ly/2ZApXtA | 5                       |        16641     |
| CQRS microservice application            | http://bit.ly/2YtbtiF | 7                       |         1632     |
