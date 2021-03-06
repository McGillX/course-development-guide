Problem Templates
=============================

.. note:: If you copy the templates below be sure to paste them in the advanced (xml) editor in edX Studio (Do NOT use the visual editor)

Dropdown - Inline Display
----------------------------------------------

Displays the question text inline with the dropdown menu for selecting answer options. Dropdown problems can only be programmed with one correct answer (trying to add more than one correct answer will result in only the last programmed answer being scored as correct).

.. literalinclude:: /problem-templates/dropdown-inline_display.html
   :language: xml
   
Long Answer
----------------------------------

Creates multiline textboxes for questions that require larger amounts of text.

.. literalinclude:: /problem-templates/long_answer.html
   :language: xml
   
Custom Numerical Response
----------------------------------

The template below removes alphabetical characters, percent signs and converts commas to decimal places. This avoids the error message resulting from standard edX numerical problems.

.. literalinclude:: /problem-templates/numerical_response.html
   :language: xml   
   
Self Report Completion Button
-----------------------------------------------

A button that when clicked awards points

.. literalinclude:: /problem-templates/self_report_completion_button.html
   :language: xml



