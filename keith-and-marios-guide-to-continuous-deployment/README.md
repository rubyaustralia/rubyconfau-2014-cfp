# Keith and Mario's Guide to Continuous Deployment with Rails

Recently it has become common practise for development teams to deploy their
code several times a day, as well as encouraging new developers to deploy on
their first day at work.

In our talk Mario and I will discuss how we use continous deployment to push
these practises to the extreme. Automatically deploying the master branch on
new changes is an awesome way to improve your development process.

Automatically deploying master will fundamentally change how you work. Gone are
the days of the epic pull request. You'll quickly find yourself writing smaller more
managable chunks of code, that overall have a great impact on the quality of the
software you produce.

By the end of the talk you'll know how to change the GitHub merge pull request
button into a deploy button - and have the confidence to do so.

Some things we'll go over in the talk:

  * How to setup your CI environment for deployments
  * Why having fast tests are important
  * How to use your Staging environment for testing deployments
  * How to use feature flags to hide deployed features from *some* users
  * Zero downtime deploys, even when there are database migrations
  * Your new deploy button, AKA The GitHub merge pull request button
  * What to do when deployment goes wrong

## A bit about us

Mario and I together performed a talk at the 2013 Ruby Australia Conference entitled "Keith and Mario's Guide to Fast Websites" ([slides](https://speakerdeck.com/keithpitt/keith-and-marios-guide-to-fast-websites), [video](http://vimeo.com/61342267)). The talk was a lot of fun and we had a great response from the audience. We would love to come back again next year to perform another talk.

### Mario Visic

Mario is a Ruby on Rails developer from Perth Australia, he currently works on the [Microlancer](http://www.microlancer.com/) team at Envato in Melbourne. As well as being a Co-Founder of [Desktoppr](https://www.desktoppr.co) he has also worked on some cool projects such as [iMeducate](https://www.imeducate.com) and [Airtasker](https://www.airtasker.com)

In his spare time he enjoys eating different types of cheeses.

![Profile picture](https://raw.github.com/keithpitt/rubyconfau-2014-cfp/master/keith-and-marios-guide-to-continuous-deployment/mario_profile_picture.jpg)

- [Website](http://www.mariovisic.com)
- [Twitter](https://twitter.com/mariovisic)
- [GitHub](https://github.com/mariovisic)
- [Past talk slides - Declarative Cucumber at Sydney roro](http://mariovisic.github.com/declarative_cucumber/)

### Keith Pitt

Keith is a Ruby Developer from Adelaide living in Melbourne. By day he works at [Pin Payments](http://www.pin.net.au) and by night he works on [Buildbox](https://buildbox.io).

In Keith's spare time, he watches many scary movies, and wins Magic Competitons.

He has been involoved with Rails Camp Australia, as well as being on the organisation comittee for the Adelaide Rails Camp 2011.

![Profile picture](https://raw.github.com/keithpitt/rubyconfau-2014-cfp/master/keith-and-marios-guide-to-continuous-deployment/keith_profile_picture.png)

- [Website](http://keithpitt.com/)
- [Twitter](https://twitter.com/keithpitt)
- [GitHub](https://github.com/keithpitt)
- [Past Talk Slides - UI Testin with Frank](http://slidesha.re/SuMD4p)
- [Past Talk Video - VendorKit at Cocoaheads Melbourne](http://www.melbournecocoaheads.com/vendorkit-keith-pitt/)
