# Reading 03

### Topic

Understanding how to arrange and manipulate data and types seems to me to be the core of most programming.. I think. I don't know programming so I'm probably very wrong on that. But it sounds correct.

## Ordered and Unordered lists

1. Unordered lists should be used when the things listed don't need a particular order. Packing list items for a camping trip for example.
2. Bullit style can be changed with `list-style-type: cirle, disc, square`, and more. You can even replace bullits with a photo.
3. Ordered lists are for things that need to be ordered specifically, like instructions on making food where adding eggs after the cake has finished baking would not be ideal.
4. Numbers are changed like bullit points, `list-style-type: decimal, upper-roman, lower-alpha`.

## CSS Box Model

1. Mr. Margin maintains the fence around the psychiatric ward, ensuring no other psych ward patients from competing loonybins get too close. Ms. Padding surround the patient, ensuring they don't hurt themselves on the inside walls of the ward itself. Keeping a safe distance.
2. + Content is the actual text inside the HTML we want the user to see.
    + Pading is between the content and the border of the HTML. Giving it a standoff distance from the border itself. It is invisible and just serves to create whitespace.
    + Border surrounds the padding, this is a line, or box that separates the content from the rest of the page visually. It can be dashed or dotted and any color.
    + Margin is the space outside of the border itself. Serves the same purpose as padding but for external bits. Ensuring no other content gets too near the Border and fk'n up the Feng Shui of your sweet doc, bro.

## Arrays, Ops, Exprs, Conditions and l00ps

1. All data types can be stored in an array. I think. Numbers, Strings, Booleans, Objects/Functions? these are similar? Would you like to know more? Undefined variables even, Null values and weird Symbols.

2. You'd have to make a variable, assign it the value of people, then bracket the items you want. Person 2 would be [1] and if you wanted their job you'd put [3] behind it, so

    > `const nameHobbies = people[1][2];`
    >
    > `console.log(nameHobbies);`

3. The JavaScript shorthand operators are.

    1. `+=` is the Add/Assign, it will add the proceeding number to the variable number on the left and then assign the sum of those as the new value of the used variable. `y = y - 10`
    2.  `-=` Subtract/Assign is the same as the last but does subtraction instead.
    3. `*=` Multiply/Assign does the same as the last two but with mutiplication.
    4. You get the idea, the last two are `/=` and `%=` which divides and the other gives the remainder, respectively.
>

4. The expression will evaluate to the string '10dog' because false will be coerced into a value of `0` which leaves `10` with the same value. Then `10` will just get concatenated into the string `'dog'` since numbers just get turned into strings when added to a string. I think.

5. Conditional statement would be useful for a website or 2FA asking for a pin number, if the pin number is wrong, do nothing/continue denying access. If true, grant access.

6. Adding up the total amount of transactions within a specific timeframe. If the PoS system lists transactions by value and date/time, then that array, if it is an array, can be put into a loop that adds the value of that particular transaction to i until all transactions are exhausted in the array.

## Things I want to know more about

+ are objects and functions the same in javascript? or are they different?