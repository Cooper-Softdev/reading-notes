# OOP, and HTML tables

This section is important because we are taking data and then displaying it to the user. That data needs to be presented cleanly in the HTML document with minimal fuss and have the ability to be changed.

## Domaing Modeling

+ I honestly didn't fully understand Domain Modeling when I read it, I'll have to ask in class, I could have been really tired at the time as well.

## HTML Tables 

+ Tables should not be used because they reduce accessibility for visually impaired users, like those that use screen readers. They aren't responsive either, so will destroy a responsive website with their rigidity unless they're specifically made ot be responsive which is as I understand it, A TASK.
+ Some semantic tags for tables include `<tr>` which is a table *row*, `<td>` which stands for *table data*, and `<th>` *table header* which name the rows.

## Constructors

+ Constructors are objects that have the task of creating new objects easily by changing the information contained in the property of the object we are making. We want to make new stores, so we can make a constructor that just changes the things about stores that are different from each other, while most of the content will stay the same. Stores will have different names, locations, employees, but they have the same hours, we want the same data from them, so since store objects are more alike than they are different and we want many of them, a constructor can help us make them faster and easily.
+ The term `this` refers that the following code should apply only to the object literal we are currently working in and not all the other objects that also contain the same property we are about to type out.

## Obj prototypes and Inheritance

  + To make a an army we have multiple levels of ranks, soldiers with different tasks proficiencies and so on. We can define these properties and place them inside of the individual soldier to show which capabilities they have individually and can create more very easily. The pilot group will be soldier just like a medic, except they have flying inheritance from a pilot object. 