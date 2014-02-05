# The Tip of the Iceberg: Development Was the Easy Part

We want to produce reliable, functioning software... but we often don't. The cliched cry of "but it works on my machine" demonstrates the myopia that most web developers (including me) suffer from: we spend almost all of our time working with a development environment. This leads us to think of production as "like development, with people using it". Then, when things go wrong, we think "oh, I see now, production is like development except this one thing that went wrong". This is exactly the opposite of the mindset we need. Production is fundamentally different from development, and it's important to keep that in mind. This talk discusses some of those fundamental differences, including load balancing, metrics, data store reliability, and network partitions. Don't get stuck rebuilding your servers at 3AM because you went with the option that was easiest during development!

### Why this talk?

Production blindness (for lack of a better phrase) is a really big problem for web developers. Once they've struggled all the way through creating their app, they have to learn how to deploy it! And even if they know how to deploy it, they are unlikely to realize just how different production environments are from development. Without awareness of how production environments are different, we can't anticipate how they will break. Let's encourage thought and discussion about those differences when it's easy to make changes, not after production has gone down for the third time this month.

## André Arko

André thinks Ruby is pretty cool. He designs and builds web applications at Cloud City Development by day, and works on Bundler and Rubygems by night… and also some days.

![Profile picture](./profile_picture.jpg)

- [My website](http://arko.net)
- [My twitter](https://twitter.com/indirect)
- [Past talk slides](http://speakerdeck.com/indirect)
- [Past talk video](http://www.confreaks.com/videos/2552-goruco2013-deathmatch-bundler-vs-rubygems-org)
