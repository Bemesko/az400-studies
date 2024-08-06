[Container jobs in YAML - Azure Pipelines | Microsoft Learn](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/container-phases?view=azure-devops&tabs=linux)

- Not supported on macos
- Obviously need access to the [[Docker]] daemon
- [Self Hosted Agent Pools](Self%20Hosted%20Agent%20Pools) needs to be running on the host, container agents dont work (but it would be redundant anyway)
- Only for [YAML Pipelines](YAML%20Pipelines.md)
- Needs the [[GNU C]] packages (glibc) which notably don't exist in [[Alpine]] based images 
	- [[Azure Pipelines]] scripts need [[NodeJS]] to run on agents, which in turn use the [[C Language]] runtime.

Minimal syntax:
```yaml
pool:
  vmImage: 'ubuntu-latest'

container: ubuntu:18.04

steps:
- script: printenv
```

You can use [[Step Targets]] to specify different containers to run each step