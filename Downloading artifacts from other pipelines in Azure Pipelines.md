Consider this:
```yaml
resources:
	pipelines:
	- pipeline: Berb-CI
	  source: Berb-CI # this pipeline produces an artifact berb.zip
```

I can later download the artifact from this pipeline using:
```yaml
- job: download
  steps:
  - download: Berb-CI # identifier for the pipe resource
    artifact: BerbZip
    patterns: 'berb.zip'
```