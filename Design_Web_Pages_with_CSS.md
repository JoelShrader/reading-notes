# Design Web Pages with CSS
Cascading Style Sheets (CSS) is a 'rule-based" programming language used to specify things like the layout and style of a web page, from text color to animations. Rule-based means your code lays out rules to apply specific groups of styles to specific elements of the web page.

An example of this is:

```
h1 {
    color: red;
    font-size: 5em;
}
```

In this case, `h1` is the element being altered. The colon (:) separates the property on the left from the value on the right. So `color` is a property, and `red` is the value we're setting it to. The {} enclose the declarations for each element being altered.

## Modules in CSS
Modules are sets of rules in CSS to do specific things so you don't have to reinvent the wheel every time. Resources like the Mozilla Developer Network (MDN) are repositories for such things. CSS is specified by part of the World Wide Web Consortium (W3C) called the CSS Working Group. When new features are developed they aren't always compatible with all browsers quickly, so be sure to check compatibility through something like MDN.

## External CSS
Instead of combining the HTML and CSS code for each page, you can separate the two and use the CSS file to standardize the look of the whole website. In the `<head>` section of the HTML files you can refer to a specific CSS file to govern the look of your site with the `<link>` element. For example, 
> `<link rel="stylesheet" href="sitestyle.css">`

## Internal CSS
If you want a page to look different than your external CSS style, you can use this. You use the `<style>` element to wrap around CSS code inside the `<head>` element. All else is the same.

## Inline CSS
This is used to change specific elements within the HTML code itself. For example, to change a header to be blue in the center you can put

> `<h1 style="color:blue;text-align:center;">Header</h1>`

## Multiple Style Sheets
If you have multiple style sheets, the *last* one read will apply. So if you have an external CSS followed by an internal CSS, the internal CSS will apply where applicable.

## Cascading Order
The order of priority for various CSS code is as follows:
    
    1. Inline style
    2. External/Internal style
    3. Browser default

## Color Properties
There are a myriad different ways to specify a color, such as a HEX value, RGB value, and it's name. You can look them up on [tables](https://www.w3schools.com/cssref/css_colors.asp) to get specific colors for text.

# Site Navigation 
- [Home](README.md)
- [Growth Mindset](Growth_Mindset.md)
- [Learning Markdown](Learning_Markdown.md)
- [Coder's Computer](Coders_Computer.md)
- [Revisions and the Cloud](Revisions_and_the_Cloud.md)
- [Structure Web Pages with HTML](Structure_Web_Pages_with_HTML.md)
- [Design Web Pages with CSS](Design_Web_Pages_with_CSS.md)
- [Dynamic Web Pages with JavaScript](Dynamic_Web_Pages_with_JavaScript.md)
- [Programming with JavaScript](Programming_with_JavaScript.md)
- [Operators and Loops](Operators_and_Loops.md)