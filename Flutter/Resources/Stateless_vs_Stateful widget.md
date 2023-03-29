# Stateless widget vs Stateful widget

<b> Befor heading towards Stateless widget vs Stateful widget
    we must understant what does basically widget and state means? </b>

- <b>Widgets: </b>In flutter widgets are the basic building blocks of the user interface.
    A widget is a description of part of a user interface, such as a button, text, or image.

- <b>State: </b>In flutter the state of an app can very simply be defined as anything that exists in
    the memory of the app while the app is running.
    so technically, the state is the information that can be read synchronously when the widget 
    is built and might change during the lifetime of the widget.

 So now as we know what are these state and widget let’s dive directly into our main topic
   i.e what are these stateful and stateless widgets and how do they differ from one another.


### Stateless Widgets:

- <b>The widgets whose state can not be altered once they are built are called stateless widgets. These widgets are immutable once they are built i.e any amount of change in the variables, icons, buttons, or retrieving data can not change the state of the app. Below is the basic structure of a stateless widget. Stateless widget overrides the build() method and returns a widget. For example, we use Text or the Icon in our flutter application where the state of the widget does not change in the runtime. It is used when the UI depends on the information within the object itself. Other examples can be Text, RaisedButton, IconButtons. </b>

- In short widgets that don't have any mutable state, meaning that they do not change their properties over time. Once a stateless widget is created, its properties cannot be changed. Examples of stateless widgets include Text, Icon, and Container
 

### Stateful Widgets:
- <b>The widgets whose state can be altered once they are built are called stateful Widgets. These states are mutable and can be changed multiple times in their lifetime. This simply means the state of an app can change multiple times with different sets of variables, inputs, data. Below is the basic structure of a stateful widget. Stateful widget overrides the createState() method and returns a State. It is used when the UI can change dynamically. Some examples can be CheckBox, RadioButton, Form, TextField. </b>

- In short widgets that can change their properties over time, meaning that they have mutable state. A stateful widget has a corresponding State object that stores the widget's mutable state. Examples of stateful widgets include TextField, Checkbox, and Slider. 
