# What is CSS?
CSS stands for Cascading Style Sheet.
<ul>
        <li>A language to style and layout web pages</li>
        <li> Used to style font, color, spacing, layout of page, animations</li>
        <li>CSS describes how HTML elements are to be displayed on screen, paper, or in other media</li>
        <li>External stylesheets are saved as '.css'</li>
        <li>We use the 'link' tag to connect our HTML document with an external stylesheet.<br>

        <link rel="stylesheet" type="text/css" href="style.css">
</li>
</ul>
Here style.css is the name of the CSS document.

# What is CSS Rule?
The CSS Rule set consists of a selector and a declaration block.<br>

 ![CSS Rule](/images/CSSRule.PNG)
<ul>
        <li>Selector points to the HTML element that you want to style.</li>
        <li>Declaration block conatins one or more declarations seperated by semicolon.</li>
        <li>Declaration blocks are surrounded by curly braces.</li>
        <li>Each declaration consists of a CSS Property and a Value, seperated by colon.</li>
</ul>
# CSS Box Model 
<br>
<ul>
        <li> Each element in HTML can be thought of as a rectangular box.</li>
        <li> The standard box model describes the space an element takes up</li>
        <li> Each box has four edges: margin, border, padding and content.</li>
</ul>

![Box Model](/images/BoxModel.PNG)

Content : Contains Text, images, videos etc <br>
Padding : extension of content;contains background color, font size, etc <br>
Border  : Borders the elements <br>
Margin  : To add or lessen space between elements above, below or next to each other <br>
The four edges help manipulate the layout.

# CSS Selectors

Selectors help us 'select' the HTML element that we want to style.

#### 1. Simple Selectors

<br>Suppose we have the following HTML document to style:

![SimpleSelectorHTML](/images/html_SimpleSelector.PNG)

We can easily select elements like h1, p, ol, or li for styling purposes.
<br>Read more about <a href="https://www.w3schools.com/css/css_selectors.asp">Simple Selectors</a> here.
<br>
Let's assume that we wrote the following CSS to style our HTML:<br>
        
![Simple Selectors](/images/CSS_SimpleSelector.PNG)

#### What if I want the two paragraph tags to have different properties? <br>
This is where our HTML semantics; ids and classes come to play.<br>

<em>(Remember we used the ids and class attributes to uniquely identify our HTML elements and HTML semantics to divide our document into sections?)</em>

#### 2. Combinator Selectors

Let's divide our HTML using semantics and give unique ids and classes<br>

![CombinatorSelectorsHTML](/images/html_CombinatorSelector.PNG)

Now we can style the elements using <a href="https://www.w3schools.com/css/css_combinators.asp"><strong>Combinator Selectors</strong></a>
<br>
Combinator Selectors grab elements based on their specific relationship between them.<br>

![Combinator Selectors](/images/CSS_CombinatorSelector.PNG)

Read more about Combinator Selectors <a href="https://www.w3schools.com/css/css_combinators.asp">here</a>.

#### 3. Pseudo Class Selectors

A pseudo-class is used to define a special state of an element.
<br>
For example, it can be used to:
<ul>
<li>Style an element when a user mouses over it</li>
<li>Style visited and unvisited links differently</li>
<li>Style an element when it gets focus</li>
<li>Style elements alternately</li>
</ul>
<br>
Take this HTML code for reference:<br>

![Pseudo Class](/images/PseudoClass.PNG)

We use Pseudo classes to style the anchor and button tags:<br>

![Pseudo Class CSS](/images/CSS_PseudoClass.PNG)

<em>Find out which Pseudo Class Selector is used to style alternate rows of a table.</em>

#### 4. Pseudo Element Selectors

A CSS pseudo-element is used to style specified parts of an element.<br>

For example, it can be used to:
<ul>
<li>Style the first letter, or line, of an element</li>
<li>Insert content before, or after, the content of an element</li>
</ul>

<a href="https://www.w3schools.com/css/css_pseudo_elements.asp">Refer this link</a> to explore more about Pseudo Elements.

#### Difference between Pseudo class and Pseudo elements?
We use <strong>pseudo-class</strong> when we need to apply css based on the state of an element.
<br>
We use <strong>pseudo-element</strong> when we need to apply css to the specific parts of an elements or a newly inserted content.

# Task 
Recreate the following design. The important features to be included are:
1. Create tables with odd rows colored  #cccccc 
2. The link provided in the table should be:
    blue in color by default
    purple in color on hover 
    red in color if visited
3. Create a Know More button with background color of your choice and on hover, the background color and cursor should be changed.
4. The button should open this link in a new tab when clicked https://simple.wikipedia.org/wiki/Jeffrey_Archer
5. For styling of different elements use the concepts explained above.

![Task](/images/Task_.jpeg)

Make a new folder on your desktop and convert it into a zip file. Refer this link if you don't know how to make a zip file.

If you are using JS Bin to compose your code, you should be able to find an "export" or "download" option from the menu. You may need to be logged-in to JSbin for that to work. If that doesn't work for you, then simply select and copy your code from JS Bin, then paste it into a text editor, and save the document as an HTML file (with the .html extension). If you don't have a text editor installed on your machine, it is recommended that you download and use Atom/ Sublime/ Visual Studio Code/ Notepad++.

🎊CONGRATULATIONS!🎊 You are now through with your <em>Fundamentals in CSS!</em> 'clap, clap...'👏
<em>See you in the next session where we will learn about Intermediate CSS</em>
