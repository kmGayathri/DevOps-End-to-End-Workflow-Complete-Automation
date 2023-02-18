# DevOps-End-to-End-Workflow-Complete-Automation
This repository contains a project where I’ve managed to create a DevOps environment and complete automation from end to end.


### Overview 

##### This Application is all about if you give some country code it will tell what are the top 10 topics which are more popular for the specific day in that country. 

1. In this project, a developer (Stalin) writes code.
2. Then he pushes the code to source control management (SCM). I am using Github as a version control system.
3. I use Jenkins to pull the code and build it. I use Jenkins Master & Slave Configuration. So, I don't run jobs on the master node. I run it on a Jenkins slave node.
4. Slave node is capable to run the Java based application as well as container based applications to build. I use Maven and Docker in the slave system.
5. To secure our Jenkins server, I use NGINX. NGINX is a reverse proxy. We don't expose our application systems directly to external networks or users.
6. To validate our code quality, I am going to use SonarQube. SonarQube helps us to do the analysis of our code and if there are any code standards are deviated then it will intimate to our Continuous Integration System.
7. Whatever I am going to build during this phase will be stored in the Jfrog Artifactory.
8. Our deployment environment is Kubernetes. I am going to use Kubernetes to deploy our microservice-based applications and run them.
9. While running i need to monitor our application weather those are performing well or not, is there anny issues for that i use Prometheus Terraform c& Grafana. 
10. I set up all this environment on AWS because we need servers.
11. Most of the infrastructure is provided by Terraform. I will write Terraform scripts to provision our infrastructure on the AWS Cloud.
12. Once I have set up EC2 instances, I want to configure our systems, so I use Ansible.

#### Tools to be covered 

- AWS  
- Terraform 
- Git & GitHub 
- Jenkins 
- Maven
- NGINX 
- SonarQube
- Jfrog Artifactory 
- Kubernetes 
- Prometheus & Grafana



