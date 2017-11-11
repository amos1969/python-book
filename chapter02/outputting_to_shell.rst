=================================
Getting Outputs from your Program
=================================


Making Python Talk to the Outside World
---------------------------------------

All computer programs and systems boil down to a very simple model, basically there has to be some sort of input,
whether that's from a user controlled device such as a keyboard or mouse, an automated device such as a sensor, or even
an external device of some kind that sends a signal to our system.

This then is either processed itself, or causes some sort of processing to take place. Finally, once a result is arrived
at this then needs to be communicated back to the user or other computer systems by outputting some sort of value.

Basically we have **Input --> Process --> Output** there may be other things which occur too, in terms of storing things,
but every computer system and every computer program essentially boils down to a version of this model. So the first
thing we are going to do is make Python tell us a story, in other words we're going to get it to output some text and
other things.

So we are going to use this to make the program output some text in the Python shell, initially we are going to start
with the simplest possible program which just outputs some text like we did in the previous section.

.. activecode:: hello_world_01
   :nocanvas: 
   :caption: The Hello World Program
   :language: python

   print("Hello world!")

If we run this it will just output the text which is between the two quote marks **"**. In technical terms this is a
**string**, which is a piece of text that we can output, manipulate or pass to some other part of the program, so that
it can do stuff to it.
