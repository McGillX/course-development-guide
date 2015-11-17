Problem Templates
=============================

.. note:: If you copy the templates below be sure to paste them in the advanced (xml) editor in edX

Dropdown - Inline Display
----------------------------------------------

Displays the question text inline with the dropdown menu for selecting answer options.

.. literalinclude:: /problem-templates/dropdown-inline_display.html
   :language: xml
   
Long Answer
----------------------------------

Creates multiline textboxes for questions that require larger amounts of text.

.. literalinclude:: /problem-templates/long_answer.html
   :language: xml
   
Numerical Response
----------------------------------

The template below removes alphabetical characters, percent signs and converts commas to decimal places. This avoids the error message resulting from standard edX numerical problems.

.. literalinclude:: /problem-templates/numerical_response.html
   :language: xml   
   
Self Report Completion Button
-----------------------------------------------

A button that when clicked awards points

.. literalinclude:: /problem-templates/self_report_completion_button.html
   :language: xml

Short Answer
-----------------------------------------------

Provides a text box for student answers. Correct answers are determined using regular expressions. 'regex101'_ provides a tool for writing regular expressions.

.. _regex101: https://regex101.com/#python

.. literalinclude:: /problem-templates/short_answer-inline_display.html
   :language: xml


Short Answer - Fill In the Blank Display/Inline Display
-----------------------------------------------

Displays question text in line with the space for students to fill in.

.. literalinclude:: /problem-templates/short_answer-inline_display.html
   :language: xml


