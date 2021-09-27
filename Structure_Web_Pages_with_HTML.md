## Structure Web Pages with HTML
Hypertext Markup Language (HTML) is the primary programming language used to structure web pages. It is currently on iteration 5. It is comprised mostly of 'elements' which include an opening tag to define what part of the code is being referenced, a closing tag to say you're done with that part, and content between the tags. This can include text or other elements. 

### Page Design
The process for [creating a prototype](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/) of your web page involves several steps that should result in a quality product. 
  1. **Research**: This can include understanding your audience, understanding what they're using your page for, what the requirements are for the page, and what others in the industry are doing for similar pages.
  2. **Reference**: Take what you got from step 1 and make it into something you can actually use. A cheatsheet including your goals for both the business and the user, features you want to include, commentary from your audience, 'personas' or the type of user you want to attract, can be helpful to summarize the findings
  3. **Map User Flow**: Determine how many screens you will need, where you expect your users to be coming from, where you want them to go, etc. The goal is to help users be self-sufficient in their use of the site, minimize frustration, and otherwise make things user friendly. 
  4. **Wireframe**: Create a very basic layout for the page(s) you want to make by literally sketching them on paper or a whiteboard or something similar. You're creating the skeleton, not detailing every feature. 
    - Organize the content to support your users' goals
    - What information should be most prominent? (main message, first impressions, etc)
    - delineate certain areas to contain consistent types of information across pages
    - determine what the user needs to do what you want them to do
  5. **Details and Testing**: Add some non-content details to your page to get the pieces working together and ready for the prototype phase. This can include things like 'useability conventions' such as the location of your logo, site navigation, and search box to conform to industry norms for ease of use. Tooltips to indicate functionality, 'trust-building elements', and simple instructions are also useful. When this is done, colleagues can help give feedback on what you have for initial testing of the design
  6. **Prototyping**: After making changes based on feedback from step 5, you can start turning your wireframe into an actual page prototype. There are many tools to help convert from drawing to code such as Sketch, Figma, Framer, Adobe XD, and Proto.io. Programs such as InVision can take the result and help turn it into a proper prototype.

Three points to consider when making a good wireframe:
  1. **Clarity**: Define what the page is, what it is the user can do there, and if it is what they need.
  2. **Confidence**: A predictable site with consistent layouts is more likely to inspire confidence in users, both in the site and what its for. 
  3. **Simplicity**: Do not crowd out what your users are looking for with fluff and unrelated information. The site should guide them towards whatever it is they're looking for

### HTML Basics
A simple example page of HTML code looks like this:

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Generic Web Page</title>
  </head>
  <body>
    <img src="images/interesting-thing.png" alt="Generic Image">
  </body>
</html>
```

- The first line defines what type of document the page is.
- `<html></html>` element, aka the 'root' element, contains all content in the page
- `<head></head>` contains elements important for the page but not for the user. Things like a page description for search engines, CSS styles, what characters it's using, etc
- `<meta charset="utf-8">` defines the character set you're using. UTF-8 contains most characters from all written languages so it is useful.
- `<title></title>` sets the title of the page that appears on the browser tab
- `<body></body>` contains what you want to show to users such as text, images, links, etc.
- `<img>` is an example of such content

Other useful content tags are ones like a header such as `<h1></h1>` for things like subject titles, `<p></p>` to define paragraphs, `<ul></ul>` for unordered lists and `<ol></ol>` for ordered lists, and `<a href="https://randomwebpage.com">Insert Web Page Here</a>` for web pages.

### Semantics
The meaning of a piece of code. Something like how `<p>` defines paragraphs and `<h1></h1> is a header. HTML should be coded to reflect what it does. Leave what things look like for CSS. This helps with search engines, accessibility, finding specific code for changes or debugging, helps define what goes where, and naming conventions.

[More detailed HTML information](https://developer.mozilla.org/en-US/docs/Web/HTML)

# Site Navigation 
- [Home](README.md)
- [Growth Mindset](Growth_Mindset.md)
- [Learning Markdown](Learning_Markdown.md)
- [Coder's Computer](Coders_Computer.md)
- [Revisions and the Cloud](Revisions_and_the_Cloud.md)
- [Structure Web Pages with HTML](Structure_Web_Pages_with_HTML.md)