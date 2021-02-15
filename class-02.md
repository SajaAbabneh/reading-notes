# Text 

**When creating a web page, you add tags to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.**

* **Structural markup:** the elements that you can use to describe both headings and paragraphs.

* **Semantic markup** : which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation.

# Heading 

**HTML has six "levels" of headings , The contents of an <h1 element is the largest, and the contents of an <h6 element is the smallest.**

![Heading](./image2/heading.PNG)

# Paragraph 

**To create a paragraph, surround the words that make up the paragraph with an opening <p
tag and closing </p tag.**


# Bold & Italic 

**By enclosing words in the tags <b and </b we can make characters appear bold.**

![Bold](./image2/bold.PNG)

**By enclosing words in the tags <i and </i we can make characters appear italic.**

![Italic](./image2/italic.PNG)

# Superscript & Subscript

* **<sup** : The <sup element is used to contain characters that should be superscript such
as the suffixes of dates or mathematical concepts like raising a number to a power.

* **<sub** : The <sub element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical
formulas .

![subp](./image2/sub.PNG)

# White Space

**When the browser comes across two or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single space too. This is known as ***white space collapsing*****.

![space](./image2/space.PNG)

# Line Break
**if you wanted to add a line break inside the
middle of a paragraph you can use the line break tag <br.**

![breakline](./image2/br.PNG)

# Horizantal Rule

**To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the <hr tag.**

![Horizantal](./image2/hr.PNG)

# Semantic markup

**There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the
pages.**

# Strong tag

**The use of the <strong  element indicates that its content has ***strong importance.*****

![strong](./image2/strong.PNG)

# emphasis tag

**The <em element indicates emphasis that subtly changes the meaning of a sentence.**

![emphasis](./image2/em.PNG)

# Blockquote tag

**The <blockquote element is used for longer quotes that take up an entire paragraph**.

**The <q element is used for shorter quotes that sit within a paragraph.**

![quote](./image2/q.PNG)

**The <abbr tag defines an abbreviation or an acronym, Use the global title attribute to show the description for the abbreviation oracronym when you mouse over the element.**

# Citations tag

**The <cite tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture),The text in the <cite element usually renders in ***italic*****.

![cite](./image2/cite.PNG)

# Defintion tag 

**The <dfn tag stands for the "definition element", and it specifies a term that is going to be defined within the content.**

![definition](./image2/dfn.PNG)

# Address tag

**The <address element has quite a specific use: to contain contact details for the author of
the page.**

![address](./image2/address.PNG)

# ins and del tag 

**The <ins element can be used to show content that has been inserted into a document, while
the <del element can show text that has been deleted from it.**

![ins](./image2/ins.PNG)

# S tag

**The <s element indicates something that is no longer accurate or relevant (but that should not be deleted).**

![s](./image2/s.PNG)

---

# CSS

**CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a ***selector and a declaration*****.

![css](./image2/css.PNG)

**CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.**

![cs](./image2/cs.PNG)

**Using External CSS**

![link](./image2/li.PNG)

# Selectors

![selector](./image2/selector.PNG) ![n](./image2/n.PNG)

---

# Basic JavaScript Instructions

***Statements*** : **A script is a series of instructions that a computer can follow one-by-one.
Statements should end with a semicolon(;).**

## COMMENTS 

 **can be used to explain JavaScript code, and to make it more readable,can also be used to prevent execution, when testing alternative code.**

 * Single line comments start with //.
 * Multi-line comments start with /* and end with */.

 ## WHAT IS A VARIABLE?

 **JavaScript variables are containers for storing data values.**
  
  ![declartion var](./image2/var.PNG)

  **How to assign value to var**:

  ![signvar](./image2/sign.PNG)

  ## DATA TYPES

  **JavaScript distinguishes between Numbers,
Strings, and Booleans.**

* var length = 16;  **Number**
* var name = "Saja"; **String**
* var chech=true; **Boolean**

## SHORTHAND FOR CREATING VARIABLES

![short](./image2/d.PNG)

## RULES FOR NAMING VARIABLES
* Names can contain letters, digits, underscores, and dollar signs.
* Names must begin with a letter.
* Names can also begin with $ and _ .
* Names are case sensitive (y and Y are different variables).
* Reserved words (like JavaScript keywords) cannot be used as names.

## Arrays

**An array is a special type of variable. It doesn't just store one value; it stores a list of values.**

### **Creating an Array**

* var array_name = [item1, item2, ...];  
* var colors = new Array("red", "yello", "gray");

![arrays](./image2/arr.PNG)

### **CHANGING VALUES IN AN ARRAY**

![change](./image2/newa.PNG)

## EXPRESSIONS

**An expression evaluates into (results in) a single value.**

## OPERATORS

**Expressions rely on things called operators; they allow programmers to create a single value from one or more values.**

* ASSIGNMENT OPERATORS : color = 'beige'; 
* ARITHMETIC OPERATORS : area = 3 * 2; 
* STRING OPERATORS : greeting= 'saja+ 'ababneh';
* COMPARISON OPERATORS  : buy = 3 > 5; 
* LOGICAL OPERATORS : buy= (5 > 3) && (2 < 4); 

## JavaScript Arithmetic

![arthematic](./image2/op.PNG)

## MIXING NUMBERS AND STRINGS TOGETHER 

![m1](./image2/m1.PNG)

![m2](./image2/m2.PNG)

![m3](./image2/m3.PNG)

---

## Comparison Operators

**Comparison operators are used in logical statements to determine equality or difference between variables or values.**

![comp](./image3/comp.PNG)
![compa](./image3/comp2.PNG)

## Logical Operators

**Logical operators are used to determine the logic between variables or values.**

![logical](./image3/logical.PNG)

## Conditional Statements

**Use if to specify a block of code to be executed, if a specified condition is true**.

### **syntax**

![ifstatemnet](./image3/if.PNG)

**Use the else statement to specify a block of code to be executed if the condition is false.**

![ifelse](./image3/if2.PNG)

**Use the else if statement to specify a new condition if the first condition is false.**

![elseif](./image3/if3.PNG)














