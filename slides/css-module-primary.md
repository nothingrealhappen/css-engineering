<img alt="" src="resources/logos/css-modules.png" style="background-color: #fff; width: 150px;">


```
html: <h1 class="title">An example heading</h1>

style.css: .title { background-color: red; }

js: 
import styles from "./styles.css";
element.innerHTML = 
  `<h1 class="${styles.title}">
     An example heading
   </h1>`;
   
output: 
<h1 class="_styles__title_309571057">An example heading</h1>
```
