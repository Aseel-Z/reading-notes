# HTML Text:
- > *Structural Markup* can be used to describe paraghraphs and headings, while *Semantic Markup* provide extra information, such as where emphasis is placed in a sentence.

- In HTML, there are 6 levels of headings (h1, h2, h3, ..h6)
- Important tags:
   - p (paraghraph)
   - i (*italic*)
   - b (**bold**)
   - sup (contain elements to be superscripted)
   - sub (contain elements to be subscripted)
   - br (line break)
   - hr (horizontal break)

- Semantic Markup (Examples):
  - em
  - strong
  - q
  - blockqoute

# CSS - An Introduction

- CSS control the styling of web page elements.
- Think of CSS as the box that surrounds an HTML element.
- CSS allows rules creation which control the way these boxes are presented.
- CSS works by associating rules with HTML elements.
- A CSS Rule consists of two parts; the Selector"determines the HTML element" and the Declaration "determines the style of this element"
- CSS declarations consist of a property and value.
     - *e.g.* h3 {font-family: Arial; color: yellow;}

- CSS could be used internally(within HTML File) or externally (in a separate CSS File).
- Use the **style** element, that lies within the head element, when CSS is used internally.
- Use the **link** element, that lies within the head element, when CSS is used externally.
- The **link** element should use three attributes:
   - **href**: specifies the path to the CSS file (often placed ina folder called css or styles).
   - **type**: specifies the document type being linked to. The value should be text/css.
   - **rel**:specifies the relationshipbetween the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS    file.
- When building a website an external CSS style sheet should be used.
- CSS Selectors are case sensitive.
- There are 8 types of Selectors:
   - Universal *** {}**
   - Type **h1, h2, h3 {}**
   - Class **.note {}** **p.note {}**
   - ID **#introduction {}**
   - Child **li>a {}**
   - Descendant **p a {}**
   - Adjacent Sibling **h1+p {}**
   - General Sibling **h1~p {}**
- If there are two or more rules that apply to the same element,
it is important to understand which will take precedence.
  - **LAST RULE**:  *If the two selectors are identical, the latter of the two will take precedence.*
  - **SPECIFICITY**: *If one selector is more specific than the others, the more specific rule will take precedence over more general ones.*

# JAVASCRIPT - Basic Instructions:

- Script: a written guide for a computer to follow which consists of multiple **statements**.
- Single-line comments can be written using // 
- Multi-line comments can be written using /*  */
- Variable: a container that is used to store data for some time.
- Variables in JS are declared as follows:
   **var** *variable-name*;
- Data Types:
   - Boolean
   - Numbers
   - String

- Arrays are variables that is used to store related pieces of information.

## Expressions
- Two types of expressions:
  - Expressions that assign a value to a variable.
  - Expressions that use two or more values to return a single value

## Operators * / &:
- Allows you to create  a single value from 2 or more values
- Operators types:
  - Arithmatic
  - Comparison “Logical”
  - String

# JAVASCRIPT - Decisions & Loops:

- A JavaScript code makes decisions with the help of conditional statement.
- If statements exceutes of code block by checking (evaluating) a condition.

### We have 8 Comparison Opertators (reaturn single boolean value):
- == : equal to by value
- ===: strictly equal to by value and type
- !== : not equal to by value
- !===: not strictly equal to by value and type
-  '>':greater than
-  '>=':greater than or equal
-  '<':less than
-  '<=':less than or equal

### Logical Opertators (allow the comparison of more than one comparison operators):
- && : AND 
- | | : OR
- ! : NOT