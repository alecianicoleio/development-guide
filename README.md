# ![Elevator Up](http://elevatorup.com/img/eulogo-87259dc5.png) Development Guide
This guide is used to define our development practices. This will be an evolving document as we continue to evolve as a company.

> In order to maintain a level of sanity with our code, we need to make sure that the tests are always passing. Due to this, if you break the test coverage, it needs to be fixed before you sign off for the day. This helps keep everyone in a place where they can be productive, instead of coming in to a broken repository.

If you break a build, you have to fix it before you go home. If you're worried about this, do not push commits at the end of the day.

1. [Git](#git)
2. [Ruby / Rails](#ruby-rails)
3. [Continuous Integration](#continuous-integration)
4. [Code Review](#code-review)

## Git
We use Git for version control on all of our projects. In order to keep a level of consistency in our usage, we use [Git Flow](https://www.youtube.com/watch?v=xvgCvT9xX7A) as a basis for our branching and commits.

Write good commit messages. Take a look at [5 Useful Tips For A Better Commit Message](https://robots.thoughtbot.com/5-useful-tips-for-a-better-commit-message) in order to help write better commit messages.

## Ruby / Rails
See the [Elevator Up Ruby / Rails Development Guide](ruby_rails.md)

## Front End
See the [Elevator Up Front End Development Guide](front_end.md)

## Continuous Integration
We are currently using [Travis](https://travis-ci.com/) for Continuous Integration.

## Code Review
We are currently using [Code Climate](https://codeclimate.com) for automated code reviews.
