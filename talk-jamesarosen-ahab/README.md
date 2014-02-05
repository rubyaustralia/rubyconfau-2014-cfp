# AHAB, An HTTP Asset Bundler

A good package management system is integral to building reliable, living
applications. The Ruby world is fortunate to have Rubygems and Bundler.

Each such system tends to get very high adoption within its own language, but
web applications are polyglot. Twitter-Bootstrap isn't written in Ruby, so
the authors don't publish them as gems. Instead, we
see a proliferation of *project*-for-*packaging sytem* wrappers:
[bootstrap-sass-rails](https://rubygems.org/gems/bootstrap-sass-rails),
npm's [bootstrap-sass](https://npmjs.org/package/bootstrap-sass),
[Bootstrap-Maven](https://github.com/efsavage/Bootstrap-Maven),
[components/bootsrap](https://github.com/components/bootstrap),
[bower-bootstrap-less](https://github.com/jozefizso/bower-bootstrap-less).

The AHAB philosophy is to move browser asset management to the one place all
web projects already agree on: the HTTP layer. This talk covers the AHAB
protocol and its usage in Rack applications, including both deploy-time- and
runtime asset resolution.

## James A. Rosen

James A. Rosen is a Senior User Happiness Engineer at Zendesk, where he writes
Ruby and JavaScript, with a focus on front-end quality and performance
engineering. He holds a degree in Information Security from Carnegie Mellon,
as well as degrees in Music and Italian Culinary Arts. He prefers his spaghetti all'arrabbiata and his code non-spaghetti-like.

![Profile picture](https://raw.github.com/jamesarosen/rubyconfau-2014-cfp/jamesarosen/ahab/talk-jamesarosen-ahab/profile_picture.png)

- [My twitter](https://twitter.com/jamesarosen)
- [Past talk slides](http://github.com/jamesarosen/presentations)
- [Past talk video](http://lanyrd.com/2013/melbjs-june/scgfrd/#link-rwkk)
