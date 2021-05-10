` `Consider the scenario where you have a text file in your repository 'repo1' containing the details about the ninja batch x in the tabular format like

S. No.    Name    Batch    Tool

1        Naveen       x        Jenkins

2        Mohit      x        Sonarqube

We have one more repository 'repo2' which contains a shell script that would read a file and then print only the 'Name' and the 'Tool' column

We have to setup a Jenkins job which would clone the repo1 and as the part of my build I would like the repo 2 as well to be cloned and the shell script should be executed

Repo 1 have file tools.txt.

![](Aspose.Words.6a877b3e-dc8d-4b33-8852-4ec2c3454c40.001.png) 

Repo 2 have script to show name and tool from tools.txt

![](Aspose.Words.6a877b3e-dc8d-4b33-8852-4ec2c3454c40.002.png) 

` `Pipeline for displaying name and tool



![](Aspose.Words.6a877b3e-dc8d-4b33-8852-4ec2c3454c40.003.png) 

![](Aspose.Words.6a877b3e-dc8d-4b33-8852-4ec2c3454c40.004.png) 

![](Aspose.Words.6a877b3e-dc8d-4b33-8852-4ec2c3454c40.005.png)  

![](Aspose.Words.6a877b3e-dc8d-4b33-8852-4ec2c3454c40.006.png)

\- Consider a scenario where you are having around 10 jobs in your jenkins instance and all the jobs are having around 30 builds in their build history, now we would like to clean the clutter but not by manually going and removing every build but by using a more automated approach, discover if there is a way we can do this in jenkins and implement the same.

We have used Purge Build History Plugin for this.

![](Aspose.Words.6a877b3e-dc8d-4b33-8852-4ec2c3454c40.007.png) 

![](Aspose.Words.6a877b3e-dc8d-4b33-8852-4ec2c3454c40.008.png) 

![](Aspose.Words.6a877b3e-dc8d-4b33-8852-4ec2c3454c40.009.png)

\- Consider a scenario where you have a build history of failed and successful build, discover a way in jenkins to visualize this in a better way instead of going through the status globes everytime.

We used Blue Ocean Plugin for this.

![](Aspose.Words.6a877b3e-dc8d-4b33-8852-4ec2c3454c40.010.png)
