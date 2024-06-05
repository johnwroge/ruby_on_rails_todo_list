# ruby_on_rails_todo_list

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
ruby-install --latest

or

ruby-install ruby
```

```
rails -v
```
//ruby -v ruby 3.3.0 (2023-12-25 revision 5124f9ac75) [x86_64-darwin21]

```
gem install rails -v 7.2.0.beta1
```


## Project

```
rails new todolist --css bootstrap --esbuild
```

```
cd todolist/
```

```
bundle add devise simple_form
```

```
rails g simple_form:install --bootstrap

```

```
rails g devise:user
```

```
rails g devise User
```

```
rails g devise:views
```

```
rails g scaffold task title body:text completed boolean user:references
```



```
rails s
```

