.. _lab-07:

Lab 7: User Control
===================

This lab gives you a chance to practice drawing an object with a function
and allow the user to control it.

.. attention::
    This lab does **NOT** use sprites. Look at :ref:`user-control` for examples
    relevant to this lab.

Write one program, following these steps:

* Create a ``Lab 07 - User Control`` folder for this lab,
  or use one that is already set up in your project.
* Begin your code with the template below:

.. literalinclude:: template.py
    :caption: Lab 7 Template
    :language: python
    :linenos:

* Create a background image of some sort in the ``on_draw`` method.
  Feel free to use any of *your* code that *you* have written from
  prior labs that you have. To do this, put your code in the ``on_draw``
  method. If your code used functions, move those functions as well to
  this program. Paste them above the ``MyGame`` class. Don't turn this in
  with just a solid color for the background, or you'll lose a couple points.
* In :ref:`user-control`, we talked about moving graphics with the keyboard, a game
  controller, and the mouse. To start, pick one of these methods, and get that ball
  moving around in your program.
* In the examples, we just moved a ball. Adjust the code so that it draws
  something more interesting than a ball. You can pull from the code you used in
  prior labs where you drew with a function, and move it to the ``on_draw`` method
  of your class. But don't have your object be a simple one line of code shape.
* Rename your class from ``Ball`` to a name that represents what you are really drawing.
* After you get that object moving, do it again:

  * Pick a *different* method of control (keyboard, mouse, gamepad.)
  * Create a *new class*
  * Draw something *different* with that class, and move it around the screen.

.. note:: Stop!

   Make sure you have two completely different items.

* In the case of the game controller and the keyboard, make sure to add checks
  so that your object does not move off-screen and get lost.
* Add sound effects

  * Add a sound effect for when the user clicks the mouse button.
  * Add a different sound effect for when the user bumps into the edge of the screen.
    Make sure the sound only plays when you are trying to go beyond the edge of the
    screen, and not when you just sit at the edge of the screen. This part isn't
    needed for anything controlled by the mouse.

That's it! Commit and turn in your work.

.. _Arcade Starting Template: https://api.arcade.academy/en/latest/examples/starting_template.html
