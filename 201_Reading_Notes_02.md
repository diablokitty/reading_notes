# Reading notes for day two of 201

We are continuing review from the Introduction to HTML documentation on the Mozilla Developer Network(MDN) webpages.

### Readings for today are:

-HTML Text Fundamentals
-HTML Advanced Text Formatting

Questions from these readings:

1. Why is it important to use semantic elements in our HTML?

Semantics help us to understand the meaning, intent or important of elements on a web page. They are really both indicators and shortcuts, as it is possible to create the same visual effect by other means, but they may also help other coders understand what  original programmer's reason for using certain elements.

2. How many levels of headings are there in HTML?

There are six levels of headings, identified as h1, h2, h3, h4, h5 and h6. The headings decrement in size, so h1 is huge and bold and h6 is tiny but also bold.

3. What are some uses for the <sup> and <sub> elements?

Dates, chemical formula, mathmatical equations, also if you like formatting to appear a certain way (like superscripted cents after your dollar amounts for money).

4. When using the <abbr> element, what attribute must be added to provide the full expansion of the term?

The title attribute needs to be used to provide full expansion of the abbreviated term. (It's good to note that <abbr> is now used for both abbreviations and acronyms, as the <acronym> tag has been deprecated.)

### Additional reading is from How CSS is Structured (same source webpages).

Questions from this section:

1. What are ways we can apply CSS to our HTML?

We can use an external stylesheet, and internal stylesheet, or inline styling to apply CSS to our HTML documents

2. Why should we avoid using inline styles?

Inline styling is messy. It can be hard to find and keep updated and can have unpredictable effects on the appearance of our website, especially if an external stylesheet is also applied. Generally, external stylesheets are preferred. The exception to this is restrictive enviornments like CMS systems, that don't offer the opportunity to separate CSS from HTML.

**Review this block of code:**

      h2 {
     color: black;
     padding: 5px;
   }

Answer the following questions:

3. What is representing the selector? 

The selector in this example is h2. That is the element that the style will be applied to.

4. Which components are the CSS declarations?

The CSS declarations are the two complete instructions - "color: black" and "padding: 5px". They give the element to be transformed and the instruction for what change to make.  

5. Which components are considered properties?

The properties are the elements being changed. In this case the color of the text, and the padding (the space between the text and any border specified, visible or not). 

## Additional reading in Javascript Basics

Answer the following questions:

1. What data type is a sequence of text enclosed in single quote marks?

A string can be enclosed in both single and double quotation marks.

2. List 4 types of JavaScript operators.

Four javascript operators are addition, (really all the math ones are one type), strict equality (which isn't used nearly as often as it should be in so many contexts), does not equal (which sounds like it should be a math type but actually isn't), and assignment.

3. Describe a real world Problem you could solve with a Function.

One problem that can be managed with a function is routing packages. If a package is is marked for one location, it would be routed to the truck for that location, else if (see what I did there?) it's marked for a different location, it would be routed to the truck for that location, else if the marking isn't legible, it would be routed to the garbage heap, and its existence would be utterly and vehemently denied by the post office. Maybe.

## More reading in Making Decisions In Your Code – Conditionals.

Answer questions:

1. An if statement checks a __ and if it evaluates to ___, then the code block will execute.

Condition, true (sort of, because it could be saying it's true that the condition is false, binary makes everything wacky).

2. What is the use of an else if?

Else if gives you and additional condition or  set of conditions to evaluate if you fail the first time around. (I.e, She'd go out with you if you're good looking, else if you're rich, else nope.)

3. List 3 different types of comparison operators.


< Less than
=/= Not equal to
<= Less than or equal to

All of these have opposites, which are also comparisons, and Markdown has decided to also use some of them as formatting directions. So there's that.

4. What is the difference between the logical operator && and ||?

&& evaluates multiple conditions and all must be true for the conditional to be evaluated as true.

|| evaluates multiple expressions and only one has to return as true for the conditional to be evaluated as true.

## Things I want to know more about:

I need to re-read and then play around with event handlers later tonight. 

[back to Table of Contents](./README.md)