## Class Diagrams

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

## Class Diagram Visibility
The +, - and # symbols before an attribute and operation name in a class denote the visibility of the attribute and operation.

### Class Visibility pics
+: denotes public attributes or operations
-: denotes private attributes or operations
#: denotes protected attributes or operations
