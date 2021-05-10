Consider a scenario where we would like to list out all the "installed packages(linux OS) / list of files in the dir(windows OS)" on our machines via a Jenkins pipeline based on the OS of our machine, i.e. if it is windows then it should execute a command to list the content/files of current working directory(of windows machine) in build logs and if the OS is linux then execute a bash script to get all the installed packages and store them in a file and finally when the execution is done we would like to view the file in our Jenkins UI itself.

![](Aspose.Words.7070e15b-b8da-49e6-b6af-aab39b1b6fc3.001.png)

![](Aspose.Words.7070e15b-b8da-49e6-b6af-aab39b1b6fc3.002.png) 

![](Aspose.Words.7070e15b-b8da-49e6-b6af-aab39b1b6fc3.003.png) 

![](Aspose.Words.7070e15b-b8da-49e6-b6af-aab39b1b6fc3.004.png)

Create a CI pipeline for our maven based application where we would like to get a list of all the goals(mvn commands) as the parameters which we can select from and based on our choice only that goals(mvn commands) should be executed








![](Aspose.Words.7070e15b-b8da-49e6-b6af-aab39b1b6fc3.005.png) 

![](Aspose.Words.7070e15b-b8da-49e6-b6af-aab39b1b6fc3.006.png) 

![](Aspose.Words.7070e15b-b8da-49e6-b6af-aab39b1b6fc3.007.png) 

![](Aspose.Words.7070e15b-b8da-49e6-b6af-aab39b1b6fc3.008.png) 

![](Aspose.Words.7070e15b-b8da-49e6-b6af-aab39b1b6fc3.009.png)
