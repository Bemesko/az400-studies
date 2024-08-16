You can use this to get artifacts produced by builds done on external build systems such as [[Jenkins]]

```yaml
resources:
	builds:
	- build: MyJenkins
	  type: Jenkins
	  connection: JenkinsServiceConnection
	  source: MyJenkinsProject
	  trigger: true
```

Using artifacts:
```yaml
- job: download_jenkins
  steps:
  - downloadBuild: MyJenkins
    patterns: '**/*.zip'
```