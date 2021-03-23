# Javascript Templating
- >  technique to render client-side view templates with Javascript by using a JSON data source.

## Mustache (logic-less)
- It is the base of templating in JavaScript.
- it is called logic less because it only includes tags, not ifs, or fors.
- in order to use Mustache-Express you'll need to follow a predetermined syntax (steps)

## How create an output using templates?
- you'll need the tempalte + the input data, then the processer which is the Templating Engine, then you'll get the required output.

# Flexbox
- flexibe and dynamically changing layout.
- it best fits application, and small-scale layouts (gid layout are for large scale projects)
- >gives the container the ability to alter its items’ width/height (and order) to best fill the available space.

## Flex Properties for parents
- dispaly (shall take the value "_flex_")
- flex-direction
- flex-wrap
- flex-flow
- justify-content
- align-items
- align-contents

## Flex Properties for children
- order
- flex-grow
- flex-shrink
- flex-basis
- alig-self

### Example
> .parent {
  display: flex;
  height: 300px; /* Or whatever */
}

.child {
  width: 100px;  /* Or whatever */
  height: 100px; /* Or whatever */
  margin: auto;  /* Magic! */
}