# Introduction to the Shell

## Problem Statement

How are we to interact with our computer _as developers_? While you might have
been using computers for years, you've likely been engaging with them as a
_user_ not a _developer_.

What's the difference? Well consider a mechanic driving to work. In that
moment, waiting in traffic, they are a _user_ of the car. But then they take a
right turn and *cough*, *splutter* their car chokes to a stop. At once their
mind changes to being a _mechanic_ or a _developer_. They think about
petroleum, spark-plugs and ignitions. They can _debug_ their car using
techniques they've learned. They can imagine what might be wrong. To get more
data or to verify their guess, they _open up the hood_. Learning to be a
developer (_computer mechanic_?) is similar. You must start "looking under the
hood" of your computer. To access the "hood's" contents, you must use the
shell.

Developers "talk" to the computer by engaging it at the shell level. The shell
is just another way to collaborate with the computer. It might feel
"old-school" or clunky at first compared with Windows or MacOSX. As you learn
more, though, it might surprise you!

Shell skills are critical in being a developer or HTML author.  Comfort in the
shell is an assumption for many technical jobs.

## Learning Objectives

1. Define what a shell program is
2. Recognize a shell interface
3. Recognize operating systems providing a shell

## Define What a Shell Program Is

The shell is the program on your computer that takes in commands you type and
takes action based on those commands. You can think of yourself as having a
conversation with the computer.

When you see a shell it will be at a "command prompt." This means, from the
computer's perspective "I'm listening..." Prompts may look different from
computer to computer. Customized prompts express developer uniqueness. We've
seen weather reports, beautiful colors, computer temperatures in prompts. At
heart, though, they they all carry your command to the operating system and run
it.

You can ask the computer to do many types of tasks. From the command prompt you
can move or rename files just like you would do from a window environment.  You
can _also_ get diagnostic information ("How is my computer?") or help your
computer recover without requiring a reboot ("Hm, computer, time to kill that
hung Chrome tab with the Twitch stream...").  You can ask the computer to run
programs like `ruby my_awesome_program.rb` or even to launch an application!

## Recognize a Shell Interface

A shell interface looks like the following pictures below.

Typically you'll be given some text output and a command prompt. The prompt
will receive commands. You tell the shell you're done typing and that it should
consider your request by hitting `return` or `enter`. After receiving your
command the shell will respond with the information you requested, or will
signal that it did your bidding (say renaming a file), or it will print an
error message. Then you'll be given another prompt and can do it again, and
again, and again.... This cycle can be called a "prompt-evaluation-response
cycle."

Here's the Learn In-Browser IDE's shell. Since the shell environment is so
important for us, whenever you open the IDE the command prompt is also shown.
You will interacting with the shell when you run commands like `learn` and
`learn submit`.

<img alt="Learn In-Browser IDE Shell" src="https://curriculum-content.s3.amazonaws.com/web-development/intro-the-shell/learn_shell.png" width=595>

Here's the Terminal application in MacOSX running a shell. You can launch it by
navigating with the Finder to `Applications` &rarr; `Utilities` &rarr;
`Terminal`.

<img alt="MacOSX Shell" src="https://curriculum-content.s3.amazonaws.com/web-development/intro-the-shell/osx_shell.png" width=595>

Here we see the prompt-evaluation-response cycle, here we
are providing the command `echo` which, well, repeats the command back to the
screen (the "response").

<img alt="MacOSX Shell response" src="https://curriculum-content.s3.amazonaws.com/web-development/intro-the-shell/prompt_response.png" width=595>

You may sometimes hear the shell referred to as your "command line" or
"terminal" or "console". There are some subtle differences between each of
those terms, but by and large you can think of these as referring to ways of
interacting with the shell.

## Recognize Operating Systems Providing a Shell

All operating systems (MacOS, Windows, and Linux / Unix) provide
a shell! While developers often disagree about which  is the
best, time has borne out that they nearly all agree that a shell-based
interface is a power-tool they can't live without.

## Conclusion

Ultimately a shell is a way for you to interact with your computer. It's a
different style than the point-and-click graphical user interfaces that you
might know, but it is incredibly powerful and is the workbench of many
developers. Shell interfaces are provided by all major operating systems and
are marked by their prompt, evaluation, response cycle.


_The video below describes what the shell installed with Mac OS X looks like_

<iframe width="1280" height="720" src="https://www.youtube.com/embed/uxANgIcjmQg?rel=0&amp;showinfo=0&html5=1" frameborder="0" allowfullscreen></iframe>

[Download Video](http://flatiron-videos.s3.amazonaws.com/ironboard/welcome%20to%20the%20shell.mp4)


<p data-visibility='hidden'>View <a href='https://learn.co/lessons/intro-the-shell-ide'>Intro to the Shell</a> on Learn.co and start learning to code for free.</p>

