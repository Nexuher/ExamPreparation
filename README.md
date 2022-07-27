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