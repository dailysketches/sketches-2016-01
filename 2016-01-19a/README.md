Sketch 2016-01-19a
--
This subfolder of the [sketches-2016-01 repo](https://github.com/dailysketches/sketches-2016-01) is the root of an individual openFrameworks sketch. It contains the full source code used to generate this sketch:

![Sketch 2016-01-19a](https://github.com/dailysketches/sketches-2016-01/blob/master/2016-01-19a/bin/data/out/2016-01-19a.png?raw=true)
[Listen to the sketch on Daily Sketches](http://dailysketches.github.io/sketch-19-01-2016/)"


This source code is published automatically along with each sketch I add to [Daily Sketches](http://dailysketches.github.io). Here is a [permalink to this sketch](http://dailysketches.github.io/sketch-19-01-2016/) on the Daily Sketches site.

Run this yourself
--
If you are running [openFrameworks via XCode](http://openframeworks.cc/download/) on a Mac you can just clone this directory and launch the `xcodeproj`. If you do that you should see something similar to the sketch above.

Addons
--
If the sketch uses any [addons](http://www.ofxaddons.com/unsorted) you don't already have you will have to clone them. Note that this readme was auto-generated and so doesn't list the addon dependencies. However you can figure out which addons you need pretty easily.

In XCode you will see a panel like this. Expand the folders under `addons` until you can see some of the source files underneath.

![How to find missing addon dependencies](https://github.com/dailysketches/dailySketches/blob/master/images/dependencies.png?raw=true)

In the example above, the addon `ofxLayerMask` is missing (it's source files are red), but `ofxGifEncoder` is present.

Versions
--
Note that openFrameworks doesn't have a great system for versioning addons. If you are getting results that look different to the gif above, or it won't compile, you may have cloned newer versions of some addons than were originally used to generate the sketch.

In that case you should clone the addon(s) at the most recent commit before the sketch date. Not ideal, but you will only have to do it rarely.

Yes, openFrameworks could use a good equivalent of [bundler](http://bundler.io/). You should write one!
