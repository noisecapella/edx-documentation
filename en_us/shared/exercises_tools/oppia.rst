.. include:: ../../links/links.rst

.. _Oppia Exploration Tool:

##########################
Oppia Exploration Tool
##########################

.. note:: EdX offers full support for this tool.

This topic describes how to embed Oppia explorations in your course.

.. contents::
  :local:
  :depth: 2

Be sure to review all supplemental materials to assure that they are accessible
before making them available through your course. For more information, see
:ref:`Accessibility Best Practices for Course Content Development`.

.. note:: The Oppia service is not available in some regions and countries.
  If Oppia service is not available in a learner's area, the learner might see
  an "image unavailable" message in the place of the referenced exploration.
  EdX strongly suggests that you provide alternative resources for learners in
  these areas.

*********
Overview
*********

You use the Oppia exploration tool to add interactive tutoring activities,
created as `Oppia`_ explorations, to your course.

The following example shows an Oppia exploration as learners see it in the edX
LMS.

.. image:: ../../../shared/building_and_running_chapters/Images/oppia.png
  :alt: An Oppia exploration in courseware.
  :width: 800


.. _Enable the Oppia Exploration Tool:

*********************************************
Enable the Oppia Exploration Tool
*********************************************

Before you can add an Oppia exploration to your course, you must enable this
tool in Studio.

To enable the Survey tool in Studio, you add the ``"oppia"`` key to the
**Advanced Module List** on the **Advanced Settings** page. For more
information, see :ref:`Enable Additional Exercises and Tools`.


***********************************
Add an Oppia Exploration in Studio
***********************************

You must :ref:`enable the Oppia exploration tool <Enable the Oppia Exploration
Tool>` before you add a component with an exploration to your course. You also
need the host URL and the ID number of the exploration you want to add.

#. On the **Course Outline** page, open the unit where you want to add the
   exploration.

#. Under **Add New Component**, select **Advanced**, and then select **Oppia
   Exploration**.

   The new component is added to the unit, with the default display name
   **Oppia Exploration**.

#. In the new component, select **Edit**.

   .. image:: ../../../shared/building_and_running_chapters/Images/oppia_studio.png
     :alt: The Edit component dialog box for an Oppia exploration in Studio.
     :width: 600

#. In the **Component Display Name** field, enter an identifying name for the
   component.

#. In the **Oppia Exploration ID** field, enter the identifier assigned to the
   exploration you want to add. For example, ``9`` or ``gC4_ggkWar-L``.


#. In the **Oppia Server URL** field, enter the host site for the exploration
   you want to add. For example, www.oppia.org.

#. Select **Save**.

   Studio does not offer a preview of your selected exploration on the Unit
   page. You can select **Preview**, or publish the unit and then select **View
   Live**.



