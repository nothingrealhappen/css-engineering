<img alt="" src="resources/logos/web-components.svg" style="background-color: #fff; width: 150px;" >

### Web Components 
<small>
<a href="https://drafts.csswg.org/css-scoping/">CSS scoping specification</a>
</small>
```
<dom-module id="x-foo">
  <template class="sign-up-template">
      <style>
        button {
          background-color: #f0f;
        }
      </style>
      <input type="text" id="username" placeholder="username">
      <input type="password" id="password" placeholder="password">
      <button id="btn">Sign Up!</button>
  </template>
</dom-module>
```
