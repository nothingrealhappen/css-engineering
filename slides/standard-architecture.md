## 架构、分层

```
|- src/css
   | -- settings.scss 变量、配置
   | -- reset.scss 浏览器初始化样式
   | -- mixin.scss 共用函数
   | -- basic.scss 基本边距、全局控件
   | -- shared/components-*.scss 复用组件
   | -- pages/*.scss 页面逻辑
```

- 底层：settings/reset/basic
- 复用：mixin/shared components/element
- 应用：pages(layout)/*.scss

