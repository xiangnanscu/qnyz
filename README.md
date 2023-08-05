# 项目初始化

```sh
npm ci && npm run dev
```

# 打包

```sh
npm run build
```

# 开发

## 增加页面

页面文件在`src/views`, 比如添加文件`src/views/Hello.vue`, 则需要重新运行一次`npm run dev`. 然后在页面文件里面就可以这样跳转到该页面:

```vue
<navigator
  url="/views/Hello"
  open-type="navigate"
  hover-class="navigator-hover"
>
  <button>点击跳转到Hello</button>
</navigator>
```

或者使用 JS

```js
utils.gotoPage("Hello"); // 简写形式,以文件名指代该页面
utils.gotoPage({ url: "/views/Hello" }); // 完整的写法
```

## 定义全局组件

全局组件在`src/components`, 比如添加文件`src/components/PageLayout.vue`之后, 那么在`src/views`里面的 vue 文件的 template 就能够直接以`<page-layout></page-layout>`引用此组件了

## 定义全局 JS 对象

全局 JS 对象在`src/composables`和`src/globals`, 这里面的 js 文件导出的对象将全局生效.

# uniapp 教程

## 介绍

https://uniapp.dcloud.net.cn/

## 组件

https://uniapp.dcloud.net.cn/component/
