# EGI Website tests

[![Build Status](https://travis-ci.org/EGI-Foundation/EGI-website-tests.svg?branch=master)](https://travis-ci.org/EGI-Foundation/EGI-website-tests)

These are behaviour-driven tests for the [EGI website](https://egi.eu), using [cucumber](https://docs.cucumber.io/).
The [features](/features) directory contains user stories and features that the website should have.
The features are written in the [gherkin](https://docs.cucumber.io/gherkin/) language, using plain human language.
Tests are implemented in ruby, and found in the 

## How to use this repo

If you have a scenario or feature which should be present on the website, it should come here.
You should be able to run the tests on your local setup in order to test your proposed feature.
This will require an installation of cucumber. Assuming you already have a working ruby setup with bundler, do

```
bundle install
```
