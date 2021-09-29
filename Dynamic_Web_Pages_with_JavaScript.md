# Dynamic Web Pages with JavaScript
JavaScript is a versatile [just-in-time](https://en.wikipedia.org/wiki/Just-in-time_compilation) programming language used in both web pages and non-web environments like Adobe Acrobat. Standards for it are known as [ECMAScript Language Specification](https://tc39.es/ecma262/) and [ECMAScript Internationalization API specification](https://tc39.es/ecma402/). There is documentation through MDN that can be referenced.

In JavaScript, variables act as containers for data storage. For example,

> `var x = 10`

is stores the *number* 10 while

> `var x = '10'`

stores the *string* 10. Anything inside single or double quotes is considered a string. A string of numbers can be converted into actual numbers but acts differently depending on the context.

Variabiles must be identified with unique names in order to not overwrite values. The variable must begin with and can contain a letter, $, or _, and can contain numbers as well. They are case sensitive, and cannot be reserved words like keywords.

An `=` is an 'assignment' operator, meaning it gives the value to the variable.  To get 'equal to' you use `==` instead. For example

> `x = x + 5`

makes no sense algebraically, but in JavaScript it would take the value you previously gave `x` and add `5` to it, then assign this new value as the value of `x` from then on.

To 'declare' a variable, i.e. create it, you use `var`. If you don't specify the value of the variable it is `undefined`. You can declare the variable and set the value either separately or together.

> `var x;`
> 
> `x = 10;`

has the same effect as 

> `var x = 10`

It is a good programming practice to declare all variables at the beginning of a script. You can declare multiple variables with a single `var` by separating each with a `,` and then ending with `;`. For example:

> `var x = 5, y = 1, z = 6;`

or 

> `var x = 5,`
> 
> `y = 1,`
> 
> `z = 6;`

behave the same way and declare all 3 variables with 1 `var`.

If the variable in question requires something like user input or later calculation, leaving it `undefined` can be useful.

Re-declaring a variable will not erase a prior value. 

> `var x = 5;`

> `var x;`

would still have `x` have the value `5`.

Arithmetic can be done with variables. Numbers will follow mathematical operations but adding strings will 'concatenate' or tack on each following string.

> `var x = 6 + 4 + 1;`

will output `11` but 

> `var x = 6 + 4 + '1';`

will output `101` because it adds up to `10` then tacks on the string `'1'` to the end of it. However

> `var x = '6' + 4 + 1;`

will output `641` because it converts all subsequent numbers to strings, so be careful.

# Site Navigation 
- [Home](README.md)
- [Growth Mindset](Growth_Mindset.md)
- [Learning Markdown](Learning_Markdown.md)
- [Coder's Computer](Coders_Computer.md)
- [Revisions and the Cloud](Revisions_and_the_Cloud.md)
- [Structure Web Pages with HTML](Structure_Web_Pages_with_HTML.md)
- [Design Web Pages with CSS](Design_Web_Pages_with_CSS.md)
- [Dynamic Web Pages with JavaScript](Dynamic_Web_Pages_with_JavaScript.md)