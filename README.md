# HTML

<aside>
💡 WHAT IS HTML<br><br>
  HTML (HyperText Markup Language) is the standard language for creating and designing documents on the World Wide Web. It structures web content and provides the basic building blocks for web pages.
<br><br>
</aside>

<aside>
💡 WHY HTML IS USED<br><br>
  HTML is used to create and structure sections, paragraphs, and links on web pages. It is the backbone of any web development process, ensuring that content is organized and displayed correctly in web browsers.
<br><br>
</aside>

<aside>
💡 What is Emmet & List 5 Emmet<br><br>
  Emmet is a plugin for text editors that improves HTML and CSS workflow. It allows developers to write abbreviated code that can be expanded into full HTML and CSS code.

<br>5 Emmet abbreviations:<br>

<br>1.! - Expands to a basic HTML5 boilerplate.
<br>2.ul>li*5 - Creates a 'ul' with 5 'li' elements.
<br>3.div.container>div.row>div.col*3 - Creates a nested structure of div elements.
<br>4.a{Click me} - Creates an anchor tag with text "Click me".
<br>5.table>tr*3>td*2 - Creates a table with 3 rows, each having 2 cells.
<br><br>
</aside>

<aside>
💡 SHORT CUT CREATE of Emmet Boiler plate of HTML<br><br>
  1.The shortcut to create an HTML boilerplate using Emmet is ! followed by pressing the Tab key.
  <br>2.html:5
  <br><br>
</aside>

<aside>
💡 WHAT STRUCTURE OF HTML
  <br><br>
## HTML Structure Example

To create a basic HTML structure with a head section, header, main content, and footer, you can use the following HTML code:

```html
<html>
  <head>
    <title>page title</title>
    <!-- meta tags -->
  </head>
  <body>
    <header><!--head and navbar content--></header>
    <main><!--main content of the page--></main>
    <footer><!--footer content--></footer>
  </body>
</html>
```
<br><br>
</aside>

<aside>
💡 WHAT IS **HEAD** TAG
  <br><br>
## HTML Head Section Example

To include the following HTML `<head>` section in your web page, you can use this code:

```html
<html>
 <head>
  <title>Page Title</title>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles.css">
  <meta name="description" content="short message less than 250 characters">
  <meta name="keyword" content="max 5-6 key words related to the content">
  <meta name="author" content="name of the author">
</head> 
</html>
```
<br><br>
</aside>

<aside>
💡 WHAT IS BODY TAG
  <br><br>
## HTML Structure Examples

  ```html
<html>
    <body>
    <header>
        <h1>logo navbar of the Website</h1>
    </header>
    <main>
        <p>the main content of the page.</p>
    </main>
    <footer>
        <p>&copy; reservation Website</p>
    </footer>
</body>
</html>
```
<br><br>
</aside>

<aside>
💡 IMPORTANT 3 ELEMENTS OR TAGS
<br><br>
  
  ```html
<h1>Heading</h1>
<p>paragraph</p>
<button>click</button>
```
<br><br>
</aside>

<aside>
💡 WHAT IS DIFFERENT B/W ELEMENTS & TAGS IN HTML
  <br><br>
In HTML, a tag is the markup used to define the start and end of an element, while an element includes the start tag, content, and end tag.

For example:

Tag: p<br>
Element: 

```html
<p>This is a paragraph.</p>
```
<br><br>
</aside>

# CSS

<aside>
💡 WHAT IS CSS <br><br>
CSS (Cascading Style Sheets) is a stylesheet language used to design the websites.<br><br>
</aside>

<aside>
💡 WHY IS CSS<br><br>
It improves the user experience by making websites easier to navigate and device-responsive.
<br><br>
</aside>

<aside>
💡 HOW TO CONNECT HTML & CSS , Tell the emmet Shortcut<br><br>
To connect HTML and CSS, you use the <link> tag within the <head> section of your HTML document. The Emmet shortcut to create this link is:

```html
link:css
```

This expands to:

```html
<link rel="stylesheet" href="style.css">
```
<br><br>
</aside>

<aside>
💡 HOW TO GET FONT & COLOR , IMAGE, CDN
  <br><br>
Font: Use Google Fonts by including a <link> in the <head> of your HTML. Example:

```html
<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
```

Color: Define colors in your CSS using hex Example:
```css
body {
    color: #333;
    background-color: #f0f0f0;
}
```

Image: Use the <img> tag in HTML or the background-image property in CSS. Example for HTML:

```html

<img src="image.jpg" alt="Description">
```

Example for CSS:

```css
body {
    background-image: url('image.jpg');
}
```

CDN: imagekit.io is used to load image ,video ,audio on documents.<br><br>
</aside>

<aside>
💡 BASIC CSS FAMILY : Text Family, Color & Background Family, Box Model<br><br>
Text Family:

<br>font-family: Specifies the font.
<br>font-size: Sets the size of the font.
<br>font-weight: Defines the thickness of the font.
<br>text-align: Aligns text horizontally.
<br>text-decoration: decorate by some styles like underline ,overline,strike..

<br>Color & Background Family:

<br>color: Sets the color of text.
<br>background-color: Sets the background color.
<br>background-image: Sets a background image.
<br>background-size: Specifies the size of the background image.
<br>background-repeat:it controls the repeatation of the bg.
<br>background-position:determines the position of bg.
<br>background-opacity:view can be adjusted through it.

<br>Box Model:

<br>margin: Space outside the border.
<br>border: Surrounds the padding and content.
<br>padding: Space inside the border.
<br>width and height: Size of the content area.
<br><br>
</aside>

<aside>
💡 WHEN TO USE **BACKGROUND IMG** VS **IMG TAG**<br><br>
Background Image:

<br>Used for decorative images,like text overlay etc ..
<br>Does not affect document flow.
<br>Positioned using CSS.
<br>Example:

```css
body {
    background-image: url('background.jpg');
}
```

<br>Image Tag:

<br>Used for content images.
<br>Affects document flow.
<br>Can have alt attributes for accessibility.
<br>Example:

```html
<img src="image.jpg" alt="Description">
```
<br><br>
</aside>

<aside>
💡 WHAT IS LAYOUT & Explain About flexbox Properties
  <br><br>
Layout: Refers to the arrangement of elements on a web page.

<br>Flexbox Properties:

<br>display: flex;: Defines a flex container.
<br>flex-direction: Defines the direction of the flex items (row, column).
<br>justify-content: Aligns items horizontally (flex-start, flex-end, center, space-between).
<br>align-items: Aligns items vertically (flex-start, flex-end, center, stretch).
<br>flex-wrap: Specifies whether flex items should wrap or not.<br><br>
</aside>

<aside>
💡 WHAT IS TAILWIND CSS & WHY IS IT USED<br><br>
Tailwind CSS is a utility-first CSS framework that provides low-level utility classes to build custom designs directly in your HTML. It is used because it allows for rapid development, encourages reusable and composable design patterns, and offers a high level of customization without writing traditional CSS.
<br><br>
</aside>
