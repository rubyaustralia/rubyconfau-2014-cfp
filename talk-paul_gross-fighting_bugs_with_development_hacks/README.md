# Fighting Bugs with Development Hacks

Bugs are an inevitable part of software development. We do our best to write higher quality software, but we never escape releasing bugs into production.

Since we can't fully remove bugs, this talk will cover strategies, hacks and monkey patches in Ruby (and Rails) to prevent bugs from becoming a big disaster. I'll use examples from [Braintree](https://www.braintreepayments.com/), a payments company where mistakes cost real money, such as:

- Ensuring that queries are scoped properly
- Runtime consistency checks on data
- Sanity specs to catch problems at development time

## Paul Gross

Paul Gross is a developer working at [Braintree](https://www.braintreepayments.com/). Braintree helps businesses accept credit card payments online with great development tools and first class support. Before Braintree, Paul worked at [ThoughtWorks](http://www.thoughtworks.com/), a global consultancy, building custom software in many languages, including Java, .NET, Python and Ruby. Paul has worked in software development and delivery for over 10 years. 

![Profile picture](https://secure.gravatar.com/avatar/a6cbdd6473de1af38ef1d8e01588ae7e?s=200)

- [My website](http://www.pgrs.net)
- [My twitter](https://twitter.com/pgr0ss)

I have not done this talk before, but it will incorporate pieces from my blog post on the same topic: https://www.braintreepayments.com/braintrust/development-hacks-to-prevent-mistakes

Last year at [RubyConf Australia](http://www.rubyconf.org.au), I gave a talk on High Availability at Braintree:
- [Slides](http://www.pgrs.net/wp-content/uploads/2013/02/rubyconf_australia_high_availability.pdf)
- [Video](http://vimeo.com/61255649)

I also gave this talk on High Availbility at Braintree at [Surge](http://surge.omniti.com/2013), [Strangeloop](https://thestrangeloop.com/), and [Velocity](http://velocityconf.com/velocityny2013/).
