While implementing CI with Java we can you multitude of different tools. For linting it is possible to use tools such as SpotBugs, PMD, Checkstyle and Error Prone. For testing we can use such tools as for example JUnit, TestNG, Selenium, Apache JMeter, FitNesse. Building with Java we can use tools like Gradle, Apache Maven and Cmake.

Alternatives to setup CI besides Jenkins and GitHub Actions while using Java are for example GitLab, Atlassin Bamboo, CircleCI, TeamCity and Travis CI

When considering whether it would be wiser to use self-hosted or a cloud based
environment there are a few elements that we need to consider. 

The benefits of a self-hosted setup is that it is very flexible and the only limit is the amount of hardware at hand. It is also more secure since others can't get access to it. The downsides are that they can be very
complicated to setup and there is the risk of hardware failure. You also have
to pay for the hardware which can get very expensive but what you do on the 
server won't change the billing.

The benefits of the cloud-hosted system is that it is easy to setup and a lot 
cheaper for small and medium size projects. The downside
is that there is usually limit for the hardware usage. Cloud-hosted systems are billed by build time which might not be optimal for very large projects.  

For the project that was introduced on the assignment I would probably use
cloud-hosted platforms since there is only 6 people working on it. The cloud-based platform would most likely be all that is needed and would be faster to implement and more cost effective to use.