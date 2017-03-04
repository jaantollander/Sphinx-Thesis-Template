Thesis Template
===============
.. list-table::

   * - Description
     - File
   * - Master's Thesis
     - `thesis.pdf <docs/_build/latex/thesis.pdf>`_


License
-------

.. figure:: https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png
   :target: http://creativecommons.org/licenses/by-nc-nd/4.0/
   :alt: Creative Commons License

   This work is licensed under a `Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License <http://creativecommons.org/licenses/by-nc-nd/4.0/>`_


Structure of the Thesis
-----------------------
- Titlepage

  - Title
  - Subtitle
  - Author
  - Institute
  - Department
  - Date (of delivery)
  - Research mentors and advisers and their emails and institutes

- Abstract
- Contents

  - Table of contents
  - List of tables
  - List of figures

- Chapters

  - Introduction
  - Methods
  - Results
  - Discussion
  - Conclusions
  - Recommendations

- End document

  - Acknowledgements
  - References
  - Appendices


Instructions
------------
This thesis is compiled using Python package called Sphinx. Sphinx is a document creation tool that allows user to create both HTML and LaTeX from same source files.

Python dependencies can be installed through commandline using

.. code-block:: bash

   pip install -r requirements.txt

Thesis can be compiled in the ``docs`` directory using command

.. code-block:: bash

   make latexpdf
