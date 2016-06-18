## App Setup
* rails new _____ --skip-turbolinks --database=postgresql

## Gemfile
* gem 'bcrypt'
* inside :development, :test: 'better_errors', 'binding_of_caller', 'pry-rails', 'annotate'
* bundle install

## NPM
* npm init --yes
* npm install --save
  * webpack
  * react
  * react-dom
  * react-router
  * flux
  * babel-core
  * babel-loader
  * babel-preset-react


## Frontend

* Frontend folder
* [appname].jsx (entry file)
* fluxes (Flux Entry Setup Snippet)
* folders
  * actions
  * components
  * constants
  * dispatcher
  * misc
  * stores
  * util


## Webpack
* webpack.config.js
* webpack (Webpack Setup Snippet)
* webpack --watch

## Routes
* root to: 'static_pages#root'

## PostgreSQL
* rake db:create

## Controller

* rails g controller StaticPages

```ruby
class StaticPagesController < ApplicationController
  def root
  end
end
```

## Views

* create static_pages folder
* create root.html file
 ```html
<div id="root"></div>
```

## Git
* git init
* .gitignore --> node_modules/, bundle.js, bundle.js.map
* add -A, commit -m "initial commit"
