.. _Designing For a Mobile Experience:

###############################################
Designing Your Course For a Mobile Experience
###############################################

The percentage of learners who access MOOCs using a mobile device is
increasing every day. Most courses on edX.org can be viewed on mobile devices,
although we still recommend that learners complete graded assignments on a
desktop computer, depending on the type of assessments their courses include.
For information on which exercises and tools are mobile-ready, see the table
in the :ref:`Introduction to Exercises and Tools<Create Exercises>` section.

To make the course experience for mobile learners as rewarding as it is for
learners using desktop computers, keep the following best practices in mind as
you design, test, and run your course.

* When learners access your course in the mobile app, they progress from
  component to component by swiping through them. It might seem useful to
  include an HTML component in a unit for the purpose of providing a
  demarcation point or guiding learners to the next unit, but having to swipe
  through too many "markers" with no real course content is not a good
  experience for mobile users.

* Display names are critical for navigation on mobile devices. As you create
  course content, make sure you replace the default display names for every
  component with useful courseware component names.

* Be concise with display names and labels. Long display names and labels
  might wrap on smaller screens, or might not be easily viewable. For example,
  if several components have names that all start with the first five words
  and differ only after that, learners on mobile devices will have a difficult
  time distinguishing between components.

* Do not assume that learners are viewing your course materials on a
  particular screen size. Optimize your materials for viewing on a range of
  screen sizes. If you upload images, provide a high resolution version that
  can be zoomed in for viewing.

* When you make choices about the problem types to use for graded versus
  ungraded assignments in your course, or which problem types to present in a
  single unit, keep the mobile experience in mind. It is a best practice to
  use only mobile-ready problem types for graded assignments.

* Embedded images can be problematic. When images are rendered on different
  displays, they might display in an unintended way, for example if the aspect
  ratio is changed.

* If you make JavaScript or CSS changes that affect more than one component
  (in the XML), be aware that the component might not render in the same way
  on a mobile device as it will in the desktop. EdX recommends that you create
  components in Studio without modifying them in XML, to ensure that components
  render reliably on both mobile and desktop.


.. _Testing Your Course For Mobile Devices:

**************************************
Testing Your Course For Mobile Devices
**************************************

If you have included some of the more complex problem types, or have
customized any of the course content, edX recommends that you test your course
for multiple devices and displays.

To test the mobile experience or your course, log in to your course on a
mobile device, using a browser such as Chrome. The courseware components will
look in the browser the way that they will look in the mobile app, although
the browser header and navigation pane will not be exactly the same.


