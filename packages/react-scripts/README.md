# react-scripts

## This is a customized version of react-scripts, including:

1. Support for Less files instead of Sass. You may also optionally include a `lessVars.js` file from the route of your project, which will be read into the less options as `modifedVars`.
  ```
    module.exports = {
      "@primary-color": "red"
    }
  ```
2. A babel plugin for `styled-components` class names prefixed with the component name.
3. `babel-plugin-import` for importing ant design components.


This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.
