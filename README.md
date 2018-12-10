[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/htmlelements/smart-tooltip)

# &lt;smart-tooltip&gt;

[Live Demo ↗](https://htmlelements.com/demos/tooltip/)
|
[Documentation ↗](https://www.htmlelements.com/docs/)
|
[Installation ↗](https://www.npmjs.com/package/@smarthtmlelements/smarthtmlelements-core)

[&lt;smart-tooltip&gt;](https://htmlelements.com/demos/tooltip/) is a Custom HTML Element providing slide show/banner rotator](https://htmlelements.com/).

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <script src="../smart-core/source/smart.core.js"></script>
    <link rel="stylesheet" href="../smart-core/source/styles/smart.default.css" type="text/css" />
 <script>
   window.onload = function () {
  
   }
   </script>
     <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
    <smart-button style="margin: 50px;" id="button">Button</smart-button>
    <smart-tooltip id="tooltip" selector="button" arrow>Tooltip</smart-tooltip>
```

[<img src="https://raw.githubusercontent.com/htmlelements/smart-tooltip/master/tooltip-web-component.png" alt="Screenshot of smart-tooltip">](https://htmlelements.com/demos/tooltip)

## Getting Started

Smart HTML Elements components documentation includes getting started, customization and api documentation topics.

[Getting Started Documentation](https://www.htmlelements.com/docs/)


## The file structure for Smart HTML Elements

- `source/`

  Javascript files.

- `source/styles/`

  Component CSS Files.

- `demos/`

  Demo files

## Running demos in browser

1. Fork the `Smart-HTML-Elements-Core` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `Smart-HTML-Elements-Core` directory, run `npm install` and then `bower install` to install dependencies.

1. Run a localhost or upload the demo on a web server. Then run:

  - /demos/smart-tooltip/smart-tooltip-overview.htm


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. 

## Creating a pull request

  - Make sure your code is compliant with ESLint
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of our team members


## License

Apache License 2.0
