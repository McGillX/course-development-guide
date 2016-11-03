Course Creation Check List
============================

- Add team members as beta testers and discussion admins as appropriate

.. note:: in order to appear as staff on the discussion board, users need to be added as discussion admin or discussion moderators in addition to any other membership right they have.

- Setup grade book
- Set component release dates

General Guidelines
============================

- Whenever possible keep images small (less than 500kb)

.. example::  Do not put an image related to a problem in a separate html module if you might just as easily include it in the problem module

- Since pages can't be scheduled for release, either save the html prepared for release or enclose content in comment tags and remove them when the content is ready for students `` <!-- --> ``

- If you export/import and lose all of the html formatting, you can copy paste (ctrl-a, ctrl-c, ctrl-v) into visual studio code and then use (shift-alt-f) to automatically fix all of the formatting (indentation, newlines, etc). 

Future Proofing Course Content
===================================

- Use permalinks when linking to external content
- Avoid time sensitive references
- Use /jump_to_id when creating internal links within the courseware


Styling
========

- Use the minimum number of modules per page 
- Use a horizontal line <hr> if you want to visually separate components

- Use ``style="color:#808080"`` for text that might distract the user
 
.. code-block:: xml

    <p style="color:#808080"> Reference: "McGillX How To" </p>

Debugging
============================

- You can not put ampersands (&) in the label field of problem
- When editing/changing an image reupload, it with the same name that way it just overwrites the earlier version (note that until you clear your browser's cache the image will remain unchanged from your point of view)

Course Closing
========================

1. Set the discussion black out dates (discussion closing dates)

Under the advanced settings tab set the discussion blackout dates with the end date being 2099. See http://edx.readthedocs.org/projects/edx-partner-course-staff/en/latest/manage_live_course/discussions.html#define-when-discussions-are-closed for further details.

.. code-block:: html

    [
        [
            "2015-12-18T00:00",
            "2099-12-31T11:59"
        ]
    ]

Resources
==============

edX
-----

Reports downtimes for edX: http://status.edx.org/

Integration Tools
------------------
Tool for writing regular expressions: https://regex101.com/#python
Page Ruler for draggable or click-on problem types (useful when drawing target areas) https://chrome.google.com/webstore/detail/page-ruler/jlpkojjdgbllmedoapgfodplfhcbnbpn
