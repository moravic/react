

Building Applications with React and Flux
(https://app.pluralsight.com/library/courses/react-flux-building-applications/table-of-contents)

REACT:

  JSX - involves writing markup in JavaScript
  Virtual DOM - enhances performance minimizing expensive updates of the DOM
  Isomorphic Rendering - allows you to render components in client and server
  Unidirectional Flows - handling all the data flows in a single direction using a centralized dispatcher


  1) HTML should be a projection of app state, not a source of truth.
  Your app is a function of props and state, you don't save anything in the DOM.
  The DOM reflects the current state of the data automatically

  2) JavaScript and HTML belong in the same file

  3) Unidirectional flow. No two-way binding.

  4) Inline styles can be good

NODE.js Server-side JavaScript
Uses the V8 Engine
Includes the npm package manager
CommonJS pattern for referencing and export modules

  a) Get the reference to dependency
     var dependency = require('path/to/file');
  b) Declare Module
     var MyModule = {
      //code here...
     }
  c) Export to others
     module.exports = MyModule;

Browserify Node packages in the browser
  npm install --save browserify reactify vinyl-source-stream

React Components library

React/Router for client side routing

Facebook Flux to handle unidirectional app data flows (more a pattern that a library)

Gulp Task Runner
  npm install --save gulp gulp-connect gulp-open

Bootstrap

npm install --save bootstrap jquery gulp-concat

ESLint Lint JS Files, including JSX

npm install --save gulp-eslint

Git

# Creating a git ignore file
echo "" > .gitignore
git add .gitignore
git commit -m "message" .gitignore

# removing files already in the repository
git rm -rf --cached .
git add .
