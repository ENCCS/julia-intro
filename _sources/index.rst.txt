Introduction to programming in Julia
====================================


Julia is a scientific programming language that is free and open
source - see the `official website <https://julialang.org/>`_ for downloads, documentation,
learning resources etc. Bridging high-level interpreted and low-level
compiled languages, it offers high performance (comparable to C and
Fortran) without sacrificing simplicity and programming productivity
(like in Python or R).

Julia has a rich ecosystem of libraries aimed
towards scientific computing and a powerful in-built package manager
to install and manage their dependencies. Julia is also gaining ground
in both data science and high-performance computing (HPC), thanks to a rich 
package ecosystem around data analysis and visualisation, machine learning, 
deep learning, threading and distributed-memory parallelisation, 
as well as GPU computing.

This lesson covers the basics of Julia: its syntax,
multiple-dispatch paradigm, package development and best practices. 
It spans the necessary foundational skills required to follow the two other 
ENCCS lessons on Julia:

- `Julia for High Performance Scientific Computing <https://enccs.github.io/julia-for-hpc/>`__
- `Julia for High Performance Data Analysis <https://enccs.github.io/julia-for-hpda/>`__


.. prereq::

   - Experience in one or more programming languages.
   - Basic familiarity with a command line (terminal) interface.

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Prerequisites

   setup

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: The lesson

   motivation
   syntax-intro
   overview
   development
   scientific-computing

.. toctree::
   :maxdepth: 1
   :caption: Reference

   quick-reference
   guide



.. _learner-personas:



Who is the lesson for?
----------------------

This lesson is appropriate for researchers, engineers and analysts from academia, 
industry or the public sector who want to adopt a new programming language into their 
repertoire. It also represents the prerequisite knowledge to follow other ENCCS lessons 
on Julia - `Julia for High Performance Scientific Computing <https://enccs.github.io/julia-for-hpc/>`__
and `Julia for High Performance Data Analysis <https://enccs.github.io/julia-for-hpda/>`__.



About the lesson
----------------

This lesson is developed by `ENCCS <https://enccs.se/>`__ - the Swedish node of the EuroCC network.
It is open source and can be reused and remixed in derivative work; see detailed 
license information below.



See also
--------

Many excellent learning resources exist for the Julia language.
For an overview, visit https://julialang.org/learning/.



Credits
-------

The lesson file structure and browsing layout is inspired by and derived from
`work <https://github.com/coderefinery/sphinx-lesson>`_ by `CodeRefinery
<https://coderefinery.org/>`_ licensed under the `MIT license
<http://opensource.org/licenses/mit-license.html>`_.
We have copied and adapted most of their license text.



Instructional Material
^^^^^^^^^^^^^^^^^^^^^^

This instructional material is made available under the
`Creative Commons Attribution license (CC-BY-4.0) <https://creativecommons.org/licenses/by/4.0/>`_.
The following is a human-readable summary of (and not a substitute for) the
`full legal text of the CC-BY-4.0 license <https://creativecommons.org/licenses/by/4.0/legalcode>`_.
You are free to:

- **share** - copy and redistribute the material in any medium or format
- **adapt** - remix, transform, and build upon the material for any purpose,
  even commercially.

The licensor cannot revoke these freedoms as long as you follow these license terms:

- **Attribution** - You must give appropriate credit (mentioning that your work
  is derived from work that is Copyright (c) ENCCS and individual contributors and, where practical, linking
  to `<https://enccs.github.io/sphinx-lesson-template>`_), provide a `link to the license
  <https://creativecommons.org/licenses/by/4.0/>`_, and indicate if changes were
  made. You may do so in any reasonable manner, but not in any way that suggests
  the licensor endorses you or your use.
- **No additional restrictions** - You may not apply legal terms or technological measures 
  that legally restrict others from doing anything the license permits.

With the understanding that:

- You do not have to comply with the license for elements of the material in
  the public domain or where your use is permitted by an applicable exception or limitation.
- No warranties are given. The license may not give you all of the permissions
  necessary for your intended use. For example, other rights such as
  publicity, privacy, or moral rights may limit how you use the material.



Software
^^^^^^^^

Except where otherwise noted, the example programs and other software provided
with this repository are made available under the `OSI <http://opensource.org/>`_-approved
`MIT license <https://opensource.org/licenses/mit-license.html>`_.
