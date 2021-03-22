week 8

# Bringing it all together: a complete functional application and interface

**Reminder: We will break at 5pm. I am introducing guest speaker Auriea Harvey. I will send out the zoom link Wednesday**  

# This week

- bringing it all together (HTML, CSS, JS) 
  - building a list app

## More jQuery

> "The essence of jQuery is selecting a node (or set of nodes) in the DOM and acting on it (getting properties, setting properties, or changing tree structure). Selection is done by a pattern language (which is a good pattern language to know because it’s used in CSS as well...For example, the pattern #send finds a node with the id attribute “send”, .toolbar finds nodes with the class attribute “toolbar”, and button just finds all ```<button>``` nodes. jQuery provides a variety of methods for acting on the nodes you find. In general, jQuery methods come in pairs with the same name: the method with no arguments gets a value, and the method with arguments sets a value. So .text() returns the text contained in the node’s descendents, while .text (“Tweet”) replaces all those descendents with the text node “Tweet”. Similarily, .attr() gets and sets attribute values, .click() sets a mouse event handler (or simulates a click), .val() gets or sets the value of a text widget, and .html() gets or sets the descendents of a node as HTML."

Example:

Our starting html:

```
<button id="send" class="toolbar">Send</button>
```

Select nodes in jQuery:

```
$("#send")    <- an element with ID "send"
$(".toolbar") <- an element with class "toolbar"
$("button")   <- a button html object
```

Create nodes:

```
$('<button class="toolbar"></button>')
```

Act on nodes:

```
$("#send").text() //returns "Send"
$("#send").text("Tweet") //changes button label
$(".toolbar").attr("disabled", "true");
$("#send").click(function(){ CODE GOES HERE TO DO WHEN CLICKED})
$("#textarea").val()
$("#mainPanel").html("<button>PRess Me</button>")
```

### Code examples


- Date picker
- Dialog box
- To-Do List


Note: An advanced to-do list (like Trello) example can be found [here](http://sdaityari.github.io/to-do-list/) with code [here](https://github.com/sdaityari/to-do-list/blob/master/assets/todo.js). Look in assets/js folder for the css and jquery code.

# Homework

### Read
- Read and be prepared to talk about [A Pioneer of Digital Arts Looks Back on a Defining Era](https://www.nytimes.com/2021/03/18/style/loretta-staples-ui-design.html): Loretta Staples, a U.I. designer in the 1980s and ’90s, had a front-row seat to the rise of personal computing. - 10 minutes 

- Read and be prepared to discuss [How to Design a Voice User Interface](https://www.interaction-design.org/literature/article/how-to-design-voice-user-interfaces) - 20 minutes

### Write

Write: Pick an application with which you are intimately familiar, using it frequently, and that you enjoy using but someone else might not be familiar with. For the purpose of this assignment do not pick a social media app or any default app on your phone. It could be a game, a meditation app, a journaling app, or something else. Describe the application: what it's for and/or what you use it for. Answer at minimum these questions: For what kind of user is this application made? How does it orient beginners (or not)? What elements of the interface and navigation support its use by an "expert" (someone that uses the application a lot)? How much do you think about the interface itself while you are using the application to do your task, read your book, play your game (etc)? Are there parts of this that you wish you could improve? What would you do differently? Could the interface be simplified and still have the functionality that you need?

### Code your own list software

Create your own List-making application and interface. Alternatively, it could be a program to list your friends' birthdays, your meals for the week, a shopping list, your dreams, etc. 

Because this is an application and interface for *you* (not for others), you do not need to do user testing (except for yourself). 

Use our starter code from class, with the goal being to add your own HTML, CSS, fonts, icons and jQuery code to make the program match your own needs and design goals.
