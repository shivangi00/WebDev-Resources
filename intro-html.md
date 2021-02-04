# 📖 What we will cover in this week
1. What is HTML and its components
2. HTML lists and attributes
3. <img> element + <a> hyperlinks
4. HTML elements - inline + block and divs
5. ids and classes
6. Semantics
7. Tables 
8. Forms

# 1.1 💻 HTML (Hyper Text Markup Language )
i)   a markup language that provides description for structuring/ layout of a webpage. <br>
ii)  enclosed in tags; <br>
iii) <opening tags> Any sample content will go here </closing tags> <br>
iv)  provides nesting of code i.e. one thing wraps inside the other. <br>
v)   saved as .html file <br>

    <html>    
    <head>
    <title> Sample Text </title>
    </head>
    <body>
        Sample text.
    <!--This is a comment in HTML-->
    </body>
    </html>

Here, 'html' tag has 'head' and 'body' tags within it, or we can say 'head' and 'body' are 'nested' inside <html> tag.
Similarly, 'title' tag is nested within 'head' tag.
HTML is not case sensitive i.e. you can write 'html' or 'HTML' it is one or the same thing.
Note that comments in HTML are written in (<!-- ) (-->) format. Addding comments, helps anyone reading the code to understand it. Comments are not displayed on the webpage.

# 1.2 Components of HTML File

Let's take a look at a sample html document

    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <title> My First Website </title>
        </head>
        <body>
            <h1> This is heading 1. The biggest heading.</h1>
            <h2> This is heading 2</h2>
            <h3> This is heading 3</h3>
            <h4> This is heading 4</h4>
            <h5> This is heading 5</h5>
            <h6> This is heading 6. This is the smallest available heading</h6>
            <p> This is a paragraph. Paragraphs by default          ignore          the extra spaces.
            Even if you 
            write it like this. 
            It will still come up in a line.
            But if I insert <br>
            My text comes in a new line.
            </p>
            <p> You can make me <strong> bold </strong> or <em> italic </em>!
            </p>
        </body>
    </html>

Starting from line 1 - DOCTYPE tells the browser that this document is of html type. <br>
'html' tag wraps the entire document    <br>
'head' contains the information for the browser which we will learn later in the section. Its content is not displayed in the webpage. <br>
'meta' sets the character set (usually 'utf-8'), which includes most characters needed in a language <br>
'body' contains all the content that is displayed on webpage <br>
'hn' n = 1, 2, 3, ...6 The heading tags, as per the name, provide headings of different font sizes. <br>
'p' paragraph tag contains detailed content. It ignores any extra spaces.   <br>
'br' is used to break the line within the <p> tag.  <br>
'strong' makes text bold    <br>
'em' lays emphasize or makes text italic    <br>
Also note, the heading 'hn' and paragraph 'p' tags are nested within the 'body' tag.

# 👩‍💻 Let's get our hands dirty with writing some code!

Think about your favourite recipe. What is your go-to snack? How do you prepare it? If you don't know, look up the recipe online. <br>

Open your code editor and create an HTML document for the same and include the following - <br>

i. Write the html document's head content same as given in above examples and add a title to your html document.    <br>
ii. Give a h1 heading to the document and a paragraph explaining what the dish is about.    <br>

<em>Great Job! You have just created your first HTML document!</em> <br>

# 2. 📝 HTML Lists and attributes

HTML Lists  -   Lists are a very useful tool. Read <a href="https://www.w3schools.com/html/html_lists.asp">this</a> to know how to use them.   <br>

#### 🔧 TASK 1    <br>
What if you want to change the bullet style from circle to square? OR   <br>
What if you don't want to number the list but use Roman Numerals instead?   <br>
Find out how can this be done!  <br>

HTML Attributes   -   Attributes allow you to add extra information/ design to your HTML text. Click <a href="https://www.w3schools.com/html/html_attributes.asp">here</a> to know more.  <br>

# 👩‍💻 Time to share your recipe with the world!
Go back to your Recipe website and add the following: <br>

i.  An unordered list of all the ingredients needed to make the dish.    <br>
ii. An ordered list, detailing the steps you need to take to prepare that dish. <br>

# 3. 🔗 'img' and 'a' tags

Images add visual appeal to any webpage and are hence important. Anchors allow you to add links, both external and internal(to be covered later) to your document. <br>
'img' element in HTML - Go through <a href="https://www.w3schools.com/html/html_images.asp">this</a> article.   <br>
anchor 'a' tags in HTML - Go through <a href="https://www.w3schools.com/html/html_links.asp">this</a> article   <br>

# 👩‍💻 Activity Time!
<em>A website without a picture? Come on, let's add some visual aid to our recipes!</em><br>
i.  Add an image to the document showing the final project. <br>
ii. Search for 5 more recipes and add their links with a 'square' style unordered list. <br>

# 4. 🧱 Inline and Block Elements

Inline Elements - generally merge themselves with the text content and do not start from a new line <br>
E.g.    'a' Anchors    <br>
        'img' Image  <br>
        'strong' Bold    <br>
        'em' Emphasizing <br>

Block Elements - create a 'block' round the content placed in them and mostly start from a new line <br>
E.g.    'hn' Headings <br>
        'p' Paragraphs <br>
        'ul' , 'ol' Lists  <br>
        'li' List Items    <br>
        
Another block element is 'div' which groups your content or creates 'divisions' wherever required. It is used only for organisation or styling purposes.  <br>

<em>Are you feeling overwhelmed? Why not take a break? Take some time out to move around the room a little bit, have something to eat. Let's start after some time...</em>
<br>
# 5. ✏️ classes and ids 

class attribute   -  a name given to html elements (both block and inline) for ease in styling (will be discussed later). More than one element can have the same class name. A single element can have multiple class names, just add space between the two names.
<br>
id attribute    -   this specifies a unique name for html elements and remains unique throughout the HTML document.<br>

    <html>
    <head>
    <meta charset="utf-8">
    <title>Class Example</title>
    </head>
    <body>
        <h1>Classes</h1>
        <div class="text">
               <p>This div block element has class name 'text'.</p>
        </div>
        <div class="text content">
               <p>This div block has two class names 'text' and 'content'</p>
        </div>
        <div id="Unique">
               <p>This is an id attribute.</p>
        </div>
     </body>
     </html>

Difference between class and id?    <br>
Class names are not unique. <br>
Ids are unique. <br>

# 6. ⚙️ Semantics
Semantics are an integral part of learning HTML. It provides logical structuring to the code. Read <a href="https://www.pluralsight.com/guides/semantic-html">this</a> article to know more about it. <br>

# 👩‍💻 Time to structure our Recipe webpage
Open your Recipe html file and do the follwing: <br>
i.  Divide the content within body tag into 'header', 'main', 'div' and 'footer.' <br>
ii. Give each of these a class name and a unique id.

# 7. 📉 Tables
Make tables using html 'table' tag  <br>
Read <a href="https://www.tutorialspoint.com/html/html_tables.htm">this</a> and try your hands on tables.  <br>

# 8. ⚙️ Forms
When you want to Log In or Sign Up at a website, you fill a form. <br>
When you want to Register somewhere, you fill a form. <br>
In short, forms are everywhere!
Read <a href="https://www.w3schools.com/html/html_forms.asp">this</a> to know basics of forms. <br>
Watch <a href="https://youtu.be/vj78j_Sy3uM">this video</a> to try out more features!  <br>

# 👩‍💻 Finish your Recipe webpage!
Lastly, create a feedback form at the end using input fields for name, email and radio buttons for selecting feedback.

To earn extra credits, you can use atmost 3 new features that we have not covered in this tutorial.
Then, add comments to your HTML, to explain the purpose of each section of code that you create.

Make a new folder on your desktop and convert it into a zip file. Refer this link if you don't know <a href="https://www.wikihow.com/Make-a-Zip-File">how to make a zip file</a>.
<br> 

If you are using JS Bin to compose your code, you should be able to find an "export" or "download" option from the menu. You may need to be logged-in to JSbin for that to work. If that doesn't work for you, then simply select and copy your code from JS Bin, then paste it into a text editor, and save the document as an HTML file (with the .html extension). If you don't have a text editor installed on your machine, it is recommended that you download and use Atom/ Sublime/ Visual Studio Code/ Notepad++.
<br>

<em>🎊CONGRATULATIONS!🎊 You have come halfway through to making your own website! 'clap, clap...'👏</em><br>
See you in the next session where we will learn more about adding style to our HTML document. <br>

