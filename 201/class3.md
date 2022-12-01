# readingnotes03

++Ordered and Unordered lists**

When should you use an unordered list in your HTML document? when grouping items that dont have numerical ordering
How do you change the bullet style of unordered list items? by using .css style commands. specifically the list-style-type  property
When should you use an ordered list vs an unorder list in your HTML document? when grouping items that have numerical importance or order.
Describe two ways you can change the numbers on list items provided by an ordered list? using type
type Sets the numbering type:

a for lowercase letters
A for uppercase letters
i for lowercase Roman numerals
I for uppercase Roman numerals
1 for numbers (default)

or using stylesheet

## box model and css

Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”? box model means everything in css has a box around it. margin and padding serve by telling the boxes how big or small they are, and what is to be pushed away from the box
List and describe the four parts of an HTML elements box as referred to by the box model.

- Content box: The area where your content is displayed; size it using properties like inline-size and block-size or      width and height.
- Padding box: The padding sits around the content as white space; size it using padding and related properties.
- Border box: The border box wraps the content and any padding; size it using border and related properties.
- Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.

## js

What data types can you store inside of an Array? numbers, strings, arrays, objects
Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why? yes. it is a multidimensional array. get to pete by "people[0][0] "

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
List five shorthand operators for assignment in javascript and describe what they do.

- += means to add something to the original value
- -+ means to subtract something from the original value
- *= means to multiply something against the original value
- /= means to divide something by the original value e. %/ means to divde by and take remainder of the original value

Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
(a + c) is 10 + false, or 10 + 0 and evaluates as a number (10 + b) is 10 + dog which evaluates as a string, so concatenates as 10dog

Describe a real world example of when a conditional statement should be used in a JavaScript program. when deciding what parts of a page a user has access to based on input.
Give an example of when a Loop is useful in JavaScript. password requirement
