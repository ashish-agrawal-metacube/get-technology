# GET Technology Guidelines

This document describes the proposed technology guidelines in Graduate Engineering Trainee Project.

If you have ***any questions*** please
[***ask***](https://github.com/dwyl/get-technology-guidelines/issues)

## Overview
This document is the guide we use for developing apps in GET project. We encourage you to set up one that works for your own team. Feel free to peruse.

Don't violate a guideline without a good reason. A reason is good when you can convince a teammate.

Feel free to [***contribute***](https://guides.github.com/activities/contributing-to-open-source/#contributing)

### Dependencies <small>(*technologies we trust*)</small>

+ [**ruby**](https://www.ruby-lang.org/en/) - A dynamic, open source programming language with a focus on simplicity and productivity. It has an elegant syntax that is natural to read and easy to write.
+ [**Ruby on Rails**](https://www.ruby-lang.org/en/) - Ruby on Rails makes it much easier and more fun. It includes everything you need to build fantastic applications.
+ [**AngularJS**](https://angularjs.org/) - AngularJS lets you write client-side web applications as if you had a smarter browser. It automatically synchronizes data from your UI (view) with your JavaScript objects (model) through 2-way data binding.
+ [**Bootstrap**](http://getbootstrap.com) - The most popular HTML, CSS, and JavaScript framework for developing responsive, mobile first projects on the web. Bootstrap is a sleek, intuitive, and powerful front-end framework for faster and easier web development.
+ [**MySQL**](http://www.mysql.com/) - the most widely used open-source RDBMS.
+ [**Heroku**](http://www.heroku.com) - Heroku is a cloud Platform-as-a-Service (PaaS) supporting several programming languages. It has Powerful platform, unparalleled ecosystem. It’s one of the best platform for building with modern architectures, innovating quickly, and scaling precisely to meet demand.


### Development Dependencies

We *carefully* select and only use *well-maintained* "*pure*" JavaScript modules
in our development toolchain:

+ [**rspec**](http://rspec.info) for testing: 
+ **simplecov** for Code Coverage. [**help**](https://github.com/gbohra/get-technology-guidelines/blob/master/learn-simplecov/)
+ **Pre-commit** for ensuring all commits pass strict quality checks before being pushed to GitHub. [**help**](https://github.com/gbohra/get-technology-guidelines/blob/master/learn-pre-commit/)
+ [**CodeClimate**](https://codeclimate.com/) for tracking code quality.
+ [**CodeCov**](https://codecov.io/) for *detailed* test/code coverage stats.
+ [**YARD**](http://www.rubydoc.info/gems/yard/file/docs/GettingStarted.md) for code comment guidelines and document generation.

### Continuous Integration

We use and *recommend* Travis-CI for Continuous Integration (CI).
If you or anyone on your team are *new* to Travis-CI,
checkout our beginners [guide](https://github.com/gbohra/get-technology-guidelines/tree/master/travis)
<br />
<br />
