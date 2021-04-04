# EJS

## What is EJS?
> EJS is a simple templating language that lets you generate HTML markup with plain JavaScript.

## Benefits of using EJS
- Use plain JavaScript
- Fast development time
- Simple syntax
- Speedy execution
- Easy debugging
- Active development

## How to use EJS? (Steps)
- **Install** 
   > install EJS with NPM ( npm install ejs)
- **Use**
   > Pass EJS a template string and some data.
   _Example_
   > let ejs = require('ejs');
   >let people = ['geddy', 'neil', 'alex'];
   >let html = ejs.render('<%= people.join(", "); %>', {people: people});
- **CLI**
   >Feed it a template file and a data file, and specify an output file.
     _Example_
   >ejs ./template_file.ejs -f data_file.json -o ./output.html
- **Browser support**
   > Download a browser build from the latest release, and use it in a script tag.
   _Example_
   > script src="ejs.js" script
   > script
   > let people = ['geddy', 'neil', 'alex'];
   > let html = ejs.render('<%= people.join(", "); %>', {people: people}); script tag


### Resource:
https://ejs.co/