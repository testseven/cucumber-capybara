# Cucumber

Getting Started
===============

[Cucumber Capybara](https://github.com/fernandosqa/cucumber-capybara) (Bundler, Cucumber, Capybara, Siteprism, RSpec)

### Installation

* Install Ruby 2.3.1 from https://www.ruby-lang.org/en/downloads/ or via RVM (https://rvm.io/).
* Install `.Ruby >2.3.0`_
* Install `Firefox` only `48` version
* Install `Chrome` and `chromedriver`
* Install `Bundler`
```
gem install bundler
```
* Install `Gems`
```
bundle install
```
  
### Basic Guide

* Run tests with `poltergeist`
```    
bundle exec cucumber -p poltergeist
```
* Run tests with `firefox`
```
bundle exec cucumber -p firefox
```
* Run tests with `chrome`
```
bundle exec cucumber -p chrome
```
* HTML Report
```
bundle exec cucumber -p html_report
```
* JSON Report for CI
```
bundle exec cucumber -p json_report
```
