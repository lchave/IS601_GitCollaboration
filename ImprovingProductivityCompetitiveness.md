# Improving Productivity and Competitiveness

Over the last few years new technologies have enabled companies to increase their productivity and their competitiveness in the market. Here we will  be discussing a couple of these technologies:

1. [Git](#git)
2. [Docker](#docker)

In addition, there have also been new development practices that improved the usage of these technologies as well as enabled companies to quickly detect any issues with new implementations and minimize the impact these might have on their product and services.

1. [Automated Testing](#automated-testing)
2. [Continuous Integration](#continuous-integration)

## GIT
Git is a Version Control System (VCS), however, is not like any other VCS. Most VCS only capture the changes made to each file over time, also known as delta-based version control. On the other hand, Git takes a snapshot of what all your files look like at the moment of the commit or when the project is saved. Git also shares some similarities with other version control systems, like not loosing any changes once they are committed. Every change in Git generates a checksum using SHA-1 hash, this hash is stored on the Git database and is the key used to identify any changes made to the repository. This enables you to make changes without the worry of destroying your production environment as you can always revert these changes.

**Delta-Based VCS** |   **Stream of Snapshots (Git)**
----    |   ----
![Delta-Based](/Images/delta-based.png) |   ![Snapshots](/Images/git-snapshots.png)    


One of the many advantages of using Git is that most operations only require local files and resources since you have all the files from the project cloned to your local repository. Which means that all these operations will be completed almost instantaneous, even if you are offline or are not connected to VPN. This makes Git a great collaboration tool, especially when you have multiple developers working on different sections of same project simultaneously. Each developer could work on their own branch offline without affecting the production environment; ensuring that only stable and high-quality code is released at a fast paced.

## Docker
Docker is a platform used for developing and running applications within containers. The applications are basically isolated and packaged within the containers. These containers are lightweight and do not rely on what is installed on the infrastructure running them. Given that containers can run independently of their infrastructure you can ensure that the same application runs smoothly, on a local computer, a data center, in the cloud or even in a mixed environment. 

[![Introduction to Docker](http://img.youtube.com/vi/Q5POuMHxW-0/0.jpg)](http://www.youtube.com/watch?v=Q5POuMHxW-0 "Introduction to Docker")

Similar to Git, Docker is another great collaboration tool. You can share containers with others to ensure everyone's environment works the same way. It also enables companies to accelerate the distribution and testing of their applications while keeping production environments untouched until everything has been fully tested. Due to its portability Docker allows you to manage workloads by scaling up or tearing down applications depending on the business needs. This also makes it cost-effective since you only pay for exactly what you need at that moment. 

## Automated Testing
Part of the software lifecycle involves testing the new code\features added in the application or service; ensuring that these new features do not break existing functionality, and that they actually do what they are supposed to do. Previously, testing was only performed manually and companies would have QA teams responsible for performing these tasks. This was a tedious and expensive process, until Automated testing was introduced.

![Automated Testing](/Images/automated-testing.png)

Basically, all the manual tasks performed by the QA team were now performed using other software tools, and the responsibility was transferred back to the engineering team. They would be the ones in charge of developing the test plans along with the roadmap for each feature release. This enabled companies to reduce the size of their QA team and shift their focus to more sensitive features.

## Continuous Integration
Continuous integration (CI) is a development practice for automating the integration  of multiple code changes into a single repository where builds and tests then run. Using a VCS and other automated tools, like automated code quality tests, and syntax style review tools, are essential to the CI process.

![Continuous Integration](/Images/continuous-integration.png)

A CI process enables a company to save time, implement changes faster and stay competitive in the market. Without a CI process, multiple teams in the organization must coordinate and communicate when they are new code changes, new releases, and new bug fixes that need to implemented. Also, all the benefits of using a VCS, like having multiple developers working is different features in parallel, are also applied here given that a VCS is essential to the CI process.