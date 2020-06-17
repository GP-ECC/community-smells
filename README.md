
## On the Detection of Community Smells using Genetic Programming-based Ensemble Classifier Chain

This repository is a companion page for our ICGSE 2020 paper "On the Detection of Community Smells using Genetic Programming-based Ensemble Classifier Chain".

It contains all the material required to replicate our analysis, including (i) the raw input data (ii) the list of studied projects, and (iii) the features for each smell instance. Some additional data are not included in the paper due to space limitations, are also provided.

## How to cite?

Please, use the following bibtex entry:

```
@inproceedings{almarimi2020community,
  title={On the Detection of Community Smells using Genetic Programming-based Ensemble Classifier Chain},
  author={Almarimi, Nuri and Ouni, Ali and Chouchen, Moataz and Saidani, Islem and Mkaouer, Mohamed Wiem},
  booktitle={15th IEEE/ACM International Conference on Global Software Engineering (ICGSE)},
  pages={1--12},
  year={2020}
}
```

## Data description : 
The data is presented in CSV format and can be directly imported in R and Weka.


```Dataset-community-smells-Features.csv```: The list of projects with their metrics values.

```Dataset-community-smells-list.csv```: The list of projects with their identified smells.
.
#### Developer Contributions metrics  

```NoD ```: Number of developers

```TAP``` : Number of active days of an author on a Project

```LCP``` : Number of changed lines of a code per author in a project

```CD``` : Number of core developers

```RCD``` : Ratio of core developers

```SD``` : Number of sponsored developers

```RSD``` : Ratio of sponsored developers


#### Social Network Analysis metrics 

```DC``` : Graph Degree centrality

```BC``` : Graph Betweenness centrality

```CC``` : Graph Closeness centrality

```ND``` : Network Density


####  Community metrics 

```NC``` : Number of communities

```RCC``` : Ratio of commits per community

```RDC``` : Ratio of developers per community

####  Geographic Dispersion metrics 

```TZ``` : Number of time zones

```RCZ``` : Ratio of commits per time zone

```RDZ``` : Ratio of developers per time zone


####  Formality metrics 

```NR``` : Number of Releases in a project

```RCR``` : Ratio of Commits per Release 

```FN``` : Formal network


####  Truck Number metrics 

```BFN``` : Bus Factor Number

```TFN``` : Truck Factor Number

```TFC``` : Truck Factor Coverage

