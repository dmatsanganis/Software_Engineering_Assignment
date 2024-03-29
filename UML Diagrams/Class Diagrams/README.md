## Class Diagrams
**_Class Diagrams_** is a graphical notation used to construct and visualize object oriented systems. 
A **_Class Diagrams_** in the _Unified Modeling Language (UML)_ is a type of static structure diagram that describes the structure of a system by showing the system's:

- classes,
- their attributes,
- operations (or methods),
- and the relationships among objects.

## Class Diagrams Notation
A **_Class_** represent a concept which encapsulates state (attributes) and behavior (operations). 
- Each **attribute** has a type.
- Each operation has a **signature**.
- _The class name is the only mandatory information._

![class_diagram_theory](https://user-images.githubusercontent.com/34712449/97092623-22adae80-164e-11eb-83ab-0dce2e9c9b36.png)

### Class Name:

- The name of the class appears in the first partition.

### Class Attributes:

- Attributes are shown in the second partition.
- The attribute type is shown after the colon.
- Attributes map onto member variables (data members) in code.

### Class Operations (Methods):

- Operations are shown in the third partition. They are services the class provides.
- The return type of a method is shown after the colon at the end of the method signature.
- The return type of method parameters are shown after the colon following the parameter name. Operations map onto class methods in code.

![class_diagram_theory2](https://user-images.githubusercontent.com/34712449/97092764-432a3880-164f-11eb-980f-38a67d4de2ec.png)

### Class Diagram Visibility
The +, - and # symbols before an attribute and operation name in a class denote the visibility of the attribute and operation.

![class_diagram_theory3](https://user-images.githubusercontent.com/34712449/97092810-aae08380-164f-11eb-9dfa-abef4590df5c.png)

- +: denotes public attributes or operations
- -: denotes private attributes or operations
- #: denotes protected attributes or operations

### Parameter Directionality
Each parameter in an operation (method) may be denoted as in, out or inout which specifies its direction with respect to the caller. This directionality is shown before the parameter name.

![class_diagram_theory4](https://user-images.githubusercontent.com/34712449/97113171-39f1a800-16f1-11eb-8af1-2d7e7f078792.png)

## Perspectives of Class Diagram
The choice of perspective depends on how far along you are in the development process. During the formulation of a **_domain model_**, for example, you would seldom move past the **_conceptual perspective_**. 

**_Analysis models_** will typically feature a mix of **_conceptual and specification perspectives. Design model_** development will typically start with heavy emphasis on the **_specification perspective_**, and evolve into the **_implementation perspective_**.

A **_Class Diagram_** can be interpreted from various perspectives:

- **_Conceptual:_** represents the concepts in the domain
- **_Specification:_** focus is on the interfaces of Abstract Data Type (ADTs) in the software
- **_Implementation:_** describes how classes will implement their interfaces

The perspective affects the amount of detail to be supplied and the kinds of relationships worth presenting. The class name is the only mandatory information.

![class_diagram_theory5](https://user-images.githubusercontent.com/34712449/97292772-59edac80-1854-11eb-89e0-40d9fcc73bb4.png)

## For this project you can find:
- [x] Class Diagrams first version v1
- [x] Class Diagrams second version v2
- [x] Class Diagrams third and final version v3
- [x] Class Diagrams Theory

