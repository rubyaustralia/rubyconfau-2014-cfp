# Building C extensions in Ruby

From time to time, when building Ruby apps, you realise there are no libraries available for what you need. Even worse, Ruby doesn't quite perform as quickly as we would expect in certain areas. There are, however, a lot of high performance, mature technologies built in C that can easily be ported to be used with Ruby. By doing this, we get to keep using our favourite language, opening it to a plethora of applications that were not possible before, and still keep things snappy.

In this talk, I will walk you through the ins and outs of building Spyglass, an OpenCV binding for Ruby. I will also talk in detail about some gotchas (memory management, lack of threading), good practices (C objects as first class citizens, how to properly test extensions), why `mkmf` needs to be retired and some great examples of extensions you probably already use and should be looking at.

## André Medeiros

André is a Ruby Ninja and self-confessed open-source evangelist at Quintel, Amsterdam. There he develops powerful applications for the renewable energy space. Previously Andre headed up the Mobile Division for the leading global internet casino company - BetVictor.com where his talent was recognised from developing the company mobile offering from internal business pitch to successful delivery. The app is now one of the most profitable revenues streams in the company's possession. He was born in the Azores, a tropical set of islands in the middle of the Atlantic that apparently breeds Ruby talent. 

Following his personal motto of "Let's make it cool", Andre loves providing innovation and style within disruptive tech industries.

André is involved in a number of awesome projects, one of which is Spyglass, an amazing versatile computer vision enabler that allows anybody with a webcam and Ruby skills to create his/her own game rapidly using image recognition.

![Profile picture](https://raw.github.com/andremedeiros/rubyconfau-2014-cfp/master/talk-ruby_c_extensions/profile_picture.jpg)

- [My GitHub](https://github.com/andremedeiros)
- [My twitter](https://twitter.com/superdealloc)
- [Past talk slides (DCI)](https://speakerdeck.com/andremedeiros/stop-use-case-time)
