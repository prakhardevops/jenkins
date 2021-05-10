\1. We would like to manage three teams in our organizations - Dev, Qa and DevOps, all the users in Dev should be able to configure and execute the jobs, all the users in QA should be able to only execute the jobs and all the users in DevOps should be able to manage the entire Jenkins instance.

\2. Consider the scenario having 3 jobs Dev, Qa and DevOps and we have 3 functional users Dev, Qa and DevOps, we would like to setup the instance in such a manner that the user Dev should only have access to the Dev job, the user Qa should only have the access to the Qa job and the user DevOps should have the access to all the jobs.

Sample Jenkins User

Use Role-based Authorization Strategy for roals.


![](Aspose.Words.0826b68e-26f4-4f91-bfde-5c762f84c03a.001.png) 

![](Aspose.Words.0826b68e-26f4-4f91-bfde-5c762f84c03a.002.png) 

![](Aspose.Words.0826b68e-26f4-4f91-bfde-5c762f84c03a.003.png) 

![](Aspose.Words.0826b68e-26f4-4f91-bfde-5c762f84c03a.004.png) 

![](Aspose.Words.0826b68e-26f4-4f91-bfde-5c762f84c03a.005.png) 

For Devops User

![](Aspose.Words.0826b68e-26f4-4f91-bfde-5c762f84c03a.006.png) 

For dev User

![](Aspose.Words.0826b68e-26f4-4f91-bfde-5c762f84c03a.007.png) 

For qa user

![](Aspose.Words.0826b68e-26f4-4f91-bfde-5c762f84c03a.008.png)
