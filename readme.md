# Bootstrap with React

1. Setup the environment
2. Responsive theme
3. React JSX
4. DOM Interaction
5. Bootstrap.js elements
6. Redux
7. Routing
8. React JS API
9. React with Node.js
10. Best practices


## Setup the environment
We basically need to load in bootstrap (CSS and JS) and then add 3 more JS files - react, reactdom and babel-core.

```HTML
        <link rel="stylesheet" href="css/bootstrap.min.css">	
		<script type="text/javascript" src="js/react.min.js"></script>
		<script type="text/javascript" src="js/react-dom.min.js"></script>
		<script src="https://cdnjs.cloudflare.com/ajax/libs/babel-core/5.8.23/browser.min.js"></script>
```
The React-Bootstrap JavaScript framework is similar to Bootstrap rebuilt for React. It's a complete reimplementation of the Bootstrap frontend reusable components in React. React- Bootstrap has no dependency on any other framework, such as Bootstrap JS or jQuery. It means that, if you are using React-Bootstrap, then you don't need to include jQuery in your project as a dependency. Using React-Bootstrap, we can be sure that there won't be external JavaScript calls to render the component which might be incompatible with the ReactDOM.render. However, you can still achieve the same functionality, look, and feel as Twitter Bootstrap, but with much cleaner code.