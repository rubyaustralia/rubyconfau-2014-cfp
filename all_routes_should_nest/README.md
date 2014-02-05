# All Routes Should Nest.

In your RESTful application, every concept that you treat as a Resource
is related to at least one other Resource. Which of these relationships
should have nested routes? This is not just a Web problem.

If you answered "just the ones I need", you're doing it wrong.
If you're thinking about your nested URLs, you're probably doing it wrong.

By analysing practical examples using the theory of conceptual graphs,
I'll show why RESTful API design needs a new approach. All concepts in
your application are inter-related, and every API should automatically
allow requests for nested data, traversing any of these relationships,
including to multiple levels of nesting.  You shouldn't have to explicitly
nest any resource. We use already colon-include in ActiveRecord, but we
need it in our APIs too. Using this approach, we can design a new
generation of simple but super-flexible APIs.

## Clifford Heath

Clifford Heath is an architect and software toolmaker with oodles
of experience in evolving software products for large enterprises.
Despite having an enterprise focus, most of his career has been in
startups, including being the principal inventor behind Australia's
first ever Internet startup (DotComDotAU). Clifford's scientific
work in semantic modeling of conceptual graphs has been recognised
and published internationally, and he is one of the longest-standing
members of the Australian Ruby community.

![Profile picture](https://raw.github.com/cjheath/rubyconfau-2014-cfp/master/all_routes_should_nest/profile_picture.jpg)

- [My website](http://dataconstellation.com)
- [My twitter](https://twitter.com/cliffordheath)
- [Past talk slides](http://dataconstellation.com/ActiveFacts/CQL%20Slides%202009.pdf)
- [Past talk video](http://dataconstellation.com/screencasts/CQL.shtml)
