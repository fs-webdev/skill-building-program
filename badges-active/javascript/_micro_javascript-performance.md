# JavaScript - JavaScript Performance  [Micro Badge]

-----

Est. to complete: 4h

## Goal
- You have demonstrated the basic foundations of JavaScript Performance
- You should have some experience with when the proper time to optimize JavaScript is, how to audit and profile JavaScript in the browser, some things that are usually slow in JavaScript, how to accurately time things in JavaScript, and algorithmic complexity


-----

## Intro

> Simple coding... Algorithms! Math! Why can't we make what we want to make... the way we want to make it?!?! - [Stanley Tucci in Transformers: 4](https://youtu.be/yNJbAJcVCGc?t=16s)


-----


## Suggested Assignment(s)

Choose one:

1) Make a creative project that demonstrates the following:
- [ ] When it's an appropriate time to micro-optimize
- [ ] Perform a JavaScript profile, and determine where in a script the most time and memory is used
- [ ] Fix some known expensive JavaScript operations
- [ ] Use JavaScript micro-timing to accurately record how long a function takes
- [ ] Show the "Big-O" complexity of at least two different operations in JavaScript
- [ ] Show how one of the previous two operations might be optimized to achieve a lower algorithmic complexity
- [ ] Show the effect of inner loops on JavaScript performance, and how to optimize them

2) Demonstrate how you've done all of #1 in your work or side-work

3) Something else creative that proves you are totally legit in this topic


-----


## Suggested Study

### Web

#### Warning: Premature Optimization and Micro-optimization Theater 

  - [The Sad Tragedy of Micro-Optimization Theater - CodingHorror](http://blog.codinghorror.com/the-sad-tragedy-of-micro-optimization-theater/)
  - [Micro-Optimization in JavaScript - Google Developer Guide](https://developers.google.com/web/fundamentals/performance/rendering/optimize-javascript-execution#avoid_micro-optimizing_your_javascript)
  - [Program Optimization - Wikipedia](https://en.wikipedia.org/wiki/Program_optimization#When_to_optimize)

#### Auditing / Profiling

  - [Get Started With Analyzing Runtime Performance - Google Developer Guide](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/)
  - [Analyze Runtime Performance in Chrome Dev Tools - Google Developer Guide](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/)
  - [Easy Profiling for Node.js Applications - NodeJS](https://nodejs.org/en/docs/guides/simple-profiling/)

#### Fixing things known to be expensive in JavaScript

  - [High-Performance JavaScript - Nicholas Zakas](http://www.slideshare.net/nzakas/high-performance-javascript-webdirections-usa-2010/)
  - [What is the best way to run expensive code in JavaScript without freezing up the UI - Quora](https://www.quora.com/What-is-the-best-way-to-run-expensive-code-in-JavaScript-without-freezing-up-the-UI?share=1)
  - [Function Call Profiling - E John](http://ejohn.org/blog/function-call-profiling/)
  - [Also See: Skill-Building-Program: Rendering Performance micro-badge](https://github.com/fs-webdev/skill-building-program/blob/master/badges-active/performance/_micro_rendering-performance.md)

#### Timing things

- [User Timing (performance.now)](http://www.html5rocks.com/en/tutorials/webperformance/usertiming/)
- [Performance.now - MDN](https://developer.mozilla.org/en-US/docs/Web/API/Performance/now)
- [process.hrtime - NodeJS](https://nodejs.org/api/all.html#all_process_hrtime)
- [Date.getTime - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/getTime)

#### Algorithmic Complexity

  - [Cyclomatic Complexity - Wikipedia](https://en.wikipedia.org/wiki/Cyclomatic_complexity)
  - [Complexity - Discrete](http://discrete.gr/complexity/)
  - [Time Complexity Algorithm (in PHP)](http://www.sitepoint.com/time-complexity-algorithms/)
  - [Big-O Cheat-Sheet](http://bigocheatsheet.com/)
  - [Big-O Algorithm Examples in JavaScript - BrandonCode](http://www.bradoncode.com/blog/2012/04/big-o-algorithm-examples-in-javascript.html)


-----


### Books

- [High Performance JavaScript (Build Faster Web Application Interfaces)](http://amzn.com/059680279X)
- [Pro JavaScript Performance: Monitoring and Visualization (Expert's Voice in Web Development) ](http://amzn.com/1430247495)
- [Mastering JavaScript High Performance](http://www.amazon.com/Mastering-JavaScript-High-Performance-Adams/dp/1784397296%3FSubscriptionId%3DAKIAILSHYYTFIVPWUY6Q%26tag%3Dduckduckgo-d-20%26linkCode%3Dxm2%26camp%3D2025%26creative%3D165953%26creativeASIN%3D1784397296)


-----


### Tools

- [JSPerf](https://jsperf.com/)
- [UnJank](https://www.npmjs.com/package/unjank)

-----

  *Is this badge missing something? Submit a PR and review it with a master in this category*








