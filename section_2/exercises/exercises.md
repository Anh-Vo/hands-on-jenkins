## Section 2: Exercises


### Theory

1. Describe the difference between a job/project and a build. 
A job/project is a structured and repeated set of instructions for jenkins to carry out. A build is a discrete execution of the job/project.

2. What is a workspace?
A workspace is a file structure and contains the required source code for the project.

3. What is a build trigger and how would you use it in a job?
A build trigger is a notification mechanism that allows external sources to notify jenkins to execute a build. One usage is setting jenkins to run a build whenever a new push is commited to github.

4. What is a parameterized job and when would you use it?
Parameterized jobs allow run time configurations for a project. This allows a user to customize the specific run of a build.

### Practice

In video 2.4 you saw how to pull code from a GitHub repository. Instead of pulling code from this companion GitHub repository, open a GitHub account (if you don't have one already), create a new repository, and upload a shell or a batch script. Then configure a new Jenkins job to pull code from your repository and run the build. 

In case you are already familiar with build tools such as ant, maven, or gradle, write a script with these tools and invoke the relevant script when choosing the build step. 
