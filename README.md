

### Diamond Shaped Pipeline with unstable step

![Image](images/cleanup-pipeline.png)

Required plugins:

- https://wiki.jenkins-ci.org/display/JENKINS/Join+Plugin
- https://wiki.jenkins-ci.org/display/JENKINS/Parameterized+Trigger+Plugin

Note: contains CloudBees {folder} notation not available in master yet.

### 20150706-1

Checkout source from github, run gradle tests and parse performance reports.

Plugins:
- git
- performance-plugin

