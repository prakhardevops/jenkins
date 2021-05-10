Create a git CI/CD pipeline which would perform all the scans in parallel, also we would like the user to have the option to skip various scans in the build execution and push the artifact to Artifactory. Now Before deployment we would like an approval stage to be set in place to approve or deny the deployment and if approved the deployment should execute and the user should be notified post successful/failed deployment.

**We have already setup SonarQube and Nexus in Assignment 6.**

We have made a parameterized job for skipping scan which we pass as parameter.

![](Aspose.Words.081b850a-9cc0-4b78-98b3-73ecb48cc266.001.png)  

Now we build job with choice Scan 1

![](Aspose.Words.081b850a-9cc0-4b78-98b3-73ecb48cc266.002.png)

It will skip scan 1 and will perform scan 2

![](Aspose.Words.081b850a-9cc0-4b78-98b3-73ecb48cc266.003.png)

It will ask for user input in between as

![](Aspose.Words.081b850a-9cc0-4b78-98b3-73ecb48cc266.004.png) 

We clicked on proceed to upload artifact to nexus.

![](Aspose.Words.081b850a-9cc0-4b78-98b3-73ecb48cc266.005.png) 

![](Aspose.Words.081b850a-9cc0-4b78-98b3-73ecb48cc266.006.png) 

Sonarcube scan result as

![](Aspose.Words.081b850a-9cc0-4b78-98b3-73ecb48cc266.007.png) 

In Blue Ocean it will look like as

![](Aspose.Words.081b850a-9cc0-4b78-98b3-73ecb48cc266.008.png)
