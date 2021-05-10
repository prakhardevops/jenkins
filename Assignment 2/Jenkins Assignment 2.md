#1 Consider a scenario where you have created a script which will install a certain package on your machine and we would like to automate that process using Jenkins but considering an organization perspective we would have 3 functional users in Jenkins as

\- DevOps

\- Dev

\- Qa

The user DevOps is able to manage the Jenkins instance globally

The user Dev is able to manage the jobs in Jenkins

The user QA is only able to execute the jobs nothing else

**This is covered in Assignment 5 .**

You should configure a custom e-mail notification that would send the details about the execution like:

\- Job name

\- Build number

\- who triggered the build

\- Execution status

#2 Consider a scenario where you have created a script which would install a package on your machine based on the name that you have provided and a second script that should display the version of that package on your machine, In jenkins we have a job1 that would execute the script 1 and we would like the second job 'job2' that would execute the second script and we want job2 to be executed automatically as soon as the first job is completed successfully also we would like to place in a check where nobody can trigger a build for Job1 if Job2 is in progress and vice-versa

We have used Build Blocker Plugin for restricting jobs execution.


![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.001.png) 

![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.002.png) 

` `![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.003.png) 

![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.004.png) 

![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.005.png) 

We have used Parameterized Trigger plugin for passing parameters between two jobs.


![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.006.png) 



![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.007.png) ![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.008.png) 



![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.009.png) 

![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.010.png) 

![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.011.png) 

![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.012.png) 

![](Aspose.Words.efe41acb-d543-4091-9dc7-5d838824773e.013.png)
