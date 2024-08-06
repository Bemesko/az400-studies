[Task types & usage - Azure Pipelines | Microsoft Learn](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/tasks?view=azure-devops&tabs=yaml#step-target)

```
resources:
	containers:
	- container: berbcontainer
	  image: berb:alpine

steps:
- task: SampleTask@1
  target: host # runs on the actual agent
- task: SampleTask@1
  target: berbcontainer
```