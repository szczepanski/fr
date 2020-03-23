**french**
-----------
from scratch


.. depth describes headings level inclusion
.. contents:: contents
   :depth: 10
   



----


reStructuredText - testing
================================




External hyperlinks, like Python_.

.. _Python: http://www.python.org/ 


.. code:: python

  def my_function():
      "just a test"
      print 8/2


.. code:: html
    <h1>code block example</h1>


what
  Definition lists associate a term with
  a definition.


Grid table:

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+



Simple table:

=====  =====  ======
   Inputs     Output
------------  ------
  A      B    A or B
=====  =====  ======
False  False  False
True   False  True
False  True   True
True   True   True
=====  =====  ======
  
``inline code``

This is a paragraph.

Paragraphs line up at their left


edges, and are normally separated
by blank lines. 




*****
Title
*****

H1
====

H2
########

H3
**********************
H4
########
H5
**********************


test
====


.. note::  This is a **note** box.
.. index::
