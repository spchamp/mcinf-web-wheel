web-wheel
=========

Web architecture for projects developed under MetaCommunity.info

## Architecture

### Development Architecture (Ideal ModeL)

* [YouTrack](https://www.jetbrains.com/youtrack/)
* [Github](https://github.com/) (hosted) or [Gitorious](http://getgitorious.com/) (local)
* [TeamCity](https://www.jetbrains.com/teamcity/)(hosted, close YouTrak integration) or [Jenkins](http://jenkins-ci.org/) (local)
    * Resource [YouTrack plugin for Jenkins](https://wiki.jenkins-ci.org/display/JENKINS/YouTrack+Plugin)
* Tentative: [TestLink](http://sourceforge.net/projects/testlink/)
    * Resource: [TestLink Integration with YouTrack](http://confluence.jetbrains.com/display/YTD6/Integration+with+TestLink)
    * Testing may be integrated with build process, and managed under the selected CI platform

### Container Architecture

* Oracle Java
* Tomcat 7
* Glassfish EE Server
* Apache HTTPD

