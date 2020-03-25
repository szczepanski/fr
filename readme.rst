**french**
----
|
*...from scratch*

|
|
|
.. comment --> depth describes headings level inclusion
.. contents:: contents
   :depth: 10
   

|
|
|

abbreviations
==============
f
   female
m 
   male
fm
   formal
ifm
   informal
| 
|
beginner a1
============
|

**subject pronouns / zaimki**


.. list-table:: pronoms sujets
   :widths: auto
   :header-rows: 2
   :align: right

   * - singular
     - plural
   * - en / formal / informal
     - en / formal / informal
   * - i / je
     - we / nous / on
   * - you / vous / tu
     - you / vous 
   * - he / il
     - they(m) / ils
   * - she / elle
     - they(f) / elles
   * - one / on
     - 

|

**ou vs u**

- **ou** --> vous, tout, roue
   - *tongue in centre of mouth (not touching any other part)*
   - mouth rounded, lips pushed forward (blowing out candle)
   - mouth almost closed

- **u** --> vue, tu, rue
   - *tongue is at the front touching the bottom front teeth*
   - mouth rounded, lips pushed forward (blowing out candle)
   - mouth almost closed
**adjectives - female and male forms**
- feminine form - usually add an "-e" at the end
- changes  pronunciation if  masculine form of the adjective ends with a consonant
- doesn't change  pronunciation if the masculine form of the adjective ends with a vowel
``Il est content. Elle est contente``
``
Il est fatigué. Elle est fatiguée.
``

|
|
|
**vocab**

enchanté / enchantée (said by m/f)
   nice to meet you 
oui / ouais (fm/ifm)
   yes
mouais, ok
   yeah, ok (not keen, ifm)
tu peux me tutoyer
   you can address me with tu
stressé / stressée (m/f)
   stressed
inquiet / inquiète (m/f)
   worried
triste / triste (m/f)
   sad
en forme / en forme (m/f)
   in good form, shape 
   

NEXT LESSON 8


|
|
|
|
|
|
|

reStructuredText - testing [H1 / title]
================================
*****
H2
*****
H3
########
H4
**********************
H4B
**********************
H3B
########


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


manual grid table

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



manual simple table


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


automated table example


.. table:: auto widths
   :widths: auto
   :align: center
   
   =====  =====
     A    not A
   =====  =====
   False  True
   True   False
   =====  =====


automated csv table

.. csv-table:: CSV
   :header: "Treat", "Quantity", "Description"
   :align: center
   :widths: auto
   
   "Albatross", 2.99, "On a stick!"
   "Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be
   crunchy, now would it?"
   "Gannet Ripple", 1.99, "On a stick!"
   
   
automated list table
   
.. list-table:: list
   :align: right
   :widths: auto
   :header-rows: 2

   * - Treat
     - Quantity
     - Description
   * - a
     - b
     - c
   * - Albatross
     - 2.99
     - On a stick!
   * - Crunchy Frog
     - 1.49
     - If we took the bones out, it wouldn't be
       crunchy, now would it?
   * - Gannet Ripple
     - 1.99
     - On a stick!

