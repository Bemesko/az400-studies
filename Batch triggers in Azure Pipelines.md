[Azure Pipelines Triggers](Azure%20Pipelines%20Triggers.md) useful to reduce the number of times a pipeline runs.

Sample:
```yaml
trigger:
	batch: true
	branches:
		include:
		- main
```
If there is an ongoing build in main and more people commit, the build will only trigger again once the last build is finished and will include all commits since the last build. As opposed to triggering the build again for every new commit