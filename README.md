# Testing Relationships Between Classes

## What it is about
This was an exercise during Week 2 at Makers to help learn mocking and isolate unit tests.
It helped me understand why use doubles in unit tests, and how to use them.

## Quickstart

Clone, then:

```bash
$ bundle install
$ rspec
# You should see four pending tests
```

## Instructions

Fill in the four tests in `spec/secret_diary_spec.rb`.

Don't:

* Change `secret_diary.rb`
* Add any new files
* Create any new classes

Do:

* Use `double` — [Reference docs here](https://relishapp.com/rspec/rspec-mocks/v/3-5/docs/basics/test-doubles)
* Use `expect(...).to receive(...)` [Reference docs here](https://relishapp.com/rspec/rspec-mocks/v/3-5/docs/basics/expecting-messages)

