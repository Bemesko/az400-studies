Define containers for use in [Container Jobs](Container%20Jobs.md), and also trigger pipelines on tag updates(!)

sample:
```yaml
resources:
	containers:
	- container: myContainer
	  endpoint: myDockerRegistry # custom registry
	  image: myImage
	  trigger:
		  tags:
		  - latest # every change to this tag will trigger a build
```