Create a CI pipeline to build the maven application along with the unit test, scans for code quality, vulnerability, code coverage- Integrate your Jenkins instance with Artifactory.- Publish the final artifacts to the Artifactory.

We have setup 2 different server as nexus server and sonarcube server

Nexus Server

![](Aspose.Words.421bc067-375b-4d34-8096-ccbc33faa7a2.001.png) 

SonarCube Server

![](Aspose.Words.421bc067-375b-4d34-8096-ccbc33faa7a2.002.png) 

We have installed N**exus Artifact Uploader ,Nexus Platform Plugin ,SonarQube Scanner for Jenkins**

We have configured Nexus and Sonar Server in Jenkins as following

![](Aspose.Words.421bc067-375b-4d34-8096-ccbc33faa7a2.003.png) 

![](Aspose.Words.421bc067-375b-4d34-8096-ccbc33faa7a2.004.png) 

` `We used Pipeline as

![](Aspose.Words.421bc067-375b-4d34-8096-ccbc33faa7a2.005.png) 

![](Aspose.Words.421bc067-375b-4d34-8096-ccbc33faa7a2.006.png) 

![](Aspose.Words.421bc067-375b-4d34-8096-ccbc33faa7a2.007.png) 

![](Aspose.Words.421bc067-375b-4d34-8096-ccbc33faa7a2.008.png) 

![](Aspose.Words.421bc067-375b-4d34-8096-ccbc33faa7a2.009.png)
