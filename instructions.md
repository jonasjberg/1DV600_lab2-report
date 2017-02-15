Analysis, Design and Implementation
===================================

* Source: [tobias-dv-lnu/1dv600-lab/wiki](https://github.com/tobias-dv-lnu/1dv600-lab/wiki/Assignment-2)
* Local source: 

In this assignment you are going further with your planning to the phases
analysis, design and implementation. In this, you will find out the value of
planning and also how successful you were at it in the first place. To perform
the tasks in this assignment you will need use diagrams from UML, primarily use
case and sequence diagrams.

Remember that all assignments are individual!


Task 1 -- Analysis
------------------
In analysis is focus is on what to do rather than how to implement it. In the
subtasks you will be using UML in different ways to perform an analysis on the
library system that you began with in the previous assignment.

### Subtask A -- Identifying Use Case
The UML way of documenting requirements is through use cases and in this first
task you are to identify and document the use cases used in the system. When
documenting a use case, it is customary to specify initiation, pre and post
conditions, the primary flow as well as some additional ones. Do this for two
of your use cases and describe the flows using activity
diagrams. 
Also write down your own reflections on identifying use cases and documenting
them in about 100 words.

### Subtask B -- Robustness Diagram
A non­standardised, but yet highly valuable diagram, in UML is the robustness
diagram in which in a way is a simplification of communication and
collaboration diagrams. They are used to analyse the steps of a use case and
validate the business logic for them, that the use cases are sufficiently
robust to represent the usage requirements for the system. Create
robustness diagrams for the use cases you identified in task a. In your
reflection document you write down about 100 words on your experience using
robustness diagrams.

### Subtask C -- Use Case Realization
To specify more in detail what a use case is supposed to do, i.e. to realize
it, it is common to use sequence diagrams. In the previous assignment you
implemented the use case "List Books" and in this subtask you are to
show a use case realization of that in the form of a sequence diagram. In
addition to that, do the same for the use case "Delete Book.
Again, write down your reflections on use case realisations in about 100 words.


Task 2 -- Design
----------------
In this task you are to design the logic to fetch books in XML format (a
suitable XML file is supplied). After reading the XML file it should be
converted into objects in the running system and lastly translated into JSON
for the web browser.
Notice that this is a design task and therefore suitable design diagrams from
UML are to be used to describe your solution (i.e. not code). You need to
identify objects used in this and what messages they are sending, and when. As
with the previous tasks, we also like you to write down your reflections in
about 100 words.


Task 3 -- Implementation
------------------------
Take the design you created in task 2 and implement it in the system. In
addition to that, also implement Delete Book without first designing
it. Describe your reflections on the two approaches in about 100 words.


Include in the submission
-------------------------
The following should be included in the submission that you hand in via Moodle:

* Suitable diagrams; use case, activity, robustness, sequence
* Design with diagram and description
* Implementation (/src for Java and /app for Node.js)
* Report with all personal reflections
* Time log
