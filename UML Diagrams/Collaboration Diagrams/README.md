# Collaboration Diagrams 
**_Collaboration Diagrams_** are used to show how objects interact to perform the behavior of a particular use case, or a part of a use case. Along with sequence diagrams, **_collaboration_** are used by designers to define and clarify the roles of the objects that perform a particular flow of events of a use case.  They are the primary source of information used to determining class responsibilities and interfaces.

## What is a Collaboration Diagram?
- A Collaboration is a collection of named objects and actors with links connecting them. They collaborate in performing some task.
- A Collaboration defines a set of participants and relationships that are meaningful for a given set of purposes.
- A Collaboration between objects working together provides emergent desirable functionalities in Object-Oriented systems.
- Each object (responsibility) partially supports emergent functionalities.
- Objects are able to produce (usable) high-level functionalities by working together.
- Objects collaborate by communicating (passing messages) with one another in order to work together.

## Why Collaboration Diagram?
Unlike a sequence diagram, a collaboration diagram shows the relationships among the objects. Sequence diagrams and collaboration diagrams express similar information, but show it in different ways.

Because of the format of the collaboration diagram, they tend to better suited for analysis activities (see Activity: Use-Case Analysis).   Specifically, they tend to be better suited to depicting simpler interactions of smaller numbers of objects.  However, if the number of objects and messages grows, the diagram becomes increasingly hard to read.  In addition, it is difficult to show additional descriptive information such as timing, decision points, or other unstructured information that can be easily added to the notes in a sequence diagram. So, here are some use cases that we want to create a collaboration diagram for:

Model collaborations between objects or roles that deliver the functionalities of use cases and operations
Model mechanisms within the architectural design of the system
Capture interactions that show the messages passing between objects and roles within the collaboration
Model alternative scenarios within use cases or operations that involve the collaboration of different objects and interactions
Support the identification of objects (hence classes) that participate in use cases
Each message in a collaboration diagram has a sequence number.
The top-level message is numbered 1. Messages sent during the same call have the same decimal prefix but suffixes of 1, 2, etc. according to when they occur.

- [x] Collaboration Diagrams first version (v1).
- [x] Collaboration Diagrams second and final version (v2).


