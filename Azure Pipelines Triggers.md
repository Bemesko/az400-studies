source: [Build Azure Repos Git repositories - Azure Pipelines | Microsoft Learn](https://learn.microsoft.com/en-us/azure/devops/pipelines/repos/azure-repos-git?view=azure-devops&tabs=yaml#pr-triggers)

minimal syntax
```yaml
trigger:
- main # trigger for only thi branch
- release/* # wildcard trigger
```

include/exclude:
```yaml
trigger:
	branches:
		include:
		- main
		- refs/tags/tag1 # referencing tags
		exclude:
		- releases/*
```

[[Batch triggers in Azure Pipelines]]
[[Tag triggers in Azure Pipelines]]
[[None trigger in Azure Pipelines]]
[[Skipping CI builds in Azure Pipelines]]
[[Structure for Azure Pipelines]]
[[Deployment Strategies for Azure Pipelines]]
[[Templates in Azure Pipelines]]
[[Resources in Azure Pipelines]]