Implementing the Command Pattern in Java
Steps:
1) Define a Java Command interface with a method named execute(). (You can name it anything you want, but it is classically named execute() or run().)

2) Create Command classes that implement this interface. The execute() method of each object will contain the logic specific to the action you are encapsulating. (For instance, you might create a FileOpenCommand and a FileCloseCommand in a text editor application.)

3) In an Model/View/Controller GUI program you will have a controller class that constructs each of your Command objects. 

4) Each of these "ready to run" command objects is passed to an <b>invoker</b> class.

5) The invoker class calls the execute() method of a Command object at the appropriate time. In a GUI application this may happen when a user selects a menu item or presses a button.
