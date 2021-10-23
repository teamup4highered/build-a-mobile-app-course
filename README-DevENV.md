# Setting Up a Development Environment

This document is about setting up a development environment with [Vusial Studio Code](https://code.visualstudio.com/) (VC) as editor under Windows 10. 

## Set up Flutter Project
Follow [Flutter Get Started](https://flutter.dev/docs/get-started/install) Documentation section 1 and 2.
- install Android studio and set up a device in AVD Manager even if you are planning to use VC
- make sure that ```flutter doctor``` does not print any issues

Create a new Flutter Project
Follow [Flutter Get Started](https://flutter.dev/docs/get-started/install) Documentation section 3.
- test the default counter app in a web browser and a mobile device (we use android)

## Set up a git project
### Software Stack
1. [Git for Windows](https://gitforwindows.org/) for bash terminal
1. [GihHub](https://github.com/) repository for version control
1. Configure [Personal Access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) for GitHub from the VC terminal

### Initialize a git project
1. Create a new repository on GitHub.  
1. Start Visual Code (VC)
1. Open a new folder inside VC
1. Open a terminal inside VC and switch to bash terminal
1. Clone the repository that you created in GitHub

### Set up README
1. Open the cloned repo folder in VC
1. Open the repository README.md file
1. In a terminal run ```flutter doctor -v``` 
1. Copy the output in the README.md file and check it in the repository
```
git add .
git commit -a -m "saved flutter doctor output in the README file"
git push
``` 

