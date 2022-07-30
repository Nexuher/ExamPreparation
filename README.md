# Main usage of this README
I'm typing this file in order to learn and see usage of technologies from: 
- **Repetytorium + Testy Klasyfikacja EE.09 / Inf.03/ Technik Informatyk/Programista**
-  See usage of **HTML/PHP/JavaScript/CSS/SCSS** code in progress while learning alone from index.html code in ExamPreparation repositorium.
# 2.1 - Web Application Notes
## Website technologies
***Front-End 
Executed by client/user browser Explicit Code*** 
Examples:  
- HTML
- CSS
- JavaScript
- SVG - Scallable Vector Graphics

***Back-End
Executed by Server Hidden Code*** 
Examples:  
- .NET
- Java
- Python
- PHP
- SQL DataBases
 # History of the development of hypertext languages
![What Is HTML? Hypertext Markup Language Basics for Beginners](https://www.hostinger.com/tutorials/wp-content/uploads/sites/2/2021/10/html-historical-milestones.png)
# (0.01 Github Commands)
- Ls/dir 
- git status 
- Cd 
- git-init 
- git add < file >
- git add .
- git commit -m < text  > 
- git push 

# 2.2 HTML Document
Every pointer is limited by a < > tags as it's called.

- Most of tags has an atributes, atributes have their own values
 **<//h1 class="x">2.1 Web Technologies</h1//>**
 
**Above as described:**
- h1- a heading descibing a size of the text.
- class = "x" - is a declaration of class where we can change style in css file later.
- 2.1 Web Technologies - is a normal text
- /h1 is ending of a header 
# Types of tags
 - **Spared** - type of which we open an element of HTML f.e.  // < title > and second is used to close it , </ title >
- **NonSpared** - type where we only use opening statement f.e // < b > or < hr >
# Definitions
- **Declaration of document type** - Defined mostly by DTD standard (ang. Document Type Definition) in which we create website. There's 3 types of documents
- **Strict**
- **Transitional**
- **Frameset**
- **Definition of an document** - Defines language in which the website was written (mostly used < html >)
- **Document Header** -  Has informations abot website which isn't showed in browser. Mostly used tags is title is:
- **< title >** - defines title of website
- **< style >** - defines style sheets
- **< link >** references other HyperText document (css,sccs)
- **< meta >** Includes specific information about website, coding, keywords, author's data.
# Coding of Polish characters
Used in < meta > tag,
- ISO 8859-2
- UTF- 8
- Windows-1250
# Document Content 
Area of website between < body > and </ body > tags.
Includes what's on the website.
# HTML Tags
All HTML Tags can be divided into groups:
**Tags that:**
- Edit and format text
- Creates references
- Divide website
- Creates tables and Forms
- Adds Multimedia elements and API

# 2.3 Basic Tags of HTML Language
**Edit and formatting tags: (At the start are things we put between <> tags to get specific effect.)**
	
- <b>b.tekst</b>
- <i>i.tekst</i>
- <u>u.tekst</u>
- <s>s.tekst</s>
- <mark>mark.tekst</mark>
 - <em>em.tekst</em>
- <sub>sub.tekst</sub>
- <sup>sup.tekst</sup>
- <strong>strong.tekst</strong>
- <dfn>dfn.tekst</dfn>
- <small>small.tekst</small>
**Special editing document tags in HTML Document**
- & quot; ---&quot;
- & amp; --- &amp;
- & plusmn;  ---&plusmn;
- & sect;  ---&sect;
- & euro;  ---&euro;
- & lt;  ---&lt;
- & gt;  ---&gt;
# Tags editing line and block elements
**Block elements** - Fragments which **cannot be put** next to eachother in the same line. F.e:
**Line elements** - **can** be put next to each other
- < h1 > - < h6 >
- Paragraph < p >
- vertical line - < hr>
- Preformat block < pre>
- Quote block < blockquote>
- Divider < div>
- Inventory tag < ol>, < ul>
- fieldset < fieldset>
- < figure>
**To Line element:**
- < span>
- Short quote < q>
- Creating a reference < a>

# Breakline
**< br>** is used to jump to next line, nothing else.
# Paragraph
Part of loger text which includes **one or more sentences** making a certain logical **whole of content or thought**.
- Text creating a paragraph are placed inside of a < p> and< /p> tag.
- Next paragraphs are placed **one after another.**
# Headings
They divide website on logically divided parts by giving them specifical format, depending on used header. 
- We're using < h1> to < h6> header, **the bigger the number, the smaller the text is**.
# Lists
Lists allow for creating **systematized groups of information**. We can use:
- Lists unstructured **(pointed)**
- Lists structured **(numbered)**
# Numbered list (structured)
In order to create numbered list, we have to use:
- **< ol> </ ol>** which creates new element list.
- Adding new element to the list is added by pointer:
- **< li> Text inside </ li>** 

Pointer < ol> has a type atribute allowing us for **describing the type of bullet point used in the list**
- A - numbering according to capital letters
- a - numbering according to lowercase letters
- I - numbering according to large Roman numerals
- i - numbering according to small Roman numerals
- 1 - numbering by Roman numerals
# Lists unstructured **(pointed)**
In order to create unstructured list, we have to use:
- **< ul> </ ul>** which creates new element list.
- Adding new element to the list is added by pointer:
- **< li> Text inside </ li>** 

Pointer < ul> has a type atribute allowing us for **describing the type of bullet point used in the list**
- Disc (default)
- Circle
- Square

Beside Lists unstructured and pointed there's a possiblitity to create **nested lists**. Which is list with pointers, We can create it using combination of previously talked about tags.
# References (links)
Job of references is **creating a connection of changing websites/files/subpage.**
We have:
- **References Absolute**: to website in URL Format
- **Reference Relative:**  to a resource specified by an access path.

Example of **Reference Absolute**:
< a href="http://www.wsip.pl"> Text here < /a> 

Example of **Reference Relative**:
< a href="C:\WebsiteFolder\index.html"> Text here < /a> 

References on website are shown as **active elements**.
They are:
- Default colour (blue)
- They are underlined 
- After pointing mouse at it or choosing link, colour of text is changed.
# HTML 5
In newest version of HTML 5, changes have been introduced in relation to HTML 4.01. The most important are:
- ***New dividers***
- - **< header>**,
- - **< footer>**,
- - **< nav>**,
-  - **< article>**,
-  - **< section>**,
- ***Tag atributes to create forms:***
- - **number**,
- - **date**,
- - **time**,
- - **calendar**,
- - **range**,
- Support for graphics on the site f.e **< svg> < canvas>**,
- Multimedia support **< audio>** and **< video>**,
# 2.4 Page splitting and data handling in HTML
From html 4.01 standard to splitting a page into functional parts, we've used elements called **blocks, boxes or conteners.**

Elements between < div> </ div> are easy to fill with, load specific subpage and use inside or outside formatting.

One of many ways to define formatting of div are: 
- **Class** / CSS class,
- **Id** / ID of an element,
- **Title** / Text to show after pointing mouse at it,
- **Align** / Centering element content horizontally
- **dir** / describing text inside of a block
# Sections
With HTML 5, new block elements have been introduced which can take over role of div, which specifies role of specific parts of HyperText.
- < article >
- < header>
- < nav>
- < section>
- < aside>
-  < footer>
# Headers Sheet
![](https://scontent-vie1-1.xx.fbcdn.net/v/t39.30808-6/218370203_207781431263554_6134652891722567958_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=730e14&_nc_ohc=TKw565fzdYwAX8eNaUi&_nc_ht=scontent-vie1-1.xx&oh=00_AT87rLNk0HlZ0PPDtK5fmaCOFUC-xC50WHkxOhsnjsXnDQ&oe=62E64A74)
# Tables
Tables allow for **easy and clear presentation** of information, text, photos or graphics in websites. 

They are used to show data in **tabular(tabelarycznej)** form
- **< table> </ table>** / tags describing area of a table
- **< tr> </ tr>** /  row of a table
- **< td> </ td>**  / cell of a table
- **< th> </ th>** / column header cell
- **< caption> </ caption>** Title of a table

Atributes of a table
- **Colspan** / merger of columns
- **Rowspan** / merger of rows
- **Cellpadding** / margin of cell
- **Cellspacing** / cell spacing size
- **Border** / Size of < table>, < tr>, < td>
- **Width** / width of table tr td
- **Height** / size of table tr td
- ** Valign** / centering text vertically in the cells
-  **Align** /  centering text horizontally in the cells
- **bgcolor** / fill color
# Forms
The form is used to **collect and send certain data for the purpose intended by the author.**

Data can be send to **email or used in script by users or serwer side.**
We start < form> </ form>. 
We can use: 
- **< input>** / creating form fields\
- **< select>** / creating drop-down lists (rozwijane listy)
- **< textarea>** / creating description fields
- **< fieldset>** / framing cell form
- **< legend>** / describtion of form cell
- **< label>** / field label for the tag

# 2.5 Color on Websites
Color is an important parameter for presenting content on a website. 

The choice of color palette not only determines the aesthetics of the sites, but also **determines its readability and accessibility**

**Color is a visual impression created by the interaction of electromagnetic waves from the frequency band of visible light.**
Color models describe specific colour pallets, to default colour pallets in graphics and websites we describe as:

 1. RGB model - Colour made from 3 basic colours, **Red, Green, Blue**
 2. HSL model - Each colour can be described by 3 atributes Shade, Saturation, Brightness.
 3. CMYK model - Colour made from 4 colour Cyan,Magenta,Yellow,Black
 4. HVS model - Colour made from 3 parametres - Hue,Saturation,Value
 
 In HTML documents we can use color notations:
 - **Verbal**
 - <body bgcolor= "red"> (inside of website) </ body>
 -  **Hexadecimal code**
 -  <body bgcolor= "#FF0000"> (inside of website) </ body>
 -  **RGB Color**
 - <body bgcolor= "rgb(255,0,0)"> (inside of website) </ body>
 - **RGBA code**
 - < div style="background-color: rgba(0, 255, 0, 0.1)> block stuff </ div>
 - HSL Code
 -  < div style="background-color: hsl(0%, 100%, 50%)> block stuff </ div>
 
 # 2.6 Graphics and Multimedias in Websites
 Static graphic:
 In order to input a graphic or photo to website we use **< img>**

 **Required parameter inside < img> is scr which shows path to the photo which will open in website after downloading itself.** 
Other atributes of  img are:
- **alt** // shows text for people who have troubles with sight or for people whose browser doesn't show graphics
- **Height** - height of a graphic in pixels
- **Width** - width of a graphic in pixels
- **Ismap** - element gives access to server image map
- usemap - **Assigns the img element to the map element**, the value of the usemap attribute must be the name with the **crosshairs (krzyzykiem) of the map element**

F.e:
< img  src="C:\X\Y\Photo" alt="Rysunek" width="128"
height="128">
Mostly used HTML extensions for static digital graphics to set inside HTML code are:
- JPG,
- JPEG
- PNG
- ICO
- APNG
- GIF
# Image/Picture map
On the graphic in webside we can create a **Map of references - create a cross-reference from the selected graphic area.** After hovering mouse over it, on specific area, we can turn on defined reference in code

**Standard mapping looks like this:**
- < img src="c\x\x.jpeg" usemap="#name">
- < map name="name"> 
- < areashape="rect" coords="1,1,50,50" href="index.html">
- </ map>

Shape atributes:
- rect - rectangle area
- circle - circle area
- poly - poly area
- default - whole graphic area

Coords define -  defines the cross-reference curve. For each type of area, coords can acquire specific atributes:
- Rect: 4 values, left, right height, width
- Circle: 3 values, left, right,  radius of the circle
-  Poly:  Angle vertices(Wierzchołki kąta) coordinates 

# SVG Container. 
HTML 5 allows to use tags which dynamically creates in browser graphic defined by < svg> tag. SVG is a language based on XML used to describe 2'd Vector Graphic.

SVG can be put directly in HTML 5 code. < svg> tag defines area where we can put:
- < rect>
- < circle>
- < ellipse>
- < line>
- < polyline> 
- < polygon>
- < path> 

Basic atributes for < svg> are width and height. 

# Element Canvas
Other element allowing to draw graphic directly in browser is < canwas>. It definec a container which we can fill with a color, text, other geometric shapes or other graphic photo.

< canvas  id="Rysunek"  width="300"  height="300"  style="border: 1px solid#000000;"> < /canvas>

# Multimedia in websites
Multimedias represent group of files including audio and video. 

**Mostly used type files for audio:**
- Wav,
- Mid,
- Midi,
- mp3,
- ogg,

**Mostly used type files for video and animation:**
- avi,
- mpeg,
- mp4,
- asf,
- swf,

Some of these types need special extensions added to browser called a **plug-in or a plug**.

**To add multimedia files on website we use < embed>**. If browser doesn't use embed then we use **< object>**.

To input video, we use < video>. To standard atributes we include:
- **src** - defines URL path to file
- **poster** - defines pathway to graphic which will be shown while loading a video.
- **autoplay** - automatic playback during video loading
- **controls** - shows display of the control panel
- **loop** - video playback loop
# 3 Cascading CSS style sheets
CSS is a language to **create sheets**, a files which helps us to **define features for specific tag i.e. their appearance on the website.** CSS is a powerful tool, it can define multiple layouts at the same time. 

**The use of style sheets has gradually replaced or removed the tags and tag attributes used to format the content of the page**.

HTML is used is used currently to **describe insides of website, but Style sheets are used to define layout of a website.** 

# 3.1 Creation of CSS sheet structure
Each cascading style sheet **consists of a list of rules specifying how the selected HTML tag or block will be displayed**.

Defining CSS style is subject to a rule in the W3C specification.

The **style** consists of **rules**, and each **rule** consists of a **selector** and a **declaration**, and the **declaration** consists of **properties** to which **certain values are assigned**
F.e:
![Anatomy of a CSS Declaration – A CSS Adventure](https://cssworkshop.files.wordpress.com/2015/03/css-declaration.png)
![Anatomy of a CSS declaration. Inside of a selector class called .selector there is a declaration of background-image: url(‘parchment.jpg’); Arrows label the property (background-image), the function (url), and the argument (parchment.jpg).](https://i2.wp.com/css-tricks.com/wp-content/uploads/2020/04/LV2OI0TM.png?fit=1024%2C333&ssl=1)

**The selector can be a selected element of the page or a group of elements that need to be formatted**.
# Methods of adding styles in HTML file
The inline method (typed, local style) **uses the style attribute for the selected HTML language tag.**
- < p style="text-align: center; color: blue;">

In the embed method in the < head> header (interior style) Style sheet defines in HTML document header **inside < style> </ style> .**

< head>
< style>
p {text-align: center; color: blue;}
</ style>
< / head>

**Method of linking to an external file (external style):**

Creating external file which includes sets of rules. **File is saved with .css extension and next defines connection by < link> tag in head header** to connect we use: 

< link  rel="stylesheet"  type="text/css"  href="CssFile.css">

**Each browser has its own Style Sheet**, additionally each user can add his own style from Inspector Mode in browser.
# Cascading style sheets
Defines the order in which the style is applied, depending on the method of appending its code to the formatted HTML document