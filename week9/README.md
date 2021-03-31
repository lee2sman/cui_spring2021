- intro to Voice user interfaces
- VUI design process
- VUI vocab
- intro to Voiceflow

# Voice User Interface

Excerpt from Her - [video](https://www.youtube.com/watch?v=GV01B5kVsC0)

#### How To Interact with Alexa


Everything you wanted to know about conversation design but were afraid to ask - [video](https://www.youtube.com/watch?v=RdCmMMwaFRs)

![Alexa parsing](https://res.cloudinary.com/hy4kyit2a/f_auto,fl_lossy,q_70/learn/modules/alexa-development-basics/how-to-design-voice-user-interface/images/1a5b4adf061c45f5e8b6172b6a481523_cj8udtea300410s8t04lhtyws.png)  
*How Alexa parses your -utterances-*  

### The Voice Design Process For Voice User Interfaces (VUIs) 

Voice User Interfaces are still an early technology, though they have connection to previous interfaces such as Command Line Interfaces. Because they are a recent mass-use technology, the process of designing a VUI is still developing.

One method based on our iterative design model for creating GUIs, adapted with additional steps for voice. - [video](https://www.youtube.com/watch?v=8OXN0ZDpwrM)
### Understand

1. User Persona
 - who will use our interface? 
 - what are their needs?
 - what device are we designing for?
2. System Persona
 - you decide how it behaves and sounds
3. Journey mapping

### Explore

1. Sample dialog
  - "Happy path" - first draft
2. Table reading - take notes
3.  "Wizard of Oz" test

### Materialize

1. User flowchart - wireframe
2. Voice design - in a spreadsheet
3. New - multi-modal interactions (combo of screen and voice.)
  - "voice first" - then screen interactions afterwards

![flow chart](https://hackernoon.com/hn-images/1*jxrvo-8m3S2Ao4mBK8_U8w.png)  

How to interact with Alexa - Voice Design Guide - [video](https://www.youtube.com/watch?v=JwUxY2-kIbg&feature=emb_logo)

### Glossary (Alexa):

- Wake word —this is the key for Alexa to start listening.
- Launch —a connector word to link the wake word and invocation name. Supported words include: ask, tell, open, launch, run, begin, and more.
- Invocation name —this is a custom phrase that customers say to invoke your skill. It is generally two–three words long and closely related to the skill’s functionality.
- Utterance —this is the specific phrase that the user wants to take action on with the skill.
- One-shot utterance —the top example is a one-shot utterance, where all information is given at once and fully satisfies what is needed to activate an intent.
- Slot value —a variable part of an utterance. In our travel-planning scenario, the starting location, destination, activity, and date are all slot values.
- Intent —an action that the skill can handle. A single intent can have many different utterances, with or without slots to account for what users may say.

### Basic user interface guidelines:

- Express intentions in examples
- Limit the amount of information
  - Recommended: do not list more than 3 different options per interaction
  - with a longer list of options, group them into subcategories. Start with the most popular options, then ask if they would like more options.
- Use some form of simple visual feedback to let the user know when the system is listening


1. Make It Clear that the User Needs to Respond
2. Don't Assume Users Know What to Do
3. Clearly Present the Options
4. Keep It Brief
5. Avoid Overwhelming Users with Too Many Choices
6. Offer Help for Complex Skills
7. Ask Only Necessary Questions
8. Use Confirmation Selectively
9. Obtain One Piece of Information at a Time


*These design tips suggested by Amazon Alexa [Best Practices](https://developer.amazon.com/en-US/docs/alexa/custom-skills/voice-design-best-practices-legacy.html) that may be useful Do's and Don'ts.*


## In-class Activity

Designing a simple Voice User Interface

[code on glitch](https://glitch.com/edit/#!/voice-commands-starter) - project starter example for a list-making VUI

# Homework

## Watch

How does Natural Language Processing work?
- [video](https://www.youtube.com/watch?v=oi0JXuL19TA) from PBS/Crash Course - 15 minutes


## Read

Why Do So Many Digital Assistants Have Feminine Names? - [article](https://www.theatlantic.com/technology/archive/2016/03/why-do-so-many-digital-assistants-have-feminine-names/475884/) - 10 minutes

Why People Name Their Machines - [article](https://www.theatlantic.com/technology/archive/2014/06/why-people-give-human-names-to-machines/373219/) - 5 minutes

## Write

Please write a reading response to the two articles. We've now read how humans like to anthropomorphize their machines, and some of the reasons digital assistants have feminine names. If you were designing a digital assistant, what choices would you make in its design? Would it have a name? A gender? Describe how you would design the assistant.

## Code

Based on your previous list application, design a voice user interface.

1. Hone in on a single idea to implement.
2. List the 'activation' words. What will the voice user interface listen for?
3. What will the program run in response?
4. What code do you need to run?
5. Now implement the coding based on the given starter code

You do not need to turn in the answer to these questions. Just a link to your program.


[code on glitch](https://glitch.com/edit/#!/voice-commands-starter) - project starter example for a list-making VUI

