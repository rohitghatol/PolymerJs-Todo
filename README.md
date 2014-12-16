Todo Example in Polymer.js
==============
## Overview
This github repository contains the Todo Sample App built using Polymer.js.
The Todo Sample App is built using numerous components
* [Todo-List](https://github.com/rohitghatol/PolymerJs-Todo/blob/master/elements/todo-list.html) Component which contains other sub components
* [Todo-Element](https://github.com/rohitghatol/PolymerJs-Todo/blob/master/elements/todo-element.html) Component which represents each Todo Item
* [Todo-TextBox](https://github.com/rohitghatol/PolymerJs-Todo/blob/master/elements/todo-textbox.html) Component which represents a TextBox Component. The Text Box appears as a Label in read mode, when double clicked it converts to Text Box. The Text Box commits the text on user pressing "Enter" Key and cancels on using pressing "Esc" Key
* [Todo-Controls](https://github.com/rohitghatol/PolymerJs-Todo/blob/master/elements/todo-controls.html) Component which represents the control bar at the bottom

## Inter-Component Communication
The [Todo-TextBox](https://github.com/rohitghatol/PolymerJs-Todo/blob/master/elements/todo-textbox.html), [Todo-Element](https://github.com/rohitghatol/PolymerJs-Todo/blob/master/elements/todo-element.html) and [Todo-Controls](https://github.com/rohitghatol/PolymerJs-Todo/blob/master/elements/todo-controls.html) Components communicate with the parent Component [Todo-List](https://github.com/rohitghatol/PolymerJs-Todo/blob/master/elements/todo-list.html) Component which contains other sub components using Events. This is done by the fire() method within the component and caught using the polymer "on-<<event>>" handlers.


## Screenshot

### Todo App
![alt tag](https://raw.githubusercontent.com/rohitghatol/PolymerJs-Todo/master/Todo-Sample.png)
