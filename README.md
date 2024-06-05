# Ruby on Rails Todo Application


## Ruby Setup

```
brew install ruby-install chruby
```

Add lines to .zshrc
```
### ~/.zshrc~
# enable chruby
source /usr/local/share/chruby/chruby.sh
source /usr/local/share/chruby/auto.sh
chruby ruby-3.3.0
```

```
ruby-install ruby 2.3.0

chruby 2.3.0
```

This is a todo app made with Ruby on Rails

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
bundle install --without production
```

Next, migrate the database:

```
rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
rails server
```
