.. _features:

reStructuredText Features
==========================

 * Bulleted points :ref:`this is an example <usecase>`

 * :ref:`To link this bulleted point to a section below <youtube>`

 * You can have a inline image like **Huawei Logo** |logo| image.

   .. |logo| image:: /images/logo.png
             :scale: 20%

.. _youtube:

YouTube Video
++++++++++++++

You can embed a YouTube Video into the document.

.. raw:: html

   <iframe width="560" height="315" src="https://www.youtube.com/embed/VP4xsZf7od0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Roles
+++++

Sphinx uses interpreted text roles to insert semantic markup into documents. They are written as \:rolename:`content`. 

There are many roles but only few are explained below:

Some Examples
**************

 * Math: Role for inline math. 
   Since Pythagoras, we know that :math:`a^2 + b^2 = c^2`.
 
 * Command 
   :command:rm
   
 * Cross-referencing syntax, anything, objects, arbitrary locations, documents, downloadable files, figure number, or items of interest.

 * Special except formatting

 * Substitutions
   |release| |today|


Directives
+++++++++++

Some Directives examples are captured below:

 * Warnings or Note or you can customize as per your needs.

   .. warning::
      warning!

   .. note::
      You can have customize titles for the boxes.


 * Code Blocks and Showing code examples

    .. code-block:: ruby

       Some Ruby code.

    .. code-block:: python
       :emphasize-lines: 3,5

       def some_function():
          interesting = False
          print 'This line is highlighted.'
          print 'This one is not...'
          print '...but this one is.'

 * Math

    .. math::

       (a + b)^2 = a^2 + 2ab + b^2

       (a - b)^2 = a^2 - 2ab + b^2

 * Tables

   .. tabularcolumns::C




