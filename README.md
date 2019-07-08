# But Every Other Beat Is Missing™

## What is this?

A machine that would (ideally) allow you to skip every other beat
in any song uploaded, even auto-detecting the uploaded song's BPM.

That, of course, was merely my dream. The actual code here is
literal garbage, and does only a fraction of what I hoped it would.

But hey this has been sitting on my computer for ages, I might
as well throw it on GitHub.

## Okay but what does it look like

I actually really like the style I was going for:

![screenshot](https://i.imgur.com/U2vLXBm.png)

[Watch it in action](https://avellar.ml/resources/but-every-other-maroon.mp4)

## Neat! What's wrong with it?

- The auto BPM detection doesn't work nearly as well as I hoped it would;
- I don't think `setInterval()` is *that* reliable, which leads to some
inconsistencies
- The UI needs a huge improvement
- Perhaps a way to export your beautiful creation would be nice