## Week 4 notes 

### Overview of the day

- review MTA Metrocard screen
- practice flexbox
- responsive design
- efficiency in design
- iterative design 
  - user-centered design
- wireframing + prototyping
  - paper prototyping
- frameworks
- intro to layout

### Questions / review CSS Selectors

## Flexbox

Flexbox layout is a relatively recent (as of 2017) addition to CSS providing an efficient, intuitive model to arrange, space out and align a series of html assets within a *container*. 

The way this works is that you define a *container*, a parent box object that your items (usually images or other html items like divs) will sit inside. You define how those items should take up the full space of the container. The items expands to take up the full space of the container.

This isn't the only way to lay out assets on a webpage or web app. It is ideal for small screen web applications. For larger layouts the CSS grid system is recommended.

![flexbox container](../assets/images/container.svg)  
*Flexbox container, source: [CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)*


#### Flexbox - code snippets 

```
.container {
/* this is a comment in css */
/* you assign the parent container using display: flex */

  display: flex;
  
/* optional: define flex-direction as row, column, etc */
  
  flex-direction: row; /* default, if undefined */
  
/* optional: flex-wrap defines whether items fit on a single line or wrap */

  flex-wrap: wrap; /* default is nowrap */
}
```

###### Justifying content

Justifying content is often used with Flexbox. It allows you to define how items spread out and take up space inside the container. You define this on the parent container.

![justify-content in flexbox](../assets/images/justify-content.svg)  
*Justify-content in Flexbox, source: [CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)*  

```
.container {
  justify-content: space-evenly;
  
  /* other options: 
    flex-start (default), aligns to left
    flex-end, aligns to right
    center, aligns to center
    space-between
    space-around
    space-evenly
  */
}
```

##### Flexbox links

- [CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Flexbox Froggy](https://flexboxfroggy.com/)


![flexbox children - flex items](../assets/images/children.svg)  
*Flexbox items aka children, source: [CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)*

```
.child-item {

/* flex-grow defines how much space an item takes up, optional */
  
  flex-grow: 2; /* this will be twice the width of other items (or height if a column) */

}


```

- [demos](https://css-tricks.com/almanac/properties/f/flex-wrap/) of flex-wrap


### More Design theory 


#### Design Principles

1. Learnability
2. Visibility
3. Efficiency
4. Error prevention / error handling
5. User control


##### Efficiency

When designing an interface, consider your *defaults*. Defaults are common answers. Consider how you may want to indicate these defaults to your users.

###### Anticipation

Anticipation is the concept that good design presents all information at once. It considers a common workflow, and minimizes having to move back and forth within this workflow.

Users don't like having to move back and forth within navigation. Consider our pizza calculator apps as an example.

## Usability through Iterative Design

User-centered design 
- iterative design is considered best practice for user-centered design
- what does iterative mean?
- considered best practice for usability


### What does iterative design look like?

It's a circular process

1. Create an initial interface design 
2. Implement
3. Evaluate

**Go back to design and begin again...**

This is in contrast to an earlier design process called Waterfall.

![waterfall model of software design](assets/images/waterfall.svg)  
*Waterfall model of software design, source: [Wikipedia](https://upload.wikimedia.org/wikipedia/commons/e/e2/Waterfall_model.svg)*  

The limitations of this model:

- User interface is difficult to predict and we're likely to get it wrong
- Users aren't involved in testing until near the end
- UI mistakes cause changes in requirements and design

#### Iterative design process

1. Create initial interface design
2. Have users test it
3. Note problems
4. Refine interface
5. Have users test it
6. Refine interface
7. Have suers test it
8. Repeat until interface issues solved

#### The spiral model

This is a modification of the iterative process. We describe the earliest interfaces as *cheap* - minimal fast prototypes.

It's possible to make multiple alternatives to consider and test. Remember David Reinfurt's alternative UI prototypes for the Metrocard machine.

Start with a paper/pencil sketch! Earliest interfaces should be considered *throw-away*.

Later iterative designs should be more detailed. THE UI should become clearer.

The more iterations the better your UI. Have every prototype get evaluated by users!

Also consider Simulation (The "Wizard of Oz" approach).

#### Prototyping

- Cheap, throw-away UI tests
- Cheapest: 
  - paper / pencil prototypes
  - "Wizard of Oz" simulation
- Medium:
  - HTML
- GUI implementation:
  - native vs web GUI

#### Homework
  Read about [Responsive Design](https://www.smashingmagazine.com/2011/01/guidelines-for-responsive-web-design/) in Smashing Magazine.  
- What is it?
- How do you do it?
  - tip: consider your viewport width, use flexbox, pay attention to font sizes
- Make a responsive web app!

Additional resources:
- basic overview of responsive design in html/css on [W3Schools](https://www.w3schools.com/html/html_responsive.asp)
- [Responsive Web Design: 50 Examples and Best Practices](https://designmodo.com/responsive-design-examples/)

*source: User-Centered Design is adapted from MIT Open Courseware 6.831 User-Centered Design*
