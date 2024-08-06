[Integrate GitHub repos and Azure Pipelines - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/implement-pipeline-strategy/4-integrate-github-repos-azure-pipelines)

- A valid workflow is integrating [[GitHub]] repositories with [Azure Pipelines](Azure%20Pipelines) for [Builds](Builds)
- Consider replicating the permission models on both services because they aren't aware of each other
- [[Agents]] need to connect to [[GitHub]] and authenticate somehow. Recommended method is [[GitHub App Authentication]] which is safer and has more features that [[Personal Access Tokens]] or [[Oauth2]]