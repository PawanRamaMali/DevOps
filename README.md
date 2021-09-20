# DevOps

Term is coined by combining the terms "DEVelopment" and "OPerationS"

### Existing Code Implementation Pain Points

* Software engineers spend a lot of time trying to bring their codebase up to date with the changes that have occurred in the production branch while they were working.
* In doing that, they have to fix a series of merge conflicts.
* There is also the possibility of them breaking the production branch, which goes on to affect those who pull from the branch before the issue is seen and fixed.
* Integration is Painful and Effort consuming 
* Fixing Issues at the end of Iterations
* Intermediate Merge Issues can hold up teams
* Long feedback cycle for functional defects
* Long iterations

![image](https://user-images.githubusercontent.com/11299574/133951714-a6077496-b4b7-4f8f-bec2-a54e67ce0fb2.png)


### Continuous integration (CI) 

![image](https://user-images.githubusercontent.com/11299574/133941051-d2a8901d-b7bb-453d-b0f3-ebcb080fe168.png)

Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project. It's a primary DevOps best practice, allowing developers to frequently merge code changes into a central repository where builds and tests then run.

In other words it involves the continuous integration of code changes made by developers into the shared branch/repository. The code to be integrated has to undergo a verified test to ensure it does not break the application. It is only when the test passes that it is integrated

The simplest example of continuous integration is something you might not have even thought of being significant: committing all your application code in a single repository!


![image](https://user-images.githubusercontent.com/11299574/133951924-72f407b3-e704-41d3-a05d-44e32127b8d4.png)

### Types of tests

In writing tests that will be part of the integration process, here are the some that can be implemented in the process:

* Integration – it combines individual units of the software and tests them as a group.
* Unit – it tests for individual units or components of the software like methods or functions.
* UI – asserts that the software works well from the user’s perspective.
* Acceptance – tests that the software meets up to business requirements.

It’s important to note that you do not need to test all of these, as a handful of them may already be covered in the code written by the developer.

### Continuous Integrations Tools

Without going into depth, here are tools that you can start making use of in your current or new projects;

* Travis CI – known in the open-source world and promises to you have your code tested seamlessly in minutes.
* Circle CI – provides you with power, flexibility, and control to automate your pipeline from control to deployment.
* Jenkins – provides hundreds of plugins to support building, deploying, and automating any project.

### Pipeline

A CI/CD pipeline is a series of steps that must be performed in order to deliver a new version of software. Continuous integration/continuous delivery (CI/CD) pipelines are a practice focused on improving software delivery using either a DevOps or site reliability engineering (SRE) approach.

![image](https://user-images.githubusercontent.com/11299574/133952137-9801d937-f83a-4b7c-9b3c-120e2891edd9.png)

![image](https://user-images.githubusercontent.com/11299574/133952180-789ddfad-3ac2-4f34-8d11-52a2d3d044d8.png)

### Old School Operations 

![image](https://user-images.githubusercontent.com/11299574/133971248-c2aa28b6-0540-4b84-9c2e-3ea7b2384cb4.png)

![image](https://user-images.githubusercontent.com/11299574/133971369-0ac2654b-90ef-471c-94ef-8a90d90c1e47.png)

![image](https://user-images.githubusercontent.com/11299574/133971399-246a3e03-0d44-4bcc-be97-ea7e2740d2a1.png)

#### Pain points 

![image](https://user-images.githubusercontent.com/11299574/133971714-e2ea4629-1e35-44fb-830d-927e5a3f9a3e.png)

### Continuous Delivery 

![image](https://user-images.githubusercontent.com/11299574/133975012-bc5d3d6e-ca49-4c01-88a8-2cdab6a85700.png)

Continuous delivery is a software engineering approach in which teams produce software in short cycles, ensuring that the software can be reliably released at any time and, when releasing the software, without doing so manually. It aims at building, testing, and releasing software with greater speed and frequency.

![image](https://user-images.githubusercontent.com/11299574/133974835-0334a5d1-9e48-4bcf-8405-548fd41e6cc5.png)


### Continuous Integration and Continuous Delivery 

![image](https://user-images.githubusercontent.com/11299574/133974987-0495920c-be3b-46ae-9b17-17e1ff87acff.png)

![image](https://user-images.githubusercontent.com/11299574/133975058-6457711d-7fd4-4436-bb27-8f93612ff0ed.png)


### Continuous Delivery and Continuous Deployment


Continuous Delivery is a software development practice where software can be released to production at any time. 

Continuous Deployment is a software development practice where software is automatically released to production continously.

> Only enterprises whose IT department has reached a very high maturity level, will go with Continuous Deployment, because of the risks involved. 

### Continuous Deployment - Phased Rollout 

![image](https://user-images.githubusercontent.com/11299574/133975499-444570f4-ebf2-41de-86f6-e2f57306775b.png)


### DevOps

DevOps does NOT mean a combination of development and Operarations skillset.

It is a new culture, and a new way of thinking, simply hiring people with dual skill sets will not help achieve it.

Automation tools simply enable you to adopt this new way.


![image](https://user-images.githubusercontent.com/11299574/133976252-80fda947-01d3-4172-9ead-c38ed8279f7a.png)



