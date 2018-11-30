# Vue Password Validator
Lightweight 🔓 password validator Component in vue.js
<p align="center">
  <img src="https://i.imgur.com/RU8fTvT.gif" alt="" title="Demo" />
</p>

## Demo
You can find a demo [Here](https://hamzaouiii.github.io/vue-password-validator/).

## Installation
Using npm
```bash
npm i vue-password-validator --save
```
or Using yarn 
```bash
yarn add vue-password-validator 
```
## Usage
This component cannot be used through the `<script>`tag! You will need to import it this way:
```js
<template>
  <div class="app">
      <password-validator></password-validator>
  </div>      
</template>

import Vue from 'vue';
import PasswordValidator from 'vue-password-validator';
export default {
	components: {
		PasswordValidator
	}
}

```
## Styling

The component is styled with a width of 100%. You can simply change that by putting it in a container and give that container a specific width:
```css
.container {
  width : 500px;
}
```

