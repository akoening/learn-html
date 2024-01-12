## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
  The _action_ attribute contains the action that should trigger the form to load.
2. What is the purpose of the _method_ attribute in the _form_ tag?
  The _method_ attribute (in this case 'GET') tells HTML what shoud be done with the _action_ attribute.
3. What is the purpose of the _name_ attribute in the _input_ tag?
  The _name_ attribute is a way to specify the name of the variable received through user input.
4. What is the purpose of the _type_ attrbute in the _input_ tag?
  The type _type_ attribute tells HTML what type to interpret the user input.
5. What is the purpose of the _label_ tag?
  The _label_ tag labels the form so that the user knows to where to input their username and password.
6. What is the purpose of the _required_ attribute?
  The _required_ attribute means the form can't be submitte without a user inputing a value for that field. 

