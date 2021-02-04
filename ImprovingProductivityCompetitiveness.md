# Improving Productivity and Competitiveness

Over the last few years new technologies have enabled companies to increase their productivity and their competitiveness in the market. Here we will  be discussing a couple of these technologies:

1. [Git](#git)
2. Docker

In addition, there have also been new development practices that improved the usage of these technologies as well as enabled companies to quickly detect any issues with new implementations and minimize the impact these might have on their product and services.

1. Automated Testing
2. Continuous Integration

## GIT
Git is a Version Control System (VCS), however, is not like any other VCS. Most VCSs only capture the changes made to each file over time, also know as delta-based version control. On the other hand, Git takes a snapshot of what all your files look like at the moment of the commit or when the project is saved.

Another advantage of Git is that most operations only require local files and resources since you have all the files from the project cloned to your local disk. Which means that all these operations will be completed almost instantaneous, even if you are offline or are not connected to VPN.

Git also shares some similarities with other version control systems, like not loosing any changes once they are commited. Every change in Git generates a checksum using SHA-1 hash, this has is stored on the Git database and is the key used to identified any changes made to the repository. This enables you to make changes without the worry of destroying your production environment as you can always revert back these changes.