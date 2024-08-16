Useful for using multiple repositories in [Azure Pipelines](Azure%20Pipelines) or getting [Templates in Azure Pipelines](Templates%20in%20Azure%20Pipelines.md)

```yaml
resources:
	repositories:
	- repository: myAzureRepo
	  type: git
	  name: myProject/myRepo

steps:
- checkout: myAzureRepo
```

They are checked out in `Build.SourcesDirectory`