**Read 02: Components, Classes and Callbacks**

**Applying Atomic Design**
* The first part puts biology words to the "break it down" paradigm from largest to smallest: Organism > Molecules > Atoms.
* Viewing a design this way makes it more methodical to tackle and lines up with how one would think about this in terms of HTML elements.
* The second part illustrates that templates and pages are larger than the _organism_.
* When actually implementing the design a developer should think backwards - smallest to largest. Create smaller components such as headers and image tags and group them into large components.
* Templates prevent the need for many stylesheets that may conflict with one another. By having templates there is a less likely chance that CSS overrides are needed or patterns need to be reimplemented.
* Creating a design library can solve a lot of issues in the long run but is often not prioritized by the business. For example, there is a lot of upfront cost to create a design system that delivers little short term value to the business. However, when these designs can be reused and reimplemented it speeds up feature development in the future.

**Callbacks**
* Since functions are objects, they can be used within functions as parameters.
* Callback functions are useful when needing to wait for another function to execute before proceeding onto some more logic.
* Functions can be assigned to variables and be passed as arguments.


**Review**
* Classes can be constructed and have methods such as getters and setters. Objects can be accessed using the **this** keyword. 
* Classes are more of an object oriented approach. If I recall correctly, we discussed during lecture that classes were not used too often in JavaScript as functions can achieve the same ends.