# Ruby sample test project

### Installation requirements

* Ruby 2.5.7
* Bundler gem
* Rspec gem

To install ruby:

To install many version of ruby, you can use RVM or RBEnv, for this tutorial we are going to use [rbenv](https://github.com/rbenv/rbenv#installation)

```
rbenv install 2.5.7
gem install bundler 
bundle install --path .bundle
```

To run the test code

```
bundle exec rspec
```

To production code that we are going to work is inside the `lib` folder.
The testing code for testing purpose is held inside the `spec` folder.