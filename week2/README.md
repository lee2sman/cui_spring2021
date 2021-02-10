# Week 2

- review
- look at our alternative desktops
- intro to text user interfaces
- play: try out CLIs
- workshop: CLIs (command line interfaces)


**Note for Windows users: I'm sorry to say this, but the *standard* text interface is Linux! Macintosh computers have access to this under the hood because they are built on top of BSD, which uses the same commands as Linux. PC users, your Windows Powershell is fundamentally different, and so you should use Windows Subsystem for Linux**.

# Text User Interfaces

Last week we looked at a history of interfaces and operating systems.

Review: What is a User Interface?

> Yet with its creaky, decades-old constraints and inexplicable quirks, the command line is still the most versatile corner of the computer. It lets you pull back the curtain, see what’s really going on, and creatively interact with the machine at a level of sophistication and depth that GUIs cannot afford. It’s available on almost any laptop, for anyone who wants to learn it. It can be used interactively, or it can be automated. And, it doesn’t change as fast as other parts of the system. There is creative value in its stability. *--source: [Command Line Interface Guidelines](https://clig.dev/)*

In the *early years* of computing, we had circuits, switches, lights, and dials. Later came punch cards for calculations and storing data and programs. Still later came terminals, which were monitors connected to a computer. We input commands to the computer through a Teletype typewriter. Output would be printed out or displayed on the terminal monitor.

Computers are complex. IC chips that computers were built from, especially in the earlier years, were expensive. Because of this, computers had a minimal amount of memory. Text was much easier to store and work with, so the priority was placed on text. This became the primary way to interact with a computer. 


Video: [keyboards and command line interfaces](https://www.youtube.com/watch?v=4RPtJ9UyHS0) on youtube - PBS Video, 11min

![example command line interface](http://toastytech.com/guis/textdos1.gif)  
example command line interface  

The command line interface is a text-only interface. Where the user types in commands is known as the *prompt*. A user types in commands; then the output is displayed immediately. And a user may then type in more commands, with more output, in a continuous cycle.

Some advantages:
- A "powerful" environment. Everything can be done on one screen, in one location. Commands can be combined together.
- Commands are "conversational". They can evolve over time, iteratively.
- They can be automated.

Disadvantages:
- "Discoverability" problem. Which commands are available? How do you use them? What options exist?
- Expertise needed to get started and to advance. Not beginner-friendly.

Macintosh computers were the first mass-market computers to popularize taking a graphics-first approach to computer interfaces. The Mac Human User Interface guidelines were printed in 1987. They emphasized "see and point" instead of remember and type.

![Hitchhiker's Guide to the Galaxy Game](http://toastytech.com/guis/texthhg.gif)  
Hitchhiker's Guide to the Galaxy Game  

You can see in this screen a text-based game. These were similar to "Choose your own adventure" style books you may have read as a kid, or other branching narratives, but they had much more functionality. Not only did you advance in a story, but you had inventory, could solve puzzles, join battles and more.

This program uses a parser. The parser is the interface that runs through commands you type in and then executes code depending on your commands.

These types of games attempted to use a more natural *language*, but they could still have problems with their commands being unclear.

Over time, programmers attempted to use space and to make these programs more *visual*.  

![Text User Interface example](http://toastytech.com/guis/textmite.gif)  
text user interface example  

![simpler text user interface example](https://upload.wikimedia.org/wikipedia/commons/2/25/XFdrake.png)  
A simpler text user interface example. You can see how this approaches a traditional graphic user interface in design.  

These kinds of programs that run in the command line are called Text User Interfaces.  

![file manager](http://toastytech.com/guis/textdiskman.gif)  
a file manager program, an alternative way to view the desktop  

Some of these programs started using color. They can be quite complex.

![email - microsoft exchange](http://toastytech.com/guis/textexchangedos.png)  
This is an example of Microsoft Exchange, the email system our school uses, navigated in DOS with a Text User Interface.

You'll notice this program almost appears to be a GUI. It even has menus.

![Google in w3m](https://mandeep7.files.wordpress.com/2014/07/google.png)  
Here is a web browser running in the command line, searching on Google.

[Keyboards and Command Line Interfaces from PBS](https://www.youtube.com/watch?v=4RPtJ9UyHS://www.youtube.com/watch?v=4RPtJ9UyHS0)  

Keyboards and Command Line Interfaces, on PBS, 11 minutes

# Workshop

Basic commands today

To move around: 

```
cd [foldername]
```

To move around ("change directory") in folders on our computer.

```
ls
```

To list files in a folder.

```
pwd
```

To remind you what folder you are in. (aka "print working directory")

```
cat [filename]
```

This prints out the text of a file onto the screen.

```
man [program-name]
```


This starts up the computer *manual* for a command line program. You can scroll up and down and press **Q** when you are finished reading to exit.

```
echo "text"
```

Prints out text.


**When you get stuck, Control-C usually is the CANCEL command**. Though a few use *Control-D*.


### Workshop: Creating simple text user interfaces.


BASH

```
#!/bin/bash
# Ask the user for their name

echo "Hello, who am I talking to?"
read varname
echo "It's nice to meet you $varname"
```


### Pizza Ordering Command Line Program

Your goal: design command line software for determining the total number of pizzas to order for a group of people.

Your software should be useable by a variety of people, from beginners to command line interfaces to advanced users.

Your program should have help, be intuitive, and ideally, powerful.

At minimum, your program should ask for the total number of people, then print out the ideal number of pizzas to order.

Your program can be more customized for you.

Things to consider:
- adding ascii art
- adding a menu
- adding help
- adding power features


### Command Line Interface Resources

- [Command Line Interface Guidelines](https://clig.dev/)  
  
  

### Our Desktops

Reminder of desktop metaphors:

![Macintosh desktop program Magic Cap](https://media.nngroup.com/media/editor/2012/12/11/anti-mac-fig1.gif)  

We'll review our homework.

### Homework

Read the excerpt from Design/Interface in The Interface Experience, up to page 46 in the book (which is 25 pages of the pdf).

Write: In The Interface Experience what concepts from earlier media theorists, technicians and designers stick out to you that can inform our user interface design work?

Read this old but important [Effective Visual Communication for Graphical User Interfaces](https://web.cs.wpi.edu/~matt/courses/cs563/talks/smartin/int_design.html)  
### User Interface Wall of Shame 

- Read [Blame terrible interface design for the Hawaii missile alert debacle](https://outline.com/L6bNfh)
- What are examples of bad interfaces you can find in your environment around you? This could be on your phone, computer, but also in th eenvironment around you (doctor's offices, a plane, elevators, public spaces).

Post examples of bad user interfaces to our discord channel. Include some text explaining what's so terrible about it, keeping in mind that some interfaces are combinations of good and bad design.

