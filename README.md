web-wheel
=========

Web architecture for projects developed under MetaCommunity.info

## Architecture

### Development Architecture (Ideal Model)

* [YouTrack](https://www.jetbrains.com/youtrack/)
* [Github](https://github.com/) (hosted) or [Gitorious](http://getgitorious.com/) (local)
* [TeamCity](https://www.jetbrains.com/teamcity/)(hosted, integrates well with YouTrack) or [Jenkins](http://jenkins-ci.org/) (local)
    * Resource [YouTrack plugin for Jenkins](https://wiki.jenkins-ci.org/display/JENKINS/YouTrack+Plugin)
* Tentative: [TestLink](http://sourceforge.net/projects/testlink/)
    * Resource: [TestLink Integration with YouTrack](http://confluence.jetbrains.com/display/YTD6/Integration+with+TestLink)
    * Testing may be integrated with build process, and managed under the selected CI platform

### Container Architecture

* Oracle Java
* Tomcat 7
* Glassfish EE Server
* Apache HTTPD


### Portal Architecture

* Liferay Portal
* (TBD) Portlets for creating a dashboard out of components of the _development architecture_
* (TBD) Portlets for presentation of project documentation
* (TBD) Portlets for presentation of project file releases
* Similar works:
    * [SourceForge](http://sourceforge.net/)
    * [Alioth](http://alioth.debian.org/) ([FushionForge](https://fusionforge.org)) 
