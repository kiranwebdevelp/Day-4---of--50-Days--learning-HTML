# Day 4 challenge of 50 days HTML Learning ✨💥
## TOPIC :
- **Day 4:** HTML Attributes Understanding attributes(e.g., class, id, style).Common attributes and their usage.


<h1>HTML Attributes</h1>


<h2>Here are some common HTML attributes, their usage, and examples:</h2>

- **`class`
Assigns one or more classes to an element, which can be used for styling or JavaScript manipulation:**

     `Example` : `<p class="highlight">This paragraph has a highlight class.</p>`

- **`id`
Assigns a unique identifier to an element, which can be used for styling, JavaScript manipulation, or linking:**

  `Example` : `<p id="intro">This paragraph has an ID of "intro".</p>`

- **`style`
Adds inline styles to an element, overriding any external styles:**

  `Example` : `<p style="color: red; font-size: 24px;">This paragraph has inline styles.</p>`

- **`title`
Provides a tooltip or hover text for an element:**

  `Example` : `<p title="This is a tooltip">Hover over me!</p>`

- **`alt`
Specifies alternative text for an image, which is displayed if the image cannot be loaded:**

`Example` : 

<img src="assets/image.jpg" alt="A beautiful mountain scenery">

- **`src`
Specifies the source URL of an image, script, or link:**

`Example` : 

<img src="assets/image.jpg">

- **`href`
Specifies the link URL for an anchor element:**

   `Example` : <a href="https://www.example.com">Visit example.com</a>

- **`target`
Specifies the target window or frame for a link:**

   `Example` : <a href="https://www.example.com" target="_blank">Open in new tab</a>

- **`rel`
Specifies the relationship between the current document and the linked document:**

  `Example` : <a href="https://www.example.com" rel="nofollow">No follow link</a>

- **`data-author`
Custom data attributes, which can be used to store additional information about an element:**

  `Example` : `<p data-author="John Doe">This paragraph has a custom data attribute.</p>`

<h1>In-Depth Concept:</h1>

<p> The class Attribute
The class attribute is used to assign one or more classes to an HTML element. Classes are used to group elements together, making it easier to style or manipulate them using CSS or JavaScript.</p>

- **`Multiple Classes`
An element can have multiple classes, separated by spaces:**

  `Example`  : `<p class="highlight important">This paragraph has two classes.</p>`

- **`Class Selectors`
In CSS, you can use class selectors to target elements with a specific class:**

  `Example` : `.highlight { color: red; } targets all elements with the class highlight.`

- **`JavaScript and Classes`
In JavaScript, you can use the classList property to manipulate an element's classes:**

  `Example`: `const elem = document.querySelector('.highlight'); elem.classList.add('new-class'); adds a new class to the element.`

#
<h1>Best Practices
When using the class attribute, follow these best practices:</h1>

- **Use meaningful and descriptive class names.
Avoid using IDs as class names, as IDs should be unique.**
- **Use class names consistently throughout your project.**

- **Use a consistent naming convention (e.g., BEM or SUIT).**

- **Avoid overusing classes, as it can lead to CSS bloat.**