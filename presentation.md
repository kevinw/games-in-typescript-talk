# using typescript for lightweight gamedev

* demo
* why pick Typescript for gamedev?
* what worked
* some pain points
* compiler API tricks

# demo

here's my game (turn the sound up)

# why pick Typescript for gamedev?

* portability
* types are my jam (and dealing with math without them is ugly)
  * playing the "where did this NaN come from" game isn't that fun

# some pain points

* compile times (but they got much better!)
* aren't a ton of game specific libraries out there
* i didn't know about the null switch till later, and then it was too late
* <reference> vs import
* webpack or (something else) and how it interacts with .tscconfig

# compiler API tricks

* minification but preserving certain class names
* examples of components
  * something bounces
  * something pathfinds
* it's really easy to write a prepass!
* integrate it into your Cd

# future

* electron builds
* maybe a more minimal webgl thing?
* is flow good?
