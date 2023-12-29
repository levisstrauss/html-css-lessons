### html-css
    - This is a comprehensive base building block foundation for understanding 
      the web development process and mastering the fundamentals of HTML and CSS.

    - URL: Uniform Ressource Location
    - HTTP: Hypertext Transfer Protocol HTTPS: Hypertext Transfer Protocol Secure
    - --------> Http request (GET, POST, PUT, DELETE)
    - <-------- Http response (200, 404, 500, 301, 302)
    - 200: OK
    - 404: Not Found
    - 500: Internal Server Error
    - 301: Moved Permanently
    - 302: Moved Temporarily
    - 401: Unauthorized
    - 403: Forbidden
    - 400: Bad Request
    - DOM (Document Object Model)

### Validator
    - https://validator.w3.org/
    - https://jigsaw.w3.org/css-validator/

### Character set
    - ASCII: American Standard Code for Information Interchange
    - ISO-8859-1: Latin-1
    - UTF-8: Unicode Transformation Format
    - UTF-16: Unicode Transformation Format
    - UTF-32: Unicode Transformation Format

### Viewport element:
    - <meta name="viewport" content="width=device-width, initial-scale=1.0">

### Meta
    - Authors
    - Description
    - Keywords
    - Robots
    - Viewport

    - Name
        The name of the property can be anything you like, although browsers usually expect a value they understand
        and can take an action upon. An example would be <meta name="author" content="name"> to state the author of the page.
        
    - Content
        The content field specifies the property's value. For example, you can use <meta name="language"
        content="english">, to specify the language of the webpage to search engines.
    
    - Charset
        The charset is a special field that lets you specify the character encoding used for the page so that the browser
        can display it properly. The most frequently used is utf-8, and you would add it to your HTML header as follows:
        <meta charset="UTF-8">
    
    - HTTP-equiv
        This field stands for HTTP equivalent, and it’s used to simulate HTTP response headers. This is rare to see,
        and it’s recommended to use HTTP headers over HTML http-equiv meta tags. For example, the next tag would instruct
        the browser to refresh the page every 30 minutes: <meta http-equiv="refresh" content="30">
        
    - Basic meta tags (meta tags For SEO)
        <meta name="description"/> provides a brief description of the web page
        <meta name=”title”/> specifies the title of the web page
        <meta name="author" content="name"> specifies the author of the web page
        <meta name="language" content="english"> specifies the language of the web page
        <meta name="robots" content="index,follow" /> tells search engines how to crawl or index a certain page
        <meta name="google"/> tells Google not to show the sitelinks search box for your page when showing search results
        <meta name="googlebot" content=”notranslate” /> tells Google you don’t want to provide an automatic translation 
         for your page if the user uses a different language
        <meta name="revised" content="Sunday, July 18th, 2010, 5:15 pm" /> specifies the last modified date and time on
         which you have made certain changes
        <meta name="rating" content="safe for kids"> specifies the expected audience for your page
        <meta name="copyright" content="Copyright 2022"> specifies a Copyright
        <meta http-equiv="..."/> tags
        <meta http-equiv="content-type" content="text/html"> specifies the format of the document returned by the server
        <meta http-equiv="default-style"/>  specifies the format of the styling document
        <meta http-equiv="refresh"/> specifies the duration of the page before it’s considered stale
        <meta http-equiv=”Content-language”/> specifies the language of the page
        <meta http-equiv="Cache-Control" content="no-cache"> instructs the browser how to cache your page
        Responsive design/mobile meta tags
        <meta name="format-detection" content="telephone=yes"/> indicates that telephone numbers should appear as hypertext
        links that can be clicked to make a phone call
        <meta name="HandheldFriendly" content="true"/> specifies that the page can be properly visualized on mobile devices
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/> specifies the area of the window in which 
        web content can be seen
            
    - <meta charset="UTF-8">
    - <meta name="description" content="Free Web tutorials">
    - <meta name="keywords" content="HTML, CSS, JavaScript">
    - <meta name="author" content="John Doe">
    - <meta http-equiv="refresh" content="30">
    - <meta name="viewport" content="width=device-width, initial-scale=1.0">
    - <meta http-equiv="X-UA-Compatible" content="ie=edge">

### Body element for working with text
    ------ Heading ------
    - <h1>Heading 1</h1>
    - <h2>Heading 2</h2>
    - <h3>Heading 3</h3>
    - <h4>Heading 4</h4>
    - <h5>Heading 5</h5>
    - <h6>Heading 6</h6>

    ------ Paragraph & Text ------
    - <b>Bold text</b>
    - <p>Paragraph</p>
    - <strong>Important text</strong>
    - <i>Italic text</i>
    - <em>Emphasized text</em>
    - <mark>Marked text</mark>
    - <small>Small text</small>
    - <del>Deleted text</del>
    - <ins>Inserted text</ins>
    - <sub>Subscript text</sub>
    - <sup>Superscript text</sup>
    - <q>Quotation</q>
    - <blockquote>Long quotation</blockquote>
    - <abbr title="World Health Organization">WHO</abbr>
    - <address>Address</address>
    - <cite>Cite</cite>
    - <bdo dir="rtl">This text will be written from right to left</bdo>
    - <bdo dir="ltr">This text will be written from left to right</bdo>
    - <pre>Preformatted text</pre>
    - <code>Code</code>
    - <kbd>Keyboard input</kbd>
    - <samp>Sample output</samp>
    - <var>Variable</var>

    ------ Break & Horizontal Rule ------
    - <br>
    - <hr>

    ------ Link ------
    - <a href="https://www.w3schools.com">This is a link</a>
    - <a href="https://www.w3schools.com" target="_blank">This is a link</a>
    - <a href="https://www.w3schools.com" target="_self">This is a link</a>
    - <a href="https://www.w3schools.com" target="_parent">This is a link</a>
    - <a href="https://www.w3schools.com" target="_top">This is a link</a>
    - <a href="mailto:
    - <em>Emphasized text</em>
    - <a href="image/banner.jpg" download>This is a link</a> // This will download the image

     ------- Jump to page -------
     - <a href="#section1">Jump to Section 1</a>
     - <h2 id="section1">Section 1</h2>

     ---- Jump to the top of the page from the bottom ----
    - <a href="#">Jump to the top</a>

    ----- Link to external page -----
    - <a hrerf="https://'google.com" target="_blank">Google</a> // Open in new tab

    ----- Link to email -----
    - <a href="mailto:email>">Email</a>

    - link is the address: www.google.com
    - hyperlink is the hole thing <a href="www.google.com">Google</a>

    ----- Entities -----
    - Website: https://dev.w3.org/html5/html-author/charref
    - &lt; = <   &lt;HTML&gt; => less than
    - &gt; = >   &lt;HTML&gt; => greater than
    - &amp; = &  &lt;HTML&gt;  => ampersand
    - &quot; = "  &lt;HTML&gt; => quotation mark
    - &copy; = ©  &lt;HTML&gt; => copy right
    - &reg; = ®  &lt;HTML&gt; => registered trademark
    - &trade; = ™  &lt;HTML&gt; => trademark
    - &nbsp; =   &lt;HTML&gt; => non-breaking space
    - &cent; = ¢  &lt;HTML&gt; => cent
    - &pound; = £  &lt;HTML&gt; => pound
    - &yen; = ¥  &lt;HTML&gt;   => yen
    - &euro; = €  &lt;HTML&gt;   => euro
    - &sect; = §  &lt;HTML&gt;   => section
    - &times; = ×  &lt;HTML&gt;  => multiplication
    - &divide; = ÷  &lt;HTML&gt; => division
    - &micro; = µ  &lt;HTML&gt; => micro
    - &para; = ¶  &lt;HTML&gt; => paragraph
    - &deg; = °  &lt;HTML&gt; => degree
    - &plusmn; = ±  &lt;HTML&gt; => plus or minus
    - &sup2; = ²  &lt;HTML&gt; => superscript 2
    - &nbsp; =   &lt;HTML&gt; => non-breaking space

### Images
    - <img src="image/banner.jpg" alt="Banner" width="100" height="100">

### Video and audio
    - Website: https://www.pexels.com/videos/  // Free videos
    - Support browser: https://caniuse.com/
     NB: Dont set the height the browser will set it automatically base on the aspect ratio

    ----- Video -----
    - <video src="assets/video/ocean.mp4" width="400" controls autoplay loop>
        Your browser does not support the video tag.
      </video>
   
    ---- Audio -----
    - <audio src="assets/audio/rock.mp3" controls autoplay loop>
        Your browser does not support the audio tag.
      </audio>'

### Lists
    ----- Unordered list -----
    - <ul>
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
      </ul>

    ----- Ordered list -----
    - <ol>
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
      </ol>

    ----- Description list -----
    - <dl>
        <dt>Coffee</dt>
        <dd>- black hot drink</dd>
        <dt>Milk</dt>
        <dd>- white cold drink</dd>
      </dl>

### Table
    - <table>
        <tr>
          <th>Firstname</th>
          <th>Lastname</th>
          <th>Age</th>
        </tr>
        <tr>
          <td>Jill</td>
          <td>Smith</td>
          <td>50</td>
        </tr>
        <tr>
          <td>Eve</td>
          <td>Jackson</td>
          <td>94</td>
        </tr>
      </table>

### Container
    - <div> // This is a block element start on a new line fill the whole width
    - <span> // This is an inline element to style a text
    - <article></article> // This is a block element
    - <section></section> // This is a block element
    - <header></header> // This is a block element
    - <footer></footer> // This is a block element
    - <aside></aside> // This is a block element
    - <nav></nav> // This is a block element
    - <main></main> // This is a block element
    - <figure></figure> // This is a block element
    - <figcaption></figcaption> // This is a block element

    * Usage of perfect partitioning of the page

 ```HTML
 <header>
   <nav></nav>
 </header>

 <main>
     <section>
         <h2>Product</h2>
         <!-- To represent the top 5 product we use article -->
         <article></article>
         <article></article>
         <article></article>
     </section>
     <section>
         <h2>Testimonials</h2>
         <article></article>
         <article></article>
         <article></article>
     </section>
 </main>
 <aside>

 </aside>
<footer>
   <nav></nav>
</footer>
```
---

### Cascading Style Sheets CSS
    - One of the most important thing about dealing with CSS accross browsers is to use Normalize.css
    - Website: https://necolas.github.io/normalize.css/
    - https://necolas.github.io/normalize.css/8.0.1/normalize.css
    - Just download it or install in using npm
    - <link rel="stylesheet" href="normalize.css"> // At the top of your css file

### Selectors
    - Element selector
    - Class selector
    - ID selector
    - Attribute selector
    - Pseudo-class selector
    - Pseudo-element selector
    - Combinator selector
    - Universal selector

    -NB: The different between id and class is that id is unique and class is not unique
         we can have multiple element for the same class but not for id

    - Only use these selector if you know that the element on page will not change in the 
          future otherwise, select them based on their id or class

    ----- Basic Selectors -------
        article              All article elements
        .product             Elements with the product class
        #products            The element with the ID of products
        a[href=“...”]        Anchors with the given href
        a[href*=“google”]    Anchors whose href contains google
        a[href^=“https”]     Anchors whose href starts with https
        a[href$=“.com”]      Anchors whose href ends with .com

    ------- Relational Selectors -------
        #products p          All p elements inside #products
        #products > p        All p elements that are direct children of #products
        #products + p        The p element immediately after #products (sibling)
        #products ~ p        All p elements after #products (siblings)
        All article elements that are the first child of their parent

    - Pseudo-class Selectors 
        article :first-child      The first child of article elements
        article :first-of-type    The first occurrence of elements of different type
        article p:first-of-type   The first p element inside article elements
        article :last-child       The last child of article elements
        article :last-of-type     The last occurrence of elements of different type
        article :nth-child(odd)   The odd children of article
        article :nth-child(even)  The even children of article

    - Pseudo-element Selectors
        p::first-letter          The first letter of every p element
        p::first-line            The first line of every p element 
        ::selection              Any selected element 
        p::before                To insert content before the content of p elements
        p::after                 To insert content after the content of p elements

    - Colors
        #fcba03                  Hexadecimal value
        rgb(252, 186, 3)         RGB value
        rgba(252, 186, 3, 0.5)   Semi-transparent RGB value
        hsl(44, 98%, 50%)        HSL value
        hsla(44, 98%, 50%, 0.5)  Semi-transparent HSL value

    - Gradients
        background: linear-gradient(blue, yellow);
        background: linear-gradient(to bottom right, blue, yellow);
        background: linear-gradient(45deg, blue, yellow);
        background: linear-gradient(45deg, blue, yellow 30%);
        background: radial-gradient(white, yellow);
        background: radial-gradient(circle, white, yellow);
        background: radial-gradient(circle at top left, white, yellow);
        Semi-transparent RGB value HSL value
        Semi-transparent HSL value
        background: linear-gradient(blue, yellow);
        background: linear-gradient(to bottom right, blue, yellow);
        background: linear-gradient(45deg, blue, yellow);
        background: linear-gradient(45deg, blue, yellow 30%);
        background: radial-gradient(white, yellow);
        background: radial-gradient(circle, white, yellow);
        background: radial-gradient(circle at top left, white, yellow);

    - Borders
        border: 10px solid blue;
        border-width: 10px 20px 30px 40px;  /* top right bottom left */
        border-radius: 5px;
        border-radius: 100%; /* full circle */

    - Shadows
        box-shadow: 10px 10px;
        box-shadow: 10px 10px grey;
        box-shadow: 10px 10px 5px grey;
        text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2);

    - object-fit: cover; // This will make the image cover the whole div
    - object-fit: contain; // This will make the image fit in the div

### Layout
    - float: left; // This will make the element float to the left
    - float: right; // This will make the element float to the right
    - float: none; // This will make the element not float
    - float: inherit; // This will make the element inherit the float property from its parent
    - float: initial; // This will make the element float to the left
    - float: unset; // This will make the element float to the left

    - clear: left; // This will clear the float to the left
    - clear: right; // This will clear the float to the right
    - clear: both; // This will clear the float to the both side
    - clear: none; // This will not clear the float
    - clear: inherit; // This will make the element inherit the clear property from its parent
    - clear: initial; // This will make the element clear to the left
    - clear: unset; // This will make the element clear to the left

    - overflow: hidden; // This will make the element overflow hidden
    - overflow: scroll; // This will make the element overflow scroll
    - overflow: auto; // This will make the element overflow auto
    - overflow: visible; // This will make the element overflow visible
    - overflow: inherit; // This will make the element inherit the overflow property from its parent
    - overflow: initial; // This will make the element overflow hidden
    - overflow: unset; // This will make the element overflow hidden

    - position: static; // This will make the element static
    - position: relative; // This will make the element relative
    - position: absolute; // This will make the element absolute
    - position: fixed; // This will make the element fixed
    - position: inherit; // This will make the element inherit the position property from its parent
    - position: initial; // This will make the element position static
    - position: unset; // This will make the element position static

    - z-index: 1; // This will make the element on top of the other element
    - z-index: -1; // This will make the element behind the other element
    - z-index: inherit; // This will make the element inherit the z-index property from its parent
### Box Model
    - This is how the element are structured in the browser

     - content
        |_ padding 
            |_ border
                |_ margin

     - p: Top, Right, Bottom, Left Ex: p: 10px 20px 30px 40px; 
     - NB: Top and Bottom are the same and Right and Left are the same
     - Specifying only one value will apply to all sides
     - Specifying two values will apply first value to top and bottom, and the second value to right and left
     - Specifying three values will apply first value to top, second value to right and left, and third value to bottom
     - Specifying four values will apply to top, right, bottom, and left in that order (clockwise)

     - Padding in inside of the element and the margin is outside the element
     - If we have two elements together, their margin gets collapsed
     - Use the margin property to separate the elements
     - Use the padding property to add space between the border and the content area of an element

     ------ Box Model -------
      padding: 10px 20px;
      padding-top: 30px;
      margin: 1px 2px 3px 4px;
      margin-top: 5px;
      border: 1px solid black;
      border-top: 1px solid black;

     
### Sizing an element 
    - NB: The width and height property are appply on the content box
          Any padding or border we apply will increase the size of the element

    - The border sizing: box-sizing: border-box; // This will make the border box the same size as the content box
    - It is better to use the universal selector to apply the border sizing to all the element but not apply to sudo 
      element like box::before and box::after. the better to do this will be:

    - * , *::before, *::after
        box-sizing: border-box;
      }
    - The width and height property are appply only on block element and not on inline element but if we want to apply
      them to the inline element we have to set the display property to inline-block
    ------ Sizing an element -------
    width: 5rem;
    height: 20%;
    box-sizing: border-box;

```css
     .box {
        display: inline-block;
        width: 100px;
        height: 100px;
        background-color: red;
      }
```
    - width: 100px; // This will make the element width 100px
    - width: 100%; // This will make the element width 100% of its parent
    - width: auto; // This will make the element width auto
    - width: inherit; // This will make the element inherit the width property from its parent
    - width: initial; // This will make the element width 100px
    - width: unset; // This will make the element width 100px

    - height: 100px; // This will make the element height 100px
    - height: 100%; // This will make the element height 100% of its parent
    - height: auto; // This will make the element height auto
    - height: inherit; // This will make the element inherit the height property from its parent
    - height: initial; // This will make the element height 100px
    - height: unset; // This will make the element height 100px

    - min-width: 100px; // This will make the element min-width 100px
    - min-width: 100%; // This will make the element min-width 100% of its parent
    - min-width: auto; // This will make the element min-width auto
    - min-width: inherit; // This will make the element inherit the min-width property from its parent
    - min-width: initial; // This will make the element min-width 100px
    - min-width: unset; // This will make the element min-width 100px

    - min-height: 100px; // This will make the element min-height 100px
    - min-height: 100%; // This will make the element min-height 100% of its parent
    - min-height: auto; // This will make the element min-height auto
    - min-height: inherit; // This will make the element inherit the min-height property from its parent
    - min-height: initial; // This will make the element min-height 100px
    - min-height: unset; // This will make the element min-height 100px

    - max-width: 100px; // This will make the element max-width 100px
    - max-width: 100%; // This will make the element max-width 100

### Overflow
    - overflow: hidden; // This will make the element overflow hidden
    - overflow: scroll; // This will make the element overflow scroll
    - overflow: auto; // This will make the element overflow auto
    - overflow: visible; // This will make the element overflow visible
    - overflow: inherit; // This will make the element inherit the overflow property from its parent
    - overflow: initial; // This will make the element overflow hidden
    - overflow: unset; // This will make the element overflow hidden
    - overflow-x: hidden; // This will make the element overflow-x hidden
    - overflow-y: hidden; // This will make the element overflow-y hidden
### Measurement 
    ---- Absolute measurement ----
     - px: Pixels
        - pt: Points (1pt = 1/72 of 1in)
    ---- Relative measurement ----
    - em: Relative to the font-size of the parent (2em means 2 times the size of the current parent)
    - rem: Relative to font-size of the root element in case  we dont have a direct parent: The best one
    - vh: Relative to 1% of the height of the viewport
    - vw: Relative to 1% of the width of the viewport
    - vmin: Relative to 1% of viewport's smaller dimension
    - vmax: Relative to 1% of viewport's larger dimension
    - %: Percent relative to the size of the container
### Positioning elements

    - position: static; // This will make the element static
    - position: relative; // This will make the element relative
    - position: absolute; // This will make the element absolute
    - position: fixed; // This will make the element fixed
    - position: inherit; // This will make the element inherit the position property from its parent
    - position: initial; // This will make the element position static
    - position: unset; // This will make the element position static

    - z-index: 1; // This will make the element on top of the other element
    - z-index: -1; // This will make the element behind the other element
    - z-index: inherit; // This will make the element inherit the z-index property from its parent

    - By default the position of all element is static
    - Giving a relative position to an element we can use:
      left, right, top, bottom to move the element
```css
.box {
    position: relative;
    left: 100px;
    top: 100px;
    right: 100px;
    bottom: 100px;
    z-index: 0; <!-- All z-index are set to 0 the more bigger the number the more the element is close -->
}
```
    - If we want to place an element on top of the other:
       - The parent have to be relative and the child absolute to be move at it correct position
```css
.box-parent {
    position: relative;
    left: 100px;
    top: 100px;
    right: 100px;
    bottom: 100px;
}
.box-child {
    position: absolute;
    left: 100px;
    top: 100px;
    right: 100px;
    bottom: 100px;
}
```
### Floating elements
    - float: left; // This will make the element float to the left
    - float: right; // This will make the element float to the right
    - float: none; // This will make the element not float
    - float: inherit; // This will make the element inherit the float property from its parent
    - float: initial; // This will make the element float to the left
    - float: unset; // This will make the element float to the left

    - Use clear both property to clear the float and apply the class clear to the element

```css
.clear {
    clear: both;
}

.clearfix::after {
    content: "";
    display: block;
    clear: both;
}
```
### FlexBox 
     - Website: https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-basics-and-terminology
     - Website: https://flexboxfroggy.com/
    NB: Flexbox is one dimensional and grid is two dimensional

     - display: flex or display: grid
     - Use Flex for simple layout and grid for complex layout

    ----- Display -----
    - display: flex; // This will make the element flex horizontally
    - display: inline-flex; // This will make the element inline-flex
    - display: inherit; // This will make the element inherit the display property from its parent
    - display: initial; // This will make the element display flex
    - display: unset; // This will make the element display flex

    ----- Flex -----
    - flex-wrap: nowrap; // This will make the element flex-wrap nowrap
    - flex-wrap: wrap; // This will make the element flex-wrap wrap
    - flex-wrap: wrap-reverse; // This will make the element flex-wrap wrap-reverse
    - flex-wrap: inherit; // This will make the element inherit the flex-wrap property from its parent
    - flex-wrap: initial; // This will make the element flex-wrap nowrap
    - flex-wrap: unset; // This will make the element flex-wrap nowrap

    - flex-basis: 100px; // The initial size of the flex item
    - flex-grow: 1; // The grow factor relative to the other flex items
    - flex-shrink: 1; // The shrink factor relative to the other flex items
    -

    ------ Direction ------
    - flex-direction: row-reverse; // This will make the element flex-direction row-reverse
    - flex-direction: column-reverse; // This will make the element flex-direction column-reverse
    - flex-direction: inherit; // This will make the element inherit the flex-direction property from its parent
    - flex-direction: initial; // This will make the element flex-direction row
    - flex-direction: unset; // This will make the element flex-direction row

     - flex-direction: row; (main => Horizontal, cross || Vertical)
     - flex-direction: column; (main || Vertical, cross => Horizontal)
     - flex-direction: row, column , row-reverse, column-reverse

     - justify-content: (along the main axis) => flex-start, flex-end, center, space-between, space-around, space-evenly
     - align-items: (along the cross axis) || flex-start, flex-end, center, baseline, stretch
     - align-content: (when we have multiple line) || flex-start, flex-end, center, space-between, space-around, stretch
     - align-self: (when we have multiple line) and want a specific one || flex-start, flex-end, center, baseline, stretch

     ----------------- Recap -----------------
     flex
     selector {
        display:flex;
     }
     - flex-direction: row | column | row-reverse | column-reverse
     - flex-wrap: nowrap | wrap | wrap-reverse
     - align-items: flex-start | flex-end | center | baseline | stretch
     - justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly
     - align-content: flex-start | flex-end | center | space-between | space-around | stretch
     - flex-grow: 1 factor of flex main size
     - flex-shrink: 1 factor of flex main size
     - flex-basis: auto | factor of main size | measurement unit 
     - order: positive or negative number
     - align-self: flex-start | flex-end | center | baseline | stretch

```css
.container {
    display: flex;
    flex-direction: row; 
    justify-content: center;
    align-items: center;
    flex-wrap: wrap; // This will make the element aligned to the next page if the page is full
    align-content: center; // We apply this property if we have multiple line
    height: 90vh;
}
```

### Grid elements

    selector {
        display: grid; // or inline-grid
    }
    
    - Creating a grid 3 X 2 

```css
.container {
    display: grid;
    grid-template-rows: repeat(3, 100px);
    grid-template-columns: repeat(2, 100px);
    grid-template: repeat(3, 100px) / repeat(2, 100px); // shotcut
    border: 3px solid lightgrey;
    height: 100vh;
}
```
    - Justify-items (along the horizontal axis) || start, end, center, stretch
    - Align-items (along the vertical axis) || start, end, center, stretch

```css
.container {
    display: grid;
    grid-template: repeat(3, 100px) / repeat(2, 100px); // shotcut
    border: 3px solid lightgrey;
    justify-items: right; // An individual item in the grid
    align-items: center;
    justify-content: right; // The content of the entire grid
    align-content: center;
    height: 100vh;
}
```
    - Using fragment fr instead of %
```css
.container {
    display: grid;
    grid-template: 100px auto 100px / 30fr 70fr; // 30fr Take 30% of the available space
    border: 3px solid lightgrey;
}
```
    - Gap: Is what allow us to create space between the element: row-gap | column-gap | gap
```css
.container {
    display: grid;
    grid-template: 100px auto 100px / 30fr 70fr; 
    row-gap: 10px;     // This will create a space between the row columns
    column-gap: 10px;  // This will create a space between the column columns
    gap: 10px          // This will create a space between the row and column columns
    border: 3px solid lightgrey;
}
```
    - Placing items in the grid: grid-row | grid-column | grid-area

```css
.container {
    display: grid;
    grid-template: 100px auto 100px / 30fr 70fr;
    border: 3px solid lightgrey;
}
.place {
    grid-column: 1 / 3; // This will place the element from column 1 to 3
    grid-column: 1 / span 2; // This will place the element from column 1 to 2
    grid-row: 2; // This will place the element on row 2
    grid-row: 2 / 4; // Start on row 2 and go to row 4 or 
    grid-row: 2 / span 2; // Start on row 2 and go to row 3
    
    grid-area: 2 / 1 / 4 / 3; // Start on row 2 and go to row 4 and start on column 1 and go to column 3
}
``` 
    - Placing element in particular place in the grid by their name

```css
.container {
    display: grid;
    grid-template: 100px auto 100px / 30fr 70fr; // 30fr Take 30% of the available space
    border: 3px solid lightgrey;
    grid-template-areas: 
        "header header"
        "main sidebar"
        "footer footer";
}

.place {
    grid-area: header;
    grid-area: main;
    grid-area: sidebar;
    grid-area: footer;
}
```

### Hiding elements
    - display: none; // This will hide the element if it is not needed
    - visibility: hidden; // This will hide the element but the space will be there

### Medias queries
```css
 @media screen and (min-width: 500px) {
    .box {
        background-color: red;
    }

}

@media screen and (min-width: 500px) and (max-width: 700px) {

}

@media print {
    body{
        font-size: 10px;
    }
}
```
---
### Typography
    - Beautiful fonts website: https://fonts.google.com/ | fontsquirrel.com | https://www.dafont.com/

    ------ Font family ------
    - serif
        - font-family: Georgia, Times New Roman, Times, serif;
    - sans-serif
        - font-family: Arial, Helvetica, sans-serif, avernir, Futura, roboto;
    - monospace
        - font-family: "Courier New", Courier, monospace;

    ------ Font weight ------
      - font-weight: normal | bold | bolder | lighter | 100 | 200 | 300 | 400 | 500 | 600 | 700 | 800 | 900

    ---- Font size ----
      - font-size: 16px | 1em | 1rem | 100% | 1vw | 1vh | 1vmin | 1vmax

    ----- Font style -----
      - font-style: normal | italic | oblique

    NB: Working with the google font is easier

    - We can also set the system font
    - font-size: 1rem // This will make the font size 16px

    ------- Styling fonts -------
    Styling Fonts
    font-family: Arial, Helvetica, sans-serif;
    font-size: 1rem;
    font-weight: bold;
    font-style: italic;

    ---- Vertical Spacing ----
    margin: 3rem 0 1rem;
    line-height: 1.5;

    ----- Horizontal Spacing -----
    letter-spacing: -1px;
    word-spacing: 2px;
    width: 50ch;

    ------ Formatting Text ------
    text-align: center;
    text-indent: 1rem;
    text-decoration: underline;
    text-transform: uppercase;
    white-space: nowrap;
    direction: rtl;

    ------ Multi-column Text ------
    column-count: 2;
    column-gap: 2rem;
    column-rule: 3px dotted #999;
  
---
### Working with Images

    ------ Background Images ------
    background: url(../images/bg.jpg);
    background-repeat: no-repeat;
    background-position: 100px 100px;
    background-size: cover;
    background-attachment: fixed;

    ------ Clipping Images ------
    clip-path: polygon(50% 0%, ...);

    ------ Filters ------
    filter: grayscale(70%);
    filter: blur(3px);
    filter: brightness(0.5);
    filter: contrast(200%);
    filter: drop-shadow(10px 10px 10px grey);
    filter: hue-rotate(90deg);
    filter: invert(50%);
    filter: saturate(25%);
    filter: sepia(50%);
    filter: opacity(50%);
    filter: grayscale(70%) blur(3px);

    ------ Supporting High-density Screens ------
    Use this for fixed-size images. The browser will download the best image based on the pixel ratio of the device. 
```html
<img 
    srcset="
        image-1x.jpg 1x, 
        image-2x.jpg 2x, 
        image-3x.jpg 3x
    "
    src="image-1x.jpg" alt="Image"
>
```
    ------ Resolution Switching ------
    Use this for flexible-size images. The browser will download the best image based on the viewport size.
```html
 <img 
    srcset="
        image-1x.jpg 400w, 
        image-2x.jpg 800w, 
        image-3x.jpg 1200w
   " 
    sizes="
        (max-width: 500px) 100px, 
        (max-width: 700px) 50px, 33vw
    "
    src="image-1x.jpg" alt="Image"
 >
```
    ------ Supporting Modern Image Formats ------
   
```html
<picture>
    <source srcset="image.webp" type="image/webp">
    <source srcset="image.jpg" type="image/jpeg">
    <img src="image.jpg" alt="Image">
</picture>

```
    ------ Art Direction ------

```html
<picture>
    <source media="(max-width: 500px)" srcset="...">
    <source media="(max-width: 501px)" srcset="...">
    <img src="image.jpg" alt="Image">
</picture>
```
---
### Forms
    ------ Forms ------
```html
    <form action=“https://formspree.io/...” method=“POST”>
       <label for=“name” />
       <input type=“text” id=“name” />
       <button type=“submit”>Register</button>
    </form>
```
  
    ------ Input Types ------
```html
    <input type=“email” />
    <input type=“password” />
    <input type=“checkbox” />
    <input type=“radio” />
    <input type=“range” />
    <input type=“date” />
    <input type=“file” />
```
    ------ Grouping fields ------
```html
    <fieldset>
        <legend>Contact</legend>
        <input type=“text” />
        <input type=“text” />
    </fieldset>
```
```html
    ------ Data Validation ------
    <input type=“number” min=“0” max=“5” required />
    <input type=“text” minlength=“3” maxlength=“50” required />
```
---
### Transformations
    ------ Transformations ------
```css
    transform: rotate(45deg);
    transform: scale(2);
    transform: scaleX(2);
    transform: scaleY(2);
    transform: skewX(45deg);
    transform: skewY(45deg);
    transform: translateX(100px);
    transform: translateY(100px);
    transform: translate(100px, 100px);
    transform: rotate(45deg) scale(2) skewX(45deg) translate(100px, 100px);
    transform: rotate(45deg) scale(2) skewX(45deg) translateX(100px) translateY(100px);
    transform: rotate(45deg) scale(2) skewX(45deg) translate(100px, 100px) translateX(100px) translateY(100px);
```
    ------ Transform Origin ------
```css
    transform-origin: 50% 50%;
    transform-origin: top left;
    transform-origin: 100px 100px;
    transform-origin: 100px 100px 100px;

    transform: rotate(15deg);
    transform: rotate(-15deg);
    transform: scale(1.3);
    transform: skew(15deg);
    transform: translate(10px, 20px);
    transform: translateX(10px);
    transform: translateY(20px);
    transform: rotate(15deg) scale(1.3);
```
    ------ Transform Style ------
```css
    transform-style: flat;
    transform-style: preserve-3d;
```
    ------ Perspective ------
```css
    perspective: 100px;
    perspective-origin: 50% 50%;
    perspective-origin: top left;
    perspective-origin: 100px 100px;
    perspective-origin: 100px 100px 100px;
```
    ------ Backface Visibility ------
```css
    backface-visibility: visible;
    backface-visibility: hidden;
```
    ------ Transitions ------
```css
    transition: all 1s;
    transition: property duration timing-function delay;
    transition-property: all;
    transition-duration: 1s;
    transition-timing-function: ease-in-out;
    transition-delay: 1s;

    transition: transform .5s;
    transition: transform .5s ease-out;
    transition: transform .5s ease-out 1s;
    transition: transform .5s, color .3s;
```
    ------ Animations ------
```css
    animation: name 1s ease-in-out 1s infinite alternate;
    animation-name: name;
    animation-duration: 1s;
    animation-timing-function: ease-in-out;
    animation-delay: 1s;
    animation-iteration-count: infinite;
    animation-direction: alternate;
    animation-fill-mode: forwards;
    animation-play-state: running;
    animation: name 1s ease-in-out 1s infinite alternate forwards running;
    animation: name 1s ease-in-out 1s infinite alternate forwards paused;
```
---

### Best practices
    Follow a naming convention for naming IDs and classes.
    The most common naming conventions are PascalCase, camelCase and kabob-case.

    For a small project, you can write all of your CSS rules in one stylesheet. 
    Use CSS comments to create logical sections in your stylesheet. 
    For a more complex project, you need to separate your stylesheet into multiple files 
    and combine them together using build tools like Webpack, Rollup or Parcel.

    Avoid over-specific selectors. Limit nesting to two or maximum three selectors.

    Avoid the !important keyword as much as possible.

    Sort CSS properties. This makes it easier to read your code.

    Take advantage of style inheritance and reduce duplication in your styles.

    Use CSS variables, also called custom properties, to keep your code DRY.

    We often declare variables using the :root selector that targets the html element. We
    can then access these variables using the var() function.

    Object-oriented CSS is a set of principles for creating reusable components. The two principles in object-oriented CSS are: 1- Separate container and content. 2- Separate structure and skin.
    BEM (Block Element Modifier) is a popular naming convention for CSS classes.
    BEM is a naming convention for CSS classes. It stands for Block Element Modifier.

    --------------- rules ---------------
    ------- Naming convention -------
    BEM: Example: .block__element--modifier
    CamelCase: Example: .blockElementModifier
    Kabob-case: Example: .block-element-modifier
    PascalCase: Example: .BlockElementModifier

    ------ Stucture and skin ------

        - Basics styles
         * {}
         html {}
   
        - Typography
         h1 {}
         p {}

        - Fomrs
         .form {}
         .form__input {}
         .form__button {}
  
        - Navigation
         .nav {}
         .nav__item {}
         .nav__link {}

    -NB: Create css separate file for each section and combine them using sass or less
    
              
       

