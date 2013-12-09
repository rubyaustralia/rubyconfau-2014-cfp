# Modern Concurrency Practices in Ruby

So you think that concurrency is a subject lost in the Ruby world?
That it's not practical because of the GVL? That the concurrency
paradigm that's bundled with Ruby (a.k.a threading) is not the best
way to do concurrency? Or that you already have multi-processes and
don't need multi-threading concurrency.

Think again. The Ruby concurrency story has advanced a lot in the last
couple of years. Have you heard of people talking about actor-based
concurrency, using futures, Software Transactional Memory etc. and
want to know more about those?

This talk is a primer on these different paradigms of concurrency,
briefly touching on the traditional threads-based model, but focusing
more on modern paradigms like actors/futures/STM, with examples and
live-demos. Along the way we'll also see what's already possible in
Ruby (and in other implementations like JRuby and Rubinius, using gems
like Celluloid and friends).

PS: To add some variety, I'll employ the widely recognized but rarely
heard (at Rubyconf AU) Indian accent.

## Arnab Deka

Arnab is a Senior Software Engineer at LivingSocial (working remotely
from Bangalore), and has been writing Ruby (i.e. having fun) since
2008. Prior to this, Arnab was with AWS at Amazon.com in Seattle.

![Profile picture](https://raw.github.com/arnab/rubyconfau-2014-cfp/cfp/arnab-modern-concurrency-in-ruby/talk-arnab_deka-modern_concurrency_practices_in_ruby/profile_picture.jpg)

- [http://arnab-deka.com/](http://arnab-deka.com/)
- [@arnab_deka](https://twitter.com/arnab_deka)
- [github/arnab/](https://github.com/arnab/)

Past talk slides:

+ [Ruby vs The World](http://slid.es/arnab_deka/ruby-vs-the-world): at
  RailsGarden Bangalore, a Ruby/RoR workshop for students, in Aug'13.
+ [Remote Pair Programming](http://slid.es/arnab_deka/pairwithme-remotely):
  at Bangalore RUG meetup in Oct'13.
