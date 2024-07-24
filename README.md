<<<<<<< HEAD
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

=======
>>>>>>
# Code Editor App
This is a React-based code editor application that allows you to write, edit, and preview HTML, CSS, and JavaScript code in real-time. It utilizes CodeMirror for the editor component and stores the code using localStorage to retain your changes even after refreshing the page.

# Features
#Simultaneous Editing: Write HTML, CSS, and JavaScript code side by side.

Real-Time Preview: View the output of your code in an iframe that updates every 250 milliseconds.

Syntax Highlighting: Enhanced code readability with syntax highlighting for HTML, CSS, and JavaScript.

Line Wrapping: Prevents horizontal scrolling by wrapping long lines of code.

Linting: Provides real-time feedback on syntax errors and potential issues.

Collapsible Editors: Toggle the visibility of each editor pane for better focus.

Persistent Storage: Automatically saves your code to localStorage and loads it when you return.

# Editing and Previewing Code
Write your HTML code in the HTML editor.

Style your HTML using the CSS editor.

Add interactivity using the JS editor.

The preview pane will update in real-time to reflect your changes.

# Collapsible Editors
Each editor has a toggle button to expand or collapse the pane.

Use these buttons to focus on a specific part of your code when needed.
# Persistent Storage
Your code is automatically saved to localStorage with the keys codepen-clone-html, codepen-clone-css, and codepen-clone-js.

When you revisit the application, your code will be loaded from localStorage.
# Code Overview
# App Component
The App component manages the state for the HTML, CSS, and JavaScript code, and updates the preview pane using an iframe.

# Editor Component
The Editor component uses CodeMirror to provide an advanced code editing experience.

# useLocalStorage Hook
The useLocalStorage hook simplifies state management by storing and retrieving state from localStorage.

# Styles
Basic styling for the application, including the layout of the editor panes and the preview pane.

# Options Explained
# CodeMirror Options
lineWrapping: Enables word wrapping to prevent horizontal scrolling.

lint: Enables linting to provide real-time feedback on syntax errors and potential issues.

mode: Sets the syntax highlighting mode for the respective language (HTML, CSS, JavaScript).

theme: Sets the theme of the editor (using 'material' theme for a consistent look).

lineNumbers: Displays line numbers for easier navigation and reference.

