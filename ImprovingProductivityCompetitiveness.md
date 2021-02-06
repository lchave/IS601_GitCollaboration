# Improving Productivity and Competitiveness

Over the last few years new technologies have enabled companies to increase their productivity and their competitiveness in the market. Here we will  be discussing a couple of these technologies:

1. [Git](#git)
2. [Docker](#docker)

In addition, there have also been new development practices that improved the usage of these technologies as well as enabled companies to quickly detect any issues with new implementations and minimize the impact these might have on their product and services.

1. Automated Testing
2. Continuous Integration

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

