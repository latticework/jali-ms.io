<!-- markdownlint-disable first-header-h1 first-line-h1 -->
<!-- cSpell:ignore  -->

<!-- markdownlint-disable ul-style no-inline-html -->

> **View our API Documentation**<br>
> - [v0.1.0](./reference/0.1.0/)

<!-- markdownlint-enable ul-style no-inline-html -->


### **Jali** is

- **specification-driven** permitting consumer driven contracts and
  multi-version management
- **serverless** so you can write just your routines and run using any
  and all configurable platforms
- where the **microservice** is the unit of development, delivery and
  management
- a full multitenant, partitionable **DevOps** platform because modern
  microservice delivery is continuous
- an extensible, polyglot **framework** providing circuit breaking and
  self-documenting APIs and explicit routine services
- an **infrastructure** pluggable for many major microservice platforms
  (eventually...)

### Demonstrated Practices and Technologies

**Jali** also demonstrates state of the art development practices and
technologies.

#### Project Management

- **[GitHub][github-wiki]**-integrated project management using [ZenHub][zen-hub]
  - [Kanban][kanban-wiki]-style project board using story points
  - [Scrum][scrum-wiki]-supporting [milestones][jali-repo-milestones]
    with [burn down charts][burn-down-charts]

#### Compliance Management

- Tools that integrate with GitHub's protected branch
  [status checks][github-status-check] to document and enforce that
  software meets compliance checks. Example: PR [#88][status-check-example]
  - Automated Contributor License Agreement (CLA) compliance
    - [CLA assistant][cla-assistant-example]
  - Package license and security compliance
    - [Dependency CI][dependency-ci-example]
    - [VersionEye][version-eye-example] (still working on white-listing)
  - Code quality compliance enforcement using static code analysis
    (includes ignored errors, duplicate code, code complexity and linting)
    - [bitHound][bit-hound-example]

#### Continuous Integration

- GitHub PR integrated Continuous Integration (CI) service
  - [SemaphoreCI][semaphore-ci-example]

[bit-hound-example]: https://www.bithound.io/github/latticework/jali/6be101682f84865e291f948447b2a4a93bd768f8/files
[burn-down-charts]: https://www.zenhub.com/blog/burndown-charts-in-github/
[cla-assistant-example]: https://cla-assistant.io/latticework/jali?pullRequest=88
[dependency-ci-example]: https://dependencyci.com/github/latticework/jali/builds/141
[github-status-check]: https://help.github.com/articles/enabling-required-status-checks/
[github-wiki]: https://en.wikipedia.org/wiki/GitHub
[jali-repo-board]: https://github.com/latticework/jali#boards
[jali-repo-milestones]: https://github.com/latticework/jali/milestones
[jali-repo-issue-template]: https://github.com/latticework/jali/blob/master/.github/ISSUE_TEMPLATE.md
[kanban-wiki]: https://en.wikipedia.org/wiki/Kanban
[scrum-wiki]: https://en.wikipedia.org/wiki/Scrum_(software_development)
[semaphore-ci-example]: https://semaphoreci.com/latticework/jali/branches/master/builds/3
[status-check-example]: https://github.com/latticework/jali/pull/88#event-923613864
[version-eye-example]: https://www.versioneye.com/pullrequests/587be84e2ef9ab000e000a39
[zen-hub]: https://www.zenhub.com/
