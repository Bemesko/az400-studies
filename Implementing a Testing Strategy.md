- Define testing goals and [[Key Performance Indicators]] to measure the effectiveness of the testing strategy

> Popular testing frameworks include [[JUnit]], [[NUnit]], [[MSTest]] for [Unit Tests](Unit%20Tests), [Selenium](Selenium), [[Cypress]] for [UI Testing](UI%20Testing), and [[JMeter]], [[Gatling]] for [Performance Tests](Performance%20Tests).

[Design and implement a comprehensive testing strategy - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/implement-pipeline-strategy/5-design-implement-comprehensive-test-strategy)

- Run automated tests for code changes on [[Continuous Integration]] [Builds](Builds) before generating [[Artifacts]] and generate reports. Use parallel jobs to optimize the CI Pipeline
- [[Continuous Deployment]] should deploy already tested code. Minimize risk using [[Blue Green Deployment]], [[Canary Release]], [[Feature Flags]]

- Monitor applications to track anomalies in real time