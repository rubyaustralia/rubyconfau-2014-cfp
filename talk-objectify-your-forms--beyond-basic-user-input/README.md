# Objectify Your Forms: Beyond Basic User Input

User input contains a lot of potential complexity. A simple CRUD form can turn into an
unmaintainable mess when we introduce `accepts_nested_attributes_for` to deal with associations,
validating first this model then that one, manually adding validation errors, and finally saving
the whole thing.

What if we could use good old object oriented design principles to make forms a pleasure to deal
with? Form objects give us a much simpler way to build any sort of form we want that is straight
forward to build, test, and maintain.

We will build a complicated form using the default Rails helpers, and then we’ll rebuild it with a
form object and let the audience decide which method they prefer.

## Danny Olson

Danny lives in San Francisco where he is a developer at Sharethrough. He fosters dogs, cooks, and complains about the weather.

![Profile picture](http://gravatar.com/avatar/0a2b39fe22075db9bd81367dc9cb1159.jpg?s=200)

- [My website](http://blog-dannyolson.herokuapp.com/)
