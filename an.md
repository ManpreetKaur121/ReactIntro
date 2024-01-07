1.What is React?
Ans :- React is an open-source JavaScript library for building user interfaces, particularly single-page applications where UI updates are frequent. It allows developers to create reusable UI components and manage the state of an application efficiently.

2.Who made React?
Ans: React was developed by Facebook. The initial release was by Jordan Walke, a software engineer at Facebook, in 2013.

3.What is Babel?
Ans: Babel is a JavaScript compiler that allows developers to write code using the latest ECMAScript standards (or even future standards) and then transform or compile it into older versions of JavaScript that can run in current browsers.

4.How does Babel convert HTML code in React into valid code?
Ans:- Babel primarily deals with JavaScript, not HTML. In the context of React, Babel is often used to transpile JSX (JavaScript XML) syntax, which is a syntax extension for JavaScript recommended by React. JSX allows developers to write HTML-like code within their JavaScript files. Babel transforms JSX code into regular JavaScript that browsers can understand.

5.What is ReactDOM used for? 
Ans:ReactDOM is a package that provides DOM-specific methods for working with React. It is used to render React components into the DOM. 

6.How do you add React to a web application?
Ans:- To add React to a web application, you need to follow these steps:
 Install React and ReactDOM using npm.
 Create React components and write your application logic.
 Use ReactDOM to render your React components into the DOM.
 Include the compiled JavaScript file in your HTML file using a script tag.

7. What is React.createElement?
Ans:- React.createElement is a function used to create React elements. It takes three arguments: the type of element (a string  representing an HTML tag or a React component), an object containing the element's properties (or null if none), and the  element's children.

8.What are the three properties that createElement accepts?
Ans:-React.createElement accepts three arguments:

   Type: The type of element (string for HTML tags or a React component).
   Props: An object containing the properties of the element (attributes and settings).
   Children: The content or children elements of the created element.
  
9. What is the meaning of render and root?
Ans:- Render: 
 In the context of React, "render" refers to the process of transforming React components into a format that can be displayed on the screen. The ReactDOM.render() method is used for this purpose, taking a React element and rendering it into a specified container in the DOM.

 Root:
  The "root" usually refers to the root DOM node where your React application is attached. In the ReactDOM.render() example, document.getElementById('root') specifies the container (or root) where the React component will be rendered within the HTML document.


10.What are the packages that you need to import for React to work with?
The two core packages you need are:
react: The React library itself.
react-dom: Provides methods for DOM manipulation with React.



