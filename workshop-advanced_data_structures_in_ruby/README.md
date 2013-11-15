# Advanced Data Structures in Ruby

Most Rubyists reach for core structures to represent their data (e.g. `Array`
and `Hash`). These may be good choices for one-off scripts or basic
applications but most real-world applications would benefit from using more
advanced data structures.

We will start by implementing a singly linked list in Ruby. This will be
followed by a doubly linked list, working our way up to trees, heaps, and
priority queues. [Thread safe](https://github.com/headius/thread_safe) and
persistent data structures will also be covered.

As we implement each of these structures, we will discuss the theoretical
tradeoffs between them and run benchmarks to prove that they perform as
predicted by the theory.

## Erik Michaels-Ober

Erik is the author of popular Ruby libraries, including RailsAdmin, the Twitter
gem, and the `t` command-line utility. He was a 2010 Ruby Summer of Code
mentor, 2011 Google Summer of Code mentor, and 2011 Code for America fellow,
and 2013 Rails Girls Summer of Code coach. He works on solving large-scale
problems with advanced data structures at SoundCloud in Berlin.

![Erik Michaels-Ober](https://raw.github.com/sferik/rubyconfau-2014-cfp/workshop-advanced_data_structures_in_ruby/workshop-advanced_data_structures_in_ruby/erik.jpg)

- [Erik's GitHub](https://github.com/sferik)
- [Erik's Twitter](https://twitter.com/sferik)
- [Past talk slides](https://speakerdeck.com/sferik)
- Past talks
  - [Code for America Summit 2011 - Adopt-a-Hydrant](https://vimeo.com/31459095)
  - [Ruby on Ales 2011 - GUI Programming with MacRuby](http://www.confreaks.com/videos/520-roa2011-gui-programming-with-mac-ruby)
  - [GoGaRuCo 2012 - Writing a Rails Engine](http://www.youtube.com/watch?v=Rvxcc46fox0)
  - [MountainWest RubyConf 2012 - Workshop: Writing a Rails Engine](http://mtnwestrubyconf.org/2012/workshops) (not recorded)
  - [dotRB 2013 - The History of Technology Booms](http://blog.bignerdranch.com/4152-dotrb-getting-plugged-in-at-a-wireless-less-conference/) (video not yet posted)
  - [Changelog Podcast - Episode 0.6.5](http://changelogshow.com/105/28859-episode-0-6-5-code-for-america-with-erik-michaels-ober-and-max-ogden) (audio only)
  - [Ruby Rogues Podcast - Episode 127](http://rubyrogues.com/127-rr-erik-michaels-ober/) (audio only)
