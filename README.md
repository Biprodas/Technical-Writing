# JavaScript

- What is JavaScript?
- What can JavaScript Do?
- Where does JavaScript Code run?

## What is JavaScript?
> JavaScript is one of the most powerful kanguage in the world. It growing faster than any other language.

What can JavaScript Do?
> With JavaScript you can work as a Front-end developer or a Back-end developer or Ful-stack developer

JavaScript Today
1. Web/ Mobile apps
2. Real time networking app
3. Command-line tools
4. Games

## Where does JavaScript Code run?
Firefox - SpiderMonkey
Chrome - V8

## Run JavaScript in Browser
```bash
> console.log("Hello World");
> 5 + 7 
> allart("Welcome to JavaScript World");
```

## Understanding Browser, HTML,  DOM etc.

## JavaScript in Browsers
- We write javascript code in <script> tag
- we can use this <script> tag in two place, one is in <head> secion, otherone is in <body>
- the best practie is use javascript code at the ed of the body

### Best Practice:
1. The browser parses this file from top to bottom so if we put script element in head section, we might have a lopt of java script code there
so our browser may get busy parsing and executing that and it wont be able to render the content of the page so this will create a bad user experience, when our user look at our web page it's white or blank while our brower is busy parsing and executing our code.
2. our code that we have in between script elements needs to talk to the elements on this web page for elemple we ma want to show or hide some elements so by adding the code here at the end of the body section we will be confident that all these eements are rendered by the browser.
now there are exceptions to this rule  some time we're using third-party code that has to be placed in the code section but these are exceptions.
so, our best practice is to add the javascript code to the end of the body section.

```bash
<body>

    <script>
        console.log('Hello World);
    </script>
</body>
```

> statement - terminated by semicolol
> string - sewuwnce of characters placed in single or double quotation

```bash
<script>
    console.log('Hello World);
    // comment - ignored by javascript engine its not executed
</script>
```

## Separation of concern
Separate javaScript code from .html file, and put it in .js file

Create `app.js` file, and write the following code
```bash
console.log('Hello World');
```
Reference that file in `index.html` 
```bash
<script src="./app.js"></script>
```

## Execute code in node
Download and Install [Node.js]()
```bash
# Check node version
$ node -v
# Run javascript code in node
$ node app.js
```

## Variables
- We use a variable to store data temporarily
```bash
var # there are soem issue wiht var, old days are gone
let # bet practice is use let to declare a variable
const  #
```

```bash
let name = 'Biprodas';
console.log(name);
# Rules for naming variable:
# Can not be a reaserved keyword
# Should be Meaningful
# Can not start with a number
# Cannot contain a space or hyphen 
# Are case-sensitive

let firstName = 'Biprodas';
let lastName = 'Roy';
let fullName = firstName + ' ' + lastName;
console.log(fullname);
```