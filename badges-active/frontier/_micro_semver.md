# Frontier - Consuming & Releasing using SemVer [Micro Badge]

## Goals:

* You have demonstrated some foundational knowledge in using SemVer correctly.
* You should be aware of several of the common practices and techniques used with SemVer in NPM

## Intro

Given a version number MAJOR.MINOR.PATCH, increment the:

* MAJOR version when you make incompatible API changes
* MINOR version when you add functionality in a backwards-compatible manner
* PATCH version when you make backwards-compatible bug fixes

## Suggested Assignment(s)

Choose one:

1. Demonstrate the following:

* What is the main contract of Semantic Versioning (SemVer)?
* What do the values in SemVer x.y.z represent?
* What should be the initial server value of any package?
* How do you initialize an npm package?
* What should the Major value of a non-production package be?
* How do you cut a release on GitHub?
* How should you best communicate your releases?
* When consuming a package, how do you "pin" to a major, minor, or hardcode to a patch?
* If you release an API change that can break consumers, what should the SemVer change look like?
* If you cut a release that breaks more than the SemVer change you indicated, how do you proceed?
* In `package.json` dependency versions, what do the `~` and `^` (tilde and caret) represent?
* In "Major version 0" (`0.y.z`), how does npm behave differently?
* Which is newer, `0.10.3` or `0.3.10`? (0.10.3)
* How do you specify ranges in package.json dependencies?
* What does `"lodash": "*"` do? Should you?
* How do you add an npm-published dependency in NPM?
* How do you add a github-hosted dependency in NPM?
* How do you semver-minor pin a github-hosted dependency in NPM? Which NPM versions support this?

* Demonstrate or explain how to install packages to dependencies or devDependencies sections via CLI, and what the difference is
* Demonstrate or explain how to install a specific version of a module via CLI

2. Demonstrate how you've done all of the tasks in the assignment above in your current work or side-projects

## Study

### Required

* https://nodesource.com/blog/semver-a-primer- https://semver.org/
* http://nodesource.com/blog/semver-tilde-and-caret/

### Optional

* https://www.npmjs.com/package/semver
* https://docs.npmjs.com/misc/semver
* https://semver.npmjs.com/
* https://www.sitepoint.com/semantic-versioning-why-you-should-using/
* https://docs.npmjs.com/files/package.json

---

_Is this badge missing something? Submit a PR and review it with a master in this category_
