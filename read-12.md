# EJS Partials
- partials are used when there is a need to use the same HMTL accross mutiple views.
- Such that you want to maintain design and html accross the web pages.
- keeping the same footer and header is a good example.
- > Think of partials as functions, they make large websites easier to maintain as you don’t have to go and       change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.


## Example 
- > <!-- views/partials/footer.ejs -->
    footer class="footer"
        p © 90210 Lawyer Stuff. p
    footer
- partials: 
  >     <%- include('partials/footer') %>


### Resource 
- https://medium.com/@henslejoseph/ejs-partials-f6f102cb7433

