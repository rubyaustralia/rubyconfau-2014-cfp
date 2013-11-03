# Fighting Fires: Lessons learnt launching a product with a small team

I want to talk about the bits of launching a product as a small
team that are hard and more important. I won't be talking about
optimising , 

Instead, I'll be taking a look at the story of the development
of our application, [Discovr](http://discovr.info) - over the period
of just over a year (with two backend developers and a team of others).

It'll cover:

* How our tendency to overengineer things bit us (and how technical debt
  is the silent killer)
* Practical tips like the tools and techniques we found helped us sleep at night
* How we used and abused several ruby and associated tools along the way to solve
  problems we encountered.
* How things can fail in unexpected ways (i.e. getting api endpoints deprecated)

Finally, it'll covr how our decision process for technology
worked and didn't work as well as why spending time in some things,
such as continious deployment and automated server management, which can
be hard to sell in a product environment, helped pay off when we got launch
day any everything was on fire.

In other words, a look at things we found important when building a product
as a small team in a startup environment, how we screwed up and a dash
of stories about the things that happened along the way.

Think of it like one of those road trip movies, were not only do you
(hopefully) get a little bit of knowledge, not a lot of substance but
in theory you get to laugh a little along the way.

## My Name

Darcy is a Developer from Melbourne, Australia. He works building backend systems and infrastructure
for [Discovr](http://discovr.info/) as well as working on a lot of [Open Source Code](https://github.com/Sutto).

![Profile picture](https://raw.github.com/Sutto/rubyconfau-2014-cfp/fighting-fires/fighting-fires/profile_picture.jpg)

- [My website](http://sutto.net)
- [My twitter](https://twitter.com/Sutto)
- [Past talk slides](http://speakerdeck.com/Sutto)
- [Past talk video: Bridging the Gap](http://http://www.youtube.com/watch?v=7YY2fia83kk)
