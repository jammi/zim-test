
ZIM Test: A JPEG animation example

This is a simple example of how to animate image sprites by blitting
them using JS as an alternative to GIF animations.

As for compression sizes, YMMV, but video clips in general look nicer
in 24 bit color than indexed and dithered 8bit colors as in
GIF animations.

"JPEG Animations" are also more flexible, because you can define
playback settings at runtime and they tend to be smaller depending
on which quality you settle for. The threshold of this animation
was at 92% JPEG Quality.

With the "Size" set to 1x, the CPU usage benchmark on my system's
browsers are like this (no other pages open in each browser):

          JPEG   GIF
Safari:    ~1%   ~2%
Chrome:  ~4.5%   ~5%
Firefox:   ~9%  ~13%
Opera:   ~5.5% ~3.5%

This repository is fairly large, including all the images used as
well as an animated GIF as the comparison. If this generates some
interest, I might consider creating a general purpose lib as well
as some tools to create the animations.

To just test it out, use my test page:
http://sorsacode.com/zim-test/

-- Juha-Jarmo Heinonen
   o@sorsacode.com
