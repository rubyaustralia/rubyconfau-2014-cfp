# Curly — Refactoring the view layer

While most parts of Rails have been thoroughly overhauled during the past few years, one part has stubbornly refused improvement. The view layer is still by default using ERB to transform your app’s objects into HTML. Though HAML has gained a lot of traction, it is not a fundamental shift away from ERB, but rather a preference for putting HTML in your Ruby rather than the other way around.

More recent efforts in the realm of JavaScript have produced Mustache and its ambitious younger brother, Handlebars. While these are more radical in their attempt to separate structure and logic, they still do not feel like native Rails code.

While trying to solve a seemingly unrelated problem we discovered a design that suddenly enabled us to move past the limitations of ERB. Though different only in subtle ways, it struck just the right balance between integration with Rails and separation of concerns. We called it Curly.

I will show how we use the same old OO techniques that you already know to clean up our views, making them less prone to bugs, more readable, and more reusable.

I’ll also show how a seemingly small change of our conceptual model enabled us to add advanced behavior to our view layer without ending with an unmaintainable mess.

Curly is open source and available at http://github.com/zendesk/curly

## Daniel Schierbeck

Daniel Schierbeck has been programming in Ruby since 2005 after completing level 99 in PHP and figuring out there was no prize to win after all.

He studied Computer Science at the University of Copenhagen, where he primarily spent his time trying to avoid writing C++. He got into Concurrent Sequential Processes before it became cool, and wrote a Ruby implementation called Minx for his bachelor thesis. As with all academic code, it is used by no one.

He currently pumps out pull requests for a living at Zendesk, a San Francisco
based Customer Support Software SaaS company.

![Profile
picture](https://0.gravatar.com/avatar/a9cc05e6a7866e5fa9a7d107b5070174?d=https%3A%2F%2Fidenticons.github.com%2Fc6862d63b17d713ee14f3a405d9fde77.png&s=420)

- [@dasch on Twitter](https://twitter.com/dasch)
- [@dasch on GitHub](https://github.com/dasch)
