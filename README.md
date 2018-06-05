A keycounter, made to record one-dimensional data of computer usage for the purpose of visualization and analysis.

## Use it with

![](http://macwright.org/graphics/minute_new.png)

[minute](https://github.com/tmcw/minute) is the original - it uses
[d3js](http://d3js.org/) to render minute output in-browser with some interactivity.

![](http://farm9.staticflickr.com/8045/8122970298_240635ef10_c.jpg)

[Sleep Chart](https://gist.github.com/3955066) calculates hours of sleep
based on keystroke gaps. Depressing, right?

![](http://farm9.staticflickr.com/8467/8123037480_a3c6af9f04_z.jpg)

[basically.js](https://gist.github.com/3955198) is a non-interactive but
faster minute visualization based on [node-canvas](https://github.com/LearnBoost/node-canvas).

![](http://farm9.staticflickr.com/8468/8150771592_514125731f_o.png)

[weekgram.js](https://gist.github.com/2410842) draws keystroke frequency per
minute for a week, showing patterns in sleeping hours, etc.

## How to Use it

Download the binary (see below), and run it. It'll record keystrokes at `~/Documents/minute/keystrokes.log` in a
CSV document. In order for this to work, you need to grant `hihowareyou` `Accessibility` access under `Security & Privacy` of your `System Preferences`.

![](https://cloud.githubusercontent.com/assets/1551510/3465657/6f4a19e2-026c-11e4-8697-c1065fcbc97b.png)

## Developers

You can compile from source here, but you probably want to just [download a pre-built binary](https://github.com/tmcw/minute-agent/downloads)
to get this working.

## See Also

* [keylogger-osx](https://github.com/dannvix/keylogger-osx)

## What it Does, Technically

It fills in a log at `~/Documents/minute/keystrokes.log` with
the number of keystrokes you make every minute.

All it does is count keystrokes. Unlike a keylogger,
it doesn't steal your money, or do anything amusing that gains
national attention. If you don't trust me,
read the horribly constructed Objective-C yourself, or
don't use it.

It requires the Accessibility API to enabled,
or for you to trust the application.
