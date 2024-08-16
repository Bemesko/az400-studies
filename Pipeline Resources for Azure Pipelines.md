```yaml
resources:
	pipelines:
	- pipeline: Berb-CI-Resource # identifier to reference the resource
	  project: Berb 
	  source: Berb-CI #name of the pipeline
	  trigger: true # when the Berb-CI pipeline ends trigger this one
```

This is pretty handy because it allows separation of [Continuous Deployment](Continuous%20Deployment) pipelines from the [Continuous Integration](Continuous%20Integration) ones.

[[Downloading artifacts from other pipelines in Azure Pipelines]]