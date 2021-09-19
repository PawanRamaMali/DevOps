# DevOps

### Existing Code Integration Pain Points

* Software engineers spend a lot of time trying to bring their codebase up to date with the changes that have occurred in the production branch while they were working.
* In doing that, they have to fix a series of merge conflicts.
* There is also the possibility of them breaking the production branch, which goes on to affect those who pull from the branch before the issue is seen and fixed.
* Integration is Painful and Effort consuming 
* Fixing Issues at the end of Iterations
* Intermediate Merge Issues can hold up teams
* Long feedback cycle for functional defects
* Long iterations


### Continuous integration (CI) 

![image](https://user-images.githubusercontent.com/11299574/133941051-d2a8901d-b7bb-453d-b0f3-ebcb080fe168.png)

Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project. It's a primary DevOps best practice, allowing developers to frequently merge code changes into a central repository where builds and tests then run.

In other words it involves the continuous integration of code changes made by developers into the shared branch/repository. The code to be integrated has to undergo a verified test to ensure it does not break the application. It is only when the test passes that it is integrated

The simplest example of continuous integration is something you might not have even thought of being significant: committing all your application code in a single repository!

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

