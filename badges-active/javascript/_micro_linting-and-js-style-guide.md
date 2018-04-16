# JavaScript - Linting & JS Style Guide

-----

Est. to complete: ~1h

## Goal
- You have demonstrated the basic foundations in JavaScript Linting & the JS Style Guide.
- You should know about linting rules, leading commas, hoisted vars and the like.
- You should be able to explain the difference between prettier and eslint. 
  - Why is every rule fixable in prettier and not eslint?
  - Which is more customizable?
  - Are they interchangeable, or should they be used in conjunction?


-----

## Intro

>Code linting is a type of static analysis that is frequently used to find problematic patterns or code that doesn't adhere to certain style guidelines. - [ESLint: About](http://eslint.org/docs/about/)

>All code in any code-base should look like a single person typed it, no matter how many people contributed. - [Idiomatic JS](https://github.com/rwaldron/idiomatic.js/)

There are two main ways we enforce consistent code. Code Linting and Language Style Guides. FamilySearch suggests you use ESLint and adopt at least the default ruleset in our FS .eslintrc file. You may be more aggressive as you see fit. We also have a JS style guide, which the web developers have created by agreeing on a short set of guidelines and conventions we would all like to see in our code.

-----


## Suggested Assignment(s)
Choose Two (or more):

1) Implement ESLint in your editor
  - [ ] [Grab the FS .eslintrc config repo](https://github.com/fs-webdev/eslint-config-frontier)
  - [ ] Install it in your project
  - [ ] Make your own .eslintrc config file in the root of your project that extends to FS .eslintrc file. See:  [http://eslint.org/docs/user-guide/configuring#extending-configuration-files](http://eslint.org/docs/user-guide/configuring.html)
  - [ ] Make your own .eslintignore file, and configure it to fit your project. See: [http://eslint.org/docs/user-guide/configuring#ignoring-files-and-directories](http://eslint.org/docs/user-guide/configuring.html)
  - [ ] Install ESLint plugin for your editor
  - [ ] Demonstrate some code you've fixed after using ESLint

2) Implement ESLint in your dev-time CI tests
  - [ ] [Grab the FS .eslintrc config repo](https://github.com/fs-webdev/eslint-config-frontier)
  - [ ] Install it in your project
  - [ ] Make your own .eslintrc config file in the root of your project that extends to FS .eslintrc file. See:  [http://eslint.org/docs/user-guide/configuring#extending-configuration-files](http://eslint.org/docs/user-guide/configuring.html)
  - [ ] Make your own .eslintignore file, and configure it to fit your project. See: [http://eslint.org/docs/user-guide/configuring#ignoring-files-and-directories](http://eslint.org/docs/user-guide/configuring.html)
  - [ ] Make a way to run ESLint against your project files on changes
  - [ ] Demonstrate some code you've fixed after using ESLint

3) Implement ESLint in your deploy-time tests
  - [ ] [Grab the FS .eslintrc config repo](https://github.com/fs-webdev/eslint-config-frontier)
  - [ ] Install it in your project
  - [ ] Make your own .eslintrc config file in the root of your project that extends to FS .eslintrc file. See:  [http://eslint.org/docs/user-guide/configuring#extending-configuration-files](http://eslint.org/docs/user-guide/configuring.html)
  - [ ] Make your own .eslintignore file, and configure it to fit your project. See: [http://eslint.org/docs/user-guide/configuring#ignoring-files-and-directories](http://eslint.org/docs/user-guide/configuring.html)
  - [ ] Set a ESLint script to run somewhere in the deploy workflow, and halt it on a failure


-----


## Suggested Study

### Web
- [FS JS Style Guide](https://github.com/fs-webdev/eslint-config-frontier)
- [FS JS Style linters: eslintrc](https://github.com/fs-webdev/eslint-config-frontier)
- [Idiomatic JS Style Guide](https://github.com/rwaldron/idiomatic.js/)
- [http://eslint.org/docs/user-guide/configuring](http://eslint.org/docs/user-guide/configuring.html)
- [http://eslint.org/docs/user-guide/integrations](http://eslint.org/docs/user-guide/integrations.html)
- [Learning JavaScript](https://github.com/iangilman/learning-javascript)
- [Prettier Announcement](http://jlongster.com/A-Prettier-Formatter)

### Tools
- [http://eslint.org/](http://eslint.org/)
- [Prettier - Opinionated Code Formatter](https://github.com/prettier/prettier)

-----

*Is this badge missing something? Submit a PR and review it with a master in this category*
