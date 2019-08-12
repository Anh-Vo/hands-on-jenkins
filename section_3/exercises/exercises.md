## Section 3: Exercises

### Theory

1. What is the difference between Continuous Integration, Continuous Delivery, and Continuous Deployment?
Continuous Integration is the merging and testing of new features into the existing product.
Continuous Delivery is ensuring that a deployable and shippable state of the product is always available.
Continuous Deployment is CD on steroids, wherein a change is pushed into production resulting in multiple deployments a day.

2. What are the main components of a typical CI workflow? 
The main components consists of the developer making a change to the code base, pushing that change to some source management
repository, that repository then notifying jenkins that a new build should be kicked off, finally jenkins running that build and tests.

3. List and explain some types of tests. 
Integration, Smoke, Stress/Load, Unit tests.

4. What is the difference between passive notifications and active notifications?


### Practice

1. Replace Slack with another notification channel of your choice (e.g. email, IRC, RSS feeds, etc.). 

2. If you have software project you are working on, try to implement a CI workflow around it that builds, tests, and notifies. Feel free to use the tools you're more familiar with. 
