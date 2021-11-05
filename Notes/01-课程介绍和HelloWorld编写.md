# 01-课程介绍和HelloWorld编写

## 01.引入Vue


```html
<script src="https://unpkg.com/vue@next"></script>
```

## 02.Hello World
在HTML文件中创建一个元素，可供vue挂载：
```html
<div id="app"></div>
```
然后在script中挂载vue：
```html
<script>
    Vue.createApp({ // 创建一个Vue实例
        template: '<div>Hello World</div>' // 模板
    }).mount("#app") // 挂载位置
</script>
```
可以看到html已经将vue的内容加载出来了：

<image src="./images/01-01.png"/>