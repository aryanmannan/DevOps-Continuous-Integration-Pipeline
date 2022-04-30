# DevOps-Continuous-Integration-Pipeline 

### DevOps
DevOps is a set of practices usually adopted by an organisation that combines software development and IT operations. Its goal is to shorten the software development life cycle and provide continuous updates.

### Continuous integration/continuous delivery (CI/CD) pipeline
A CI/CD pipeline is a series of steps that must be performed in order to deliver a new version of software. Continuous integration/continuous delivery (CI/CD) pipelines are a practice focused on improving software delivery using either a DevOps or site reliability engineering (SRE) approach.

### Continuous Integration (CI)
Continuous integration is a DevOps software development practice where developers regularly merge their code changes into a central repository, after which automated builds and tests are run. It most often refers to the build or integration stage of the software release process.

### Jenkins
Jenkins isvan open source automation server which enables developers around the world to reliably build, test, and deploy their software. It can work with Java, JavaScript, Groovy, Golang, Ruby, Shell scripts.

### Objective
The Objective of this project is to demonstrate the working of continuous integration pipelines in DevOps through Jenkins by compiling, reviewing and testing a code from a user specified github repository.

### Overview
The DevOps-Continuous-Integration-Pipeline Project aims at obtaining source code from a github repository specified by the user and then carrying out three major processes (jobs) on that source code to validate its usability and represent it on a pipeline that is called the CI pipeline. Each run of these three jobs created is called a build and each step is called a build step. The jobs that are carried out in this project are:  
##### 1. Compile Job:
Job to compile the code that is present in the github repository
##### 1. Review Job
Job to review the code that has been compiled by the previous job
##### 1. Test Job
Job to carry out all the test cases for the compiled and reviewed code  

### Technology Used: Jenkins

### Plug-ins Utilized:
Jenkins comes with a pre-loaded set of plug-ins that it uses to carry out its basic functions, not all jobs can be carried out through pre-loaded plugins thus we can also import various plug-ins as per requirement. The plug-ins used in this project are: Repository Connector, Tracking Git Plugin, Pipeline: Supporting APIs, Pipeline: Stage View Plugin, Pipeline: GitHub, Pipeline: API, Pipeline, Maven.

### Conclusion
Continuous Integration Pipeline was implemented in Jenkins by compiling, reviewing and testing a source code present in a user-defined github repository.

###### Note:The working of this pipeline on jenkins is shown in the video attached titled 'Working of Continuous Integration Pipeline on Jenkins'. The application runs on user's system server and hence doesn't conist of any files that can be attached.






