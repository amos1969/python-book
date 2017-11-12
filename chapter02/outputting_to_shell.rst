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
it can do stuff to it. We can change the code so that it will output other text, by altering what lies between the quote
marks. Do that now and rerun the code to make sure it works successfully.

We can make the code output over multiple lines in a number of ways. Firstly we can add a print function for each line
of text we want to output. The last verse of the poem "The Masque of Anarchy" by Shelley reads::

   Rise, like lions after slumber  
   In unvanquishable number!  
   Shake your chains to earth like dew  
   Which in sleep had fallen on you:  
   Ye are many-they are few!  

We can turn this into a program in a number of ways. Firstly as stated we can use multiple **print** functions:

.. activecode:: masque_of_anarchy_01
   :nocanvas: 
   :caption: Multiple print functions
   :language: python

   print("Rise, like lions after slumber")
   print("In unvanquishable number!")
   print("Shake your chains to earth like dew")
   print("Which in sleep had fallen on you:")
   print("Ye are many-they are few!")

Each **print** automatically outputs a newline character after the text has been displayed, making each string display
on a new line. This is behaviour we can modify if we so choose (more on this in a later section). The second way in
which we can display the poem on multiple lines is to put triple quotes around the whole verse, and use a single
**print** function. This will output whatever is inside the string, using any newline characters that make up the
string.

.. activecode:: masque_of_anarchy_02
   :nocanvas: 
   :caption: Multi-line print functions
   :language: python

   print("""Rise, like lions after slumber
   In unvanquishable number!
   Shake your chains to earth like dew
   Which in sleep had fallen on you:
   Ye are many-they are few!""")

Adding extra line breaks inside the string, is then reflected in the output from the **print** function. Try putting the
cursor at the end of one of the lines of poetry and hitting enter, then rerun the code.

We can also get the same effect using a single **print** function, by including all of the lines of text in a single
string and adding in the newline character ourselves (newline is a backslash followed by an n - **\\n**).

.. activecode:: masque_of_anarchy_03
   :nocanvas: 
   :caption: Multi-line print function with manual newline character.
   :language: python

   print("Rise, like lions after slumber\nIn unvanquishable number!\nShake your chains to earth like dew\nWhich in sleep had fallen on you:\nYe are many-they are few!")

