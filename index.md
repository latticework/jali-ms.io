<!-- markdownlint-disable first-header-h1 first-line-h1 -->
<!-- cSpell:ignore cirkel -->

<!-- markdownlint-disable ul-style no-inline-html -->

> **View our API Documentation**<br>
> - [v0.1.0][jali-site-api]

<!-- markdownlint-enable ul-style no-inline-html -->


## **Jali** is

> - **specification-driven** permitting consumer driven contracts and
>   multi-version management
> - **serverless** so you can write just your routines and run using any
>   and all configurable platforms
> - where the **microservice** is the unit of development, delivery and
>   management
> - a full multitenant, partitionable **DevOps** platform because modern
>   microservice delivery is continuous
> - an extensible, polyglot **framework** providing circuit breaking and
>   self-documenting APIs and explicit routine services
> - an **infrastructure** pluggable for many major microservice platforms
>   (eventually...)

## Demonstrated Practices and Technologies

**Jali** also demonstrates state of the art development practices and
technologies.

### Communication

- [Team site][latticework-site]
- [Team blog][latticework-blog] and [twitter feed][latticework-twitter]
  that communicate direction and announce changes.
- [Project site][jali-site] with integrated [api documentation][jali-site-api]
  - Includes innovative use of the TypeScript compiler to build, test,
    and generate [example documentation][jali-site-api-example] that are
    known to function.

[jali-site]: /
[jali-site-api]: ./reference/0.1.0/manual/index.html
[jali-site-api-example]: http://jali-ms.io/reference/0.1.0/manual/example.html
[latticework-blog]: 
[latticework-blog-principles]
[latticework-site]
[latticework-twitter]

### Project Management

- List of [architectural principles][latticework-blog-principles]
  governing development practices
- [GitHub][github-wiki]-integrated project management using [ZenHub][zen-hub]
  - [Kanban][kanban-wiki]-style project board using story points
  - [Scrum][scrum-wiki]-supporting [milestones][jali-repo-milestones]
    with [burn down charts][burn-down-charts]
- Detailed GitHub-integrated [issue template][jali-repo-issue-template]
  with clear [instructions][jali-repo-issue-instructions]

### Compliance Management

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

### DevOps

#### Developer Experience (DX)

- Use of Configuration Management tools to provide consistent
  development environment
  - Only [Vagrant][vagrant], [VirtualBox][virtual-box], and [Chef][chef]
    tools need to installed to stand up a consistent graphical [Ubuntu][ubuntu-wiki]
    16.04 development environment across all operating systems.
  - Guest development environment provides the full range of tools
    needed, including Docker, NodeJS, Visual Studio Code, sphinx for
    Jekyll-based documentation, etc.

#### Continuous Integration / Continuous Delivery (CI/CD)

- GitHub PR integrated Continuous Integration (CI) service ensures only
  successfully build code gets merged into the master branch
  - [SemaphoreCI][semaphore-ci-example]

### NodeJS Development Techniques

- [monorepo][monorepo-turf]-style projects that use
  [scoped npm packages][jali-npm-user]
  - Like [angular][angular-npm-org]
  - Supports projects using TypeScript, ES6 modules, or NodeJS-style modules
- `npm` as a [task runner][npm-build]
- [TypeScript 2.1][typescript] ([wikipedia][typescript-wiki]) adds
  optional static typing to JavaScript
- [EcmaScript 2017+][ecmascript] ([wikipedia][ecmascript-wiki]) The maturing
  JavaScript language
  - See [ECMASCRIPT-PROPOSALS.md][jali-repo-proposals] for what
    proposals are implemented and supported by Jali
  - [esdoc][esdoc] documentation generator
  - [eslint] EcmaScript compliant linter
- [webpack 2][webpack] ([wikipedia][webpack-wiki]) NodeJS module loader
- [Babel 6][babel] JavaScript parser and transpilation platform
- [AVA][ava] Concurrent JavaScript test framework for EcmaScript + Babel
- [istanbul][istanbul] JavaScript code coverage tool

[ava]: https://github.com/avajs/ava
[angular-npm-org]: https://www.npmjs.com/~angular
[babel]:https://babeljs.io/
[bit-hound-example]: https://www.bithound.io/github/latticework/jali/6be101682f84865e291f948447b2a4a93bd768f8/files
[burn-down-charts]: https://www.zenhub.com/blog/burndown-charts-in-github/
[chef]: https://github.com/latticework/jali/blob/master/%5Bwiki%5D%5BChefWiki%5D
[cla-assistant-example]: https://cla-assistant.io/latticework/jali?pullRequest=88
[dependency-ci-example]: https://dependencyci.com/github/latticework/jali/builds/141
[ecmascript]: https://github.com/tc39/proposals
[ecmascript-wiki]: https://en.wikipedia.org/wiki/ECMAScript
[esdoc]: https://github.com/latticework/jali/blob/master/integrated%20by%20Jali
[eslint]: http://eslint.org/
[github-status-check]: https://help.github.com/articles/enabling-required-status-checks/
[github-wiki]: https://en.wikipedia.org/wiki/GitHub
[istanbul]: https://github.com/gotwarlost/istanbul
[jali-npm-user]: https://www.npmjs.com/~jali-ms
[jali-repo-board]: https://github.com/latticework/jali#boards
[jali-repo-milestones]: https://github.com/latticework/jali/milestones
[jali-repo-proposals]: https://github.com/latticework/jali/blob/master/ecmascript-proposals.md
[jali-repo-issue-instructions]: https://github.com/latticework/jali/blob/master/ISSUE-TEMPLATE-INSTRUCTIONS.md
[jali-repo-issue-template]: https://github.com/latticework/jali/blob/master/.github/ISSUE_TEMPLATE.md
[kanban-wiki]: https://en.wikipedia.org/wiki/Kanban
[monorepo-turf]: http://www.macwright.org/2016/07/08/lerna-npm-organizations-new-wave-modularity.html
[npm-build]: https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/
[scrum-wiki]: https://en.wikipedia.org/wiki/Scrum_(software_development)
[semaphore-ci-example]: https://semaphoreci.com/latticework/jali/branches/master/builds/3
[status-check-example]: https://github.com/latticework/jali/pull/88#event-923613864
[typescript]: https://blogs.msdn.microsoft.com/typescript/2016/07/11/announcing-typescript-2-0-beta/
[typescript-wiki]: https://en.wikipedia.org/wiki/TypeScript
[ubuntu-wiki]: https://en.wikipedia.org/wiki/Ubuntu
[vagrant]: https://github.com/latticework/jali/blob/master/%5Bwiki%5D%5BVagrantWiki%5D
[version-eye-example]: https://www.versioneye.com/pullrequests/587be84e2ef9ab000e000a39
[virtual-box]: https://github.com/latticework/jali/blob/master/%5Bwiki%5D%5BVirtualBoxWiki%5D
[webpack]: https://gist.github.com/sokra/27b24881210b56bbaff7
[webpack-wiki]: https://en.wikipedia.org/wiki/Webpack
[zen-hub]: https://www.zenhub.com/
