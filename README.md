[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/unionthugface/paper-input-money)

# \<paper-input-money\>

`<paper-input-money>` is a Polymer 2 input for displaying currency with locale features.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
	<link rel="import" href="../paper-input/paper-input.html">
    <link rel="import" href="paper-input-money.html">
    <style>
      paper-input-money {
        max-width: 400px;
        margin: auto;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<div>
<paper-input-money label="Input label"
				   always-float-label
				   required
				   value="2454"></paper-input-money>
</div>
```
