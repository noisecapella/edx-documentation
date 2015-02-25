.. include:: ../links.rst

.. _Enable Entrance Exams:

######################################################
Enable Entrance Exams
######################################################

In the Open edX Birch release, a new feature allows course staff to create an
entrance exam for the course. Learners must pass the entrance exam before
participating in the course.

To enable this feature on your instance of Open edX, you must enable
entrance exams in Studio and the Learning Management System.

For information about entrance exams, see the *Building and Running an
Open edX Course* and *Open edX Learner's* guides.

.. Note::  
  Before proceeding, review :ref:`Guidelines for Updating the edX Platform`.

.. include:: configure_milestone_app.rst

*************************************************************************
Enable Entrance Exams in Studio and the Learning Management System
*************************************************************************

#. Set the value of ``ENABLE_ENTRANCE_EXAMS`` in the
   ``/cms/envs/common.py`` and ``/lms/envs/common.py`` files to ``True``.
   
   .. code-block:: bash

     # Entrance exams feature flag
     'ENABLE_ENTRANCE_EXAMS': True,

#. Save the ``/cms/envs/common.py`` and ``/lms/envs/common.py`` files.
   