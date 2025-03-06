Web Fonts and Translation
^^^^^^^^^^^^^^^^^^^^^^^^^

The correct font for this text is called Nastaliq or Nastaleeq. Google
has a version called Noto Nastaliq Urdu.

In order to make this font available for the project on BIEL (or WACS)
we need to add something to the project. In the project folder (found
via the data path) we will create a directory called ``.apps`` It must
start with a dot, or period.

In the .apps directory we create a directory called
``scripture-rendering-pipeline``. In the scripture-rendering-pipeline
directory, we create a text file called ``meta.json``

The contents of the text file are very specific:

.. code:: json

       {
         “fontUrl” : “https://fonts.googleapis.com/css2?family=Noto+Nastaliq+Urdu:wght@400;700&display=swap”,
         “fontFamily” : “’Noto Nastaliq Urdu’, serif;”
       }

Here, we point to the place where the web browser will get the font
(fonts.googleapis.com) and give specific information about the name of
the font and what display characteristics it will have. This particular
font comes from https://fonts.google.com/. You can find more information
about the different fonts available there, as well as the ways in which
you will specify how to display them.

This is an advanced topic. Most of our translation work will display
correctly with our default fonts.

Lab 61: Web Fonts
'''''''''''''''''

1. What needs to be added to a translation project folder to have a
   special font appear on WACS / BIEL?
   \________________________________________________________\_
   \________________________________________________________\_
2. How often will you need to do this?
   \________________________________________________________\_
   \________________________________________________________\_
   \________________________________________________________\_
   \________________________________________________________\_
   \________________________________________________________\_
