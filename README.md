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

![image](https://user-images.githubusercontent.com/11299574/133940970-4c7694f5-155b-46e2-b287-299da156ee3e.png)

Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project. It's a primary DevOps best practice, allowing developers to frequently merge code changes into a central repository where builds and tests then run.

In other words it involves the continuous integration of code changes made by developers into the shared branch/repository. The code to be integrated has to undergo a verified test to ensure it does not break the application. It is only when the test passes that it is integrated

The simplest example of continuous integration is something you might not have even thought of being significant: committing all your application code in a single repository!

