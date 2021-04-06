# Sending Form Data

## what happens when a user submits a form?
- the form provides the required data tp be sent via the HTTPs request.
- It is important to define the attribute (action & method).

### The action attribute
- > The action attribute defines where the data gets sent. Its value must be a valid relative or absolute URL.

### The method attribute
- > HTML form data can be transmitted via a number of different methods, the most common being the GET method and the POST method
- the GET method reads data 
  - >"Hey server, take a look at this data and send me back an appropriate result."
- the POST method creates data
  - >"Hey server, I want to get this resource."

- The user cannot view HTTPs request unless some tools were used.

### data retrieving - the server
- > Whichever HTTP method you choose, the server receives a string that will be parsed in order to get the data as a list of key/value pairs
- Respones can be handled either by PHP or Python or by other languages and frameworks.

#### Sending files is special case for HTML forms (binary data)
> If you want to send files, you need to take three extra steps:
  - Set the method attribute to POST because file content can't be put inside URL parameters.
  - Set the value of enctype to multipart/form-data because the data will be split into multiple parts, one for each file plus one for the text data included in the form body (if text is also entered into the form).
  - Include one or more input type="file" controls to allow your users to select the file(s) that will be uploaded. 

