####  😤 作用域控制 😤
```
// page-a.css
.menu-button {
  color: #fff;
  background-color: #f0f;
}

// page-b.css
.menu-button {
  background-color: #fff;
}
```

<div class="menu-button">button</div>
<div class="menu-button menu-button--issue">button</div>

<style>
.menu-button {
  color: #fff;
  background-color: #f0f;
}

.menu-button--issue {
  background-color: #fff;
}
</style>
