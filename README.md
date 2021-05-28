# README

To get started with the app, clone the repo and then install the needed gems:
```
$ gem install bundler -v 2.2.17
$ bundle  config set --local without 'production'
$ bundle install
```
Next, migrate the database:
```
$ rails db:migrate
```
Finally, run the test suite to verify that everything is working correctly:
```
$ rails test
```
If the test suite passes, you'll be ready to run the app in a local server:
```
$ rails server
```