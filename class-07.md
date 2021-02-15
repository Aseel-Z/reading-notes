# Domain Modeling
- is a procees in which a conceptual model is build for a certain problem inside the code.
- Tips to follow:
  > - When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
    - Model its attributes with a constructor function that defines and initializes properties.
    - Model its behaviors with small methods that focus on doing one job well.
    - Create instances using the new keyword followed by a call to a constructor function.
    - Store the newly created object in a variable so you can access its properties and methods from outside.
    - Use the this variable within methods so you can access the object's properties and methods from inside.


# HTML - TABLES
- tables are grid based layout for information.
- tables are constructed using the following tags:
   - table
   - tr
   - td
   - th
- Long tables can be split *thead*, *tbody*, and *tfoot*