PATs are the only way to authenticate new agents with [Azure DevOps](Azure%20DevOps). 

The token needs the following permissions:
- **Agent Pools (read, manage)**
- If it's a [[Deployment Group Agent]] it needs a **Deployment Group (read, manage)** permission

The token is only used to add the agent pool. After that it can be safely discarded.

Source: [Register an agent using a personal access token (PAT) - Azure Pipelines | Microsoft Learn](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/personal-access-token-agent-registration?view=azure-devops)