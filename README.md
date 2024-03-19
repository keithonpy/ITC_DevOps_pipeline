# Introduction to DevOps

## Waterfall model VS Agile model 

| Waterfall model  | Agile model|
| ------------- | ------------- |
| Supports all planning to be completed up front with a clear roadmap for every stage of the project  | Deliver software well-tailored to an ever-growing understanding of customer demands  |
| Utilizes a clear, structured approach | Software is deployed more quickly and improved more regularly  |
| Easy to track progress, identify risks, and manage project budgets|Better code hygiene including style, readability, and structuring|
| Project manager holds significant authority over the project, plan, and value delivery|Flexible and adaptable process enables pivots or changes mid-project|
||Doesn’t require a complete list of requirements upfront|
||Makes room to act on organizational learning as the project progresses|
||Transparency and continuous communication with involved stakeholders|


## Limitations of Agile model

* Development team wants to change
* Operation team wants to be stable

**That's why the DevOps comes!!**

## DevOps Stages in big data
DevOps is a methodology instead of technology​. It helps to build, evolve and operate a rapidly changing systems at scale​


![alt text](https://github.com/keithonpy/ITC_DevOps_pipeline/blob/main/chart/stages.png)
1. Version Control - maintain different version of the code
2. Continuous integration - compile, validate, code review, unit testing, integration testing
3. Continuous Delivery - 
4. Deployment

## CI/CD tools - Jenkins
![alt text](https://github.com/keithonpy/ITC_DevOps_pipeline/blob/main/chart/Jenkins_icon.png)

Jenkins is an open source automation tools written in java with plugins built for continuous integration and continuous delivery purpose

## Building a Jenkins pipeline

1. Trigger build after other projects are built (Freestyle project)
2. Jenkins pipeline


## Jenkins distributed architecture

Jenkins is in a master-slave architecture. Jenkins slaves are generally required to provide the desired environment. 

![alt text](https://github.com/keithonpy/ITC_DevOps_pipeline/blob/main/chart/master-slave.jpg)
