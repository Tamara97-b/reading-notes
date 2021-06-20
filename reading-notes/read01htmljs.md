# HTML #

### pages are text documents.
### HTML uses tags (characters that sit inside angled
### brackets) to give the information they surround special
### meaning.
### Tags are often referred to as elements.
### Tags usually come in pairs.
### The opening tag denotes
### the start of a piece of content; the closing tag denotes
### the end.

### Opening tags can carry attributes, which tell us more
### about the content of that element.
### Attributes require a name and a value.
### To learn HTML you need to know what tags are
### available for you to use, what they do, and where they
### can go.

## text ##
### The opening <html> tag indicates that anything between it and a closing </html> tag is HTML code.
### The <body> tag indicates that anything between it and the closing
### </body> tag should be shown inside the main browser window.
### Words between <h1> and </h1> are a main heading.
### A paragraph of text appears between these <p> and </p> tags.
### Words between <h2> and </h2> form a sub-heading.
### Here is another paragraph between opening <p> and closing </p> tags

## lists ##
### There are three tags types of HTML lists:
 ### 1)ordered.
### 2)unordered.
### Ordered lists use numbers
### Unordered lists use bullets.
### Definition lists are used to define terminology.
### Lists can be nested inside one another.

## links ##
### Links are created using the <a> element.
###  The <a> element uses the href attribute to indicate
### the page you are linking to.
### If you are linking to a page within your own site, it is
### best to use relative links rather than qualified URLs.
### You can create links to open email programs with an
### email address in the "to" field.
### You can use the id attribute to target elements within
### a page that can be linked to.
## images ##
### The <img> element is used to add images to a
### web page.
### You must always specify a src attribute to indicate the
### source of an image and an alt attribute to describe the
### content of an image.
### You should save images at the size you will be using
### them on the web page and in the appropriate format.
### Photographs are best saved as JPEGs; illustrations or
### logos that use flat colors are better saved as GIFs.
## tables ##
### The <table> element is used to add tables to a web
### page.
### A table is drawn out row by row. Each row is created
### with the <tr> element.
### Inside each row there are a number of cells
### represented by the <td> element (or <th> if it is a
### header).
### You can make cells of a table span more than one row
### or column using the rowspan and colspan attributes.
###  For long tables you can split the table into a <thead>,
### <tbody>, and <tfoot>.
## forms ##
### Whenever you want to c XX ollect information from
### visitors you will need a form, which lives inside a
### <form> element.
### Information from a form is sent in name/value pairs.
### Each form control is given a name, and the text the
### user types in or the values of the options they select
### are sent to the server.
### HTML5 introduces new form elements which make it
### easier for visitors to fill in forms.
## extra ##
### DOCTYPES tell browsers which version of HTML you
### are using.
###  You can add comments to your code between the
### <!-- and --> markers.
###  The id and class attributes allow you to identify
### particular elements.
### The <div> and <span> elements allow you to group
### block-level and inline elements together.
### <iframes> cut windows into your web pages through
### which other pages can be displayed.
###  The <meta> tag allows you to supply all kinds of
### information about your web page.
### Escape characters are used to include special
### characters in your pages such as <, >, and ©.
## vidio and oudio ##
### Flash allows you to add animations, v XX ideo and audio to
### the web.
### Flash is not supported on iPhone or iPad.
###  HTML5 introduces new <video> and <audio>
### elements for adding video and audio to web pages, but
### these are only supported in the latest browsers.
### Browsers that support the HTML5 elements do not
### all support the same video and audio formats, so you
### need to supply your files in different formats to ensure
### that everyone can see/hear them.
# javascipt #
### A script is a series of instructions that the computer
### can follow in order to achieve a goal.
### Each time the script runs, it might only use a subset of
### all the instructions.
### Computers approach tasks in a different way than
### humans, so your instructions must let the computer
### solve the task prggrammatically.
### To approach writing a script, break down your goal into
### a series of tasks and then work out each step needed
### to complete that task (a flowchart can help).
## the ABC of programming ##
### It is best to keep JavaScript code in its own JavaScript
### file. JavaScript files are text files (like HTML pages and
### CSS style sheets), but they have the . j s extension.
### The HTML <script> element is used in HTML pages
### to tell the browser to load the JavaScript file (rather like
### the <link> element can be used to load a CSS file).
### If you view the source code of the page in the browser,
### the JavaScript will not have changed the HTML,
### because the script works with the model of the web
### page that the browser has created.
## instruction ##
### A script is made up of a series of statements. Each
### statement is like a step in a recipe.
### Scripts contain very precise instructions. For example,
### you might specify that a value must be remembered
### before creating a calculation using that value.
### Variables are used to temporarily store pieces of
### information used in the script.
### Arrays are special types of variables that store more
### than one piece of related information.
### JavaScript distinguishes between numbers (0-9),
### strings (text), and Boolean values (true or false).
### Expressions evaluate into a single value.
### Expressions rely on operators to calculate a value.
## function ##
### Functions allow you to group a set of related
### statements together that represent a single task.
### Functions can take parameters (informatiorJ required
### to do their job) and may return a value.
### An object is a series of variables and functions that
### represent something from the world around you.
### In an object, variables are known as properties of the
### object; functions are known as methods of the object.
### Web browsers implement objects that represent both
### the browser window and the document loaded into the
### browser window.
### JavaScript also has several built-in objects such as
### String, Number, Math, and Date. Their properties and
### methods offer functionality that help you write scripts.
### Arrays and objects can be used to create complex data
### sets (and both can contain the other).
## the loops ##
### Conditional statements allow your code to make
### decisions about what to do next.
### Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
### are used to compare two operands.
### Logical operators allow you to combine more than one
### set of comparison operators.
### if ... else statements allow you to run one set of code
### if a condition is true, and another if it is false.
### switch statements allow you to compare a value
### against possible outcomes (and also provides a default
### option if none match).
### Data types can be coerced from one type to another.
### All values evaluate to either truthy or falsy.
### There are three types of loop: for, while, and
### do ... while. Each repeats a set of statements.
## document object ##
### The browser represents the page using a DOM tree.
### DOM trees have four types of nodes: document nodes,
### element nodes, attribute nodes, and text nodes.
### You can select element nodes by their id or cl ass
### attributes, by tag name, or using CSS selector syntax.
### Whenever a DOM query can return more than one
### node, it will always return a Nadel i st.
### From an element node, you can access and update its
### content using properties such as textContent and
### i nnerHTML or using DOM manipulation techniques.
### An element node can contain multiple text nodes and
### child elements that are siblings of each other.
### In older browsers, implementation of the DOM is
### inconsistent (and is a popular reason for using jQuery).
### cBrowsers offer tools for viewing the DOM tree ..
••