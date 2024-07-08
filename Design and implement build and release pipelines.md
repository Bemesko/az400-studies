#### Design and implement a package management strategy

- Recommend package management tools including [[GitHub Packages]] registry and [[Azure Artifacts]]
- Design and implement package feeds and views for local and upstream packages
- Design and implement a dependency versioning strategy for code assets and packages, including semantic versioning ([[SemVer]]) and date-based ([[CalVer]])
- Design and implement a versioning strategy for pipeline artifacts
#### Design and implement a testing strategy for pipelines
- Design and implement quality and release gates, including security and governance
- Design a comprehensive testing strategy, including local tests, unit tests, integration tests, and load tests
- Implement tests in a pipeline, including configuring test tasks, configuring test agents, and integration of test results
- Implement code coverage analysis
#### Design and implement pipelines
- Select a deployment automation solution, including GitHub Actions and Azure Pipelines
- Design and implement a GitHub runner or Azure DevOps agent infrastructure, including cost, tool selection, licenses, connectivity, and maintainability
- Design and implement integration between GitHub repositories and Azure Pipelines
- Develop and implement pipeline trigger rules
- Develop pipelines by using YAML
- Design and implement a strategy for job execution order, including parallelism and multi-stage pipelines
- Develop and implement complex pipeline scenarios, such as hybrid pipelines, VM templates, and self-hosted runners or agents
- Create reusable pipeline elements, including YAML templates, task groups, variables, and variable groups
- Design and implement checks and approvals by using YAML-based environments
#### Design and implement deployments
- Design a deployment strategy, including blue-green, canary, ring, progressive exposure, feature flags, and A/B testing
- Design a pipeline to ensure that dependency deployments are reliably ordered
- Plan for minimizing downtime during deployments by using virtual IP address (VIP) swap, load balancing, rolling deployments, and deployment slot usage and swap
- Design a hotfix path plan for responding to high-priority code fixes
- Design and implement a resiliency strategy for deployment
- Implement feature flags by using Azure App Configuration Feature Manager
- Implement application deployment by using containers, binaries, and scripts
- Implement a deployment that includes database tasks
#### Design and implement infrastructure as code (IaC)
- Recommend a configuration management technology for application infrastructure
- Implement a configuration management strategy for application infrastructure
- Define an IaC strategy, including source control and automation of testing and deployment
- Design and implement desired state configuration for environments, including Azure Automation State Configuration, Azure Resource Manager, Bicep, and Azure Automanage Machine Configuration
- Design and implement Azure Deployment Environments for on-demand self-deployment
#### Maintain pipelines
- Monitor pipeline health, including failure rate, duration, and flaky tests
- Optimize a pipeline for cost, time, performance, and reliability
- Optimize pipeline concurrency for performance and cost
- Design and implement a retention strategy for pipeline artifacts and dependencies
- Migrate a pipeline from classic to YAML in Azure Pipelines