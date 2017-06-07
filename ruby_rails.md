# ![Elevator Up](http://elevatorup.com/img/eulogo-87259dc5.png)  Ruby / Rails Development Guide

1. [Common Gems](#common-gems)
2. [Ruby Style Guide](#ruby-style-guide)
3. [Rails Style Guide](#rails-style-guide)
4. [RubuCop](#rubocop)

### Common Gems
In order to try and keep a consistency between projects, this is a list of some of our preferred gems. This is by no means a definitive list, just what we prefer to use for certain situations.

#### Authentication
- [devise](https://github.com/plataformatec/devise)

#### Authorization
- [pundit](https://github.com/elabs/pundit)

#### Development
- [better_errors](https://github.com/charliesome/better_errors) (Better error pages)
- [bullet](https://github.com/flyerhzm/bullet) (Detect N+1 queries)
- [pry-rails](https://github.com/rweng/pry-rails) (Alternative IRB shell)
- [rubocop](https://github.com/bbatsov/rubocop) (Code Analyzer)

#### Ecommerce
- [solidus](https://github.com/solidusio/solidus) (Rails ecommerce system)

#### Forms
- [cocoon](https://github.com/nathanvda/cocoon) (Nested Forms)
- [simple_form](https://github.com/plataformatec/simple_form) (Form Builder DSL)

#### Pagination
- [kaminari](https://github.com/amatsuda/kaminari)

#### Testing
- [rspec](https://github.com/rspec/rspec) and [rspec-rails](https://github.com/rspec/rspec-rails) (Testing Framework)
- [shoulda_matchers](https://github.com/thoughtbot/shoulda-matchers) (Common matchers for testing)
- [factory_girl](https://github.com/thoughtbot/factory_girl) and [factory_girl_rails](https://github.com/thoughtbot/factory_girl_rails) (Create factories to use in tests)

### Ruby Style Guide
We are currently using the default [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide) supplied by [RuboCop](https://github.com/bbatsov/rubocop).
As we move forward, we may fork this style guide and update it to match our coding style.

### Rails Style Guide
We are currently using the default [Rails Style Guide](https://github.com/bbatsov/rails-style-guide) supplied by [RuboCop](https://github.com/bbatsov/rubocop).
As we move forward, we may fork this style guide and update it to match our coding style.

### RuboCop
We are using [RuboCop](https://github.com/bbatsov/rubocop) to analyze our code and make sure it meets our standards (listed in the [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide) and [Rails Style Guide](https://github.com/bbatsov/rails-style-guide).

A template for our Rubocop config can be found [here](templates/rails/.rubocop.yml).
