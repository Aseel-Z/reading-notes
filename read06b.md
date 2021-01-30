# CSS

## An Introduction

- CSS allows you to control the styling of web page elements.
- CSS is the box that surrounds an HTML element.
- CSS allows rules creation which control the way these boxes are presented.
- CSS works by associating rules with HTML elements.
- A Rule consists of two parts; the Selector"determines the HTML element" and the Declaration "determines the style of this element"
- CSS declarations consist of a property and value.
     - *e.g.* h3 {font-family: Arial; color: yellow;}

- CSS could be used internally(within HTML File) or externally (in a separate CSS File).
- Use the **<style>** element, that lies within the <head> element, when CSS is used internally.
- Use the **<link>** element, that lies within the <head> element, when CSS is used externally.
- The **<link>** element should use three attributes:
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

## COLOR

- Use the **color** property to specify the *Foreground Color*.
- Use the **background-color** property to specify the *Background Color*.
- To specify any color"value" in CSS, there are three ways:
   - RGB Values
   - HEX Codes
   - Color Names
- Every pixel color is a mix of Red, Green, and Blue.
- When choosing the Foreground & Background colors, make sure there is enough contrast for the text to be legible.
- RGBA in CSS3 indicates opacity.  .
- HSLA in CSS3  allows you to specify colors as HSL values, with an optional opacity value.
