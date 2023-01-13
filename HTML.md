HTML 

1) What is HTML?

HTML stands for Hyper Text Markup Language. It is a language of World Wide Web. It is a standard text formatting language which is used to create and display pages on the Web. It makes the text more interactive and dynamic. It can turn text into images, tables, links. More details.

2) What are Tags?

HTML tags are composed of three things: an opening tag, content and ending tag. Some tags are unclosed tags.

HTML documents contain two things:

content, and
tags
When a web browser reads an HTML document, the browser reads it from top to bottom and left to right. HTML tags are used to create HTML documents and render their properties. Each HTML tags have different properties.

Syntax
<tag> content </tag>  
Content is placed between tags to display data on the web page.


3) Do all HTML tags have an end tag?  

No. There are some HTML tags that don't need a closing tag. For example: <image> tag, <br> tag. More details.

4) What is formatting in HTML?

The HTML formatting is a process of format the text for a better look and feel. It uses different tags to make text bold, italicized, underlined. More details.

5) How many types of heading does an HTML contain?

The HTML contains six types of headings which are defined with the <h1> to <h6> tags. Each type of heading tag displays different text size from another. So, <h1> is the largest heading tag and <h6> is the smallest one. For example:

6) Diffrence between == and === ?

Double equals used as Type converting the conversion while
Triple equals used as Strict conversion without performing any conversion in operands.

7) Different type of unit in CSS ?

pixel , % , rem , em , vh , vw.

8 ) what is meta tags ?
 The <meta> tag defines metadata about an HTML document. Metadata is data (information) about data.

9) what is DOCTYPE? 

All HTML documents must start with a <!DOCTYPE> declaration.
The declaration is not an HTML tag. It is an "information" to the browser about what document type to expect.

10) Difference between undefined and null?

Null means an empty or non-existent value. Null is assigned, and explicitly means nothing.
Undefined means a variable has been declared, but the value of that variable has not yet been defined. 

11) what is specificity ?

If there are two or more CSS rules that point to the same element, the selector with the highest specificity value will "win", and its style declaration will be applied to that HTML element.

inline-style            --> 1000    
id                      --> 100
class,pseudo classes    --> 10
tag,pseudo elements     --> 1
universal               --> 0

12) How to create a hyperlink in HTML?
The HTML provides an anchor tag to create a hyperlink that links one page to another page. These tags can appear in any of the following ways:

Unvisited link - It is displayed, underlined and blue.
Visited link - It is displayed, underlined and purple.
Active link - It is displayed, underlined and red.

13) Which HTML tag is used to display the data in the tabular form?
The HTML table tag is used to display data in tabular form (row * column). It also manages the layout of the page, e.g., header section, navigation bar, body content, footer section. Here is the list of tags used while displaying the data in the tabular form:

Tag	Description
<table>	It defines a table.
<tr>	It defines a row in a table.
<th>	It defines a header cell in a table.
<td>	It defines a cell in a table.
<caption>	It defines the table caption.
<colgroup>	It specifies a group of one or more columns in a table for formatting.
<col>	It is used with <colgroup> element to specify column properties for each column.
<tbody>	It is used to group the body content in a table.
<thead>	It is used to group the header content in a table.
<tfooter>	It is used to group the footer content in a table.

14) What are some common lists that are used when designing a page?
There are many common lists which are used to design a page. You can choose any or a combination of the following list types:

Ordered list - The ordered list displays elements in numbered format. It is represented by <ol> tag.
Unordered list - The unordered list displays elements in bulleted format. It is represented by <ul> tag.
Definition list - The definition list displays elements in definition form like in dictionary. The <dl>, <dt> and <dd> tags are used to define description list.

15) What is the difference between HTML elements and tags?
HTML elements communicate to the browser to render text. When the elements are enclosed by brackets <>, they form HTML tags. Most of the time, tags come in a pair and surround content.

16) What is semantic HTML?
Semantic HTML is a coding style. It is the use of HTML markup to reinforce the semantics or meaning of the content. For example: In semantic HTML <b> </b> tag is not used for bold statement as well as <i> </i> tag is used for italic. Instead of these we use <strong></strong> and <em></em> tags

17) Define flex and Grid property and its difference ?

The basic difference between CSS Grid Layout and CSS Flexbox Layout is that flexbox was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time. 

18) Difference between var , let and const ?

### VAR
-> The scope of a var variable is functional scope.
-> It can be updated and re-declared into the scope.
-> It can be declared without initialization.
-> It can be accessed without initialization as its default value is “undefined”.
-> hoisting done, with initializing as ‘default’ value

### LET
-> The scope of a let variable is block scope.
-> It can be updated but cannot be re-declared into the scope.
-> It can be declared without initialization.
-> It cannot be accessed without initialization otherwise it will give ‘referenceError’.
-> Hoisting is done , but not initialized (this is the reason for the error when we access the let variable before declaration/initialization

### CONST
-> The scope of a const variable is block scope.
-> It cannot be updated or re-declared into the scope.
-> It cannot be declared without initialization.
-> It cannot be accessed without initialization, as it cannot be declared without initialization.
-> Hoisting is done, but not initialized (this is the reason for error when we access the const variable before declaration/initialization


19) Difference between Regular function and Arrow function ?

-> Use of this keyword: Unlike regular functions, arrow functions do not have their own this. 
-> Availability of arguments objects: Arguments objects are not available in arrow functions, but are available in regular functions. 
-> Using new keyword: Regular functions created using function declarations or expressions are ‘constructible’ and ‘callable’. Since regular functions are constructible, they can be called using the ‘new’ keyword. However, the arrow functions are only ‘callable’ and not constructible. Thus, we will get a run-time error on trying to construct a non-constructible arrow function using the new keyword.

20) What is debouncing ?

Debouncing is a programming pattern or a technique to restrict the calling of a time-consuming function frequently, by delaying the execution of the function until a specified time to avoid unnecessary CPU cycles, and API calls and improve performance.

A Debounce function is a higher-order function that returns another function, to create closure around the function parameters (func, timeout) and the timer variable.
