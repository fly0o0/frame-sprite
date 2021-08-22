# frame-sprite

这是一款帧动画合成工具。

通过该插件，可以将目录下的图片快速合成一张雪碧图，且输出你可能会需要的css文件。当前支持四种合成模式，后期会拓展更多需要的功能。

## 使用

```js
    // 本地安装使用
    npm install frame-sprite -D
    npx frame-sprite -i test/imgs -o test/dist -m 0
```

**参数说明**

+ -i 源文件输入目录（相对于命令执行的目录），默认值：img
+ -o 雪碧图输出目录（相对于命令执行的目录），默认值：和-i一致
+ -m 目前支持四种模式（0 1 2 3），对应生成的css文件，默认值：0
## 范例

![image.png](https://yun.dui88.com/tuia/frame/20210822125413.jpg)


