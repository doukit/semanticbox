# semanticbox
semantic-ui box like bootbox in semantic-ui

## 说明
[bootbox](http://bootboxjs.com/)只针对bootstrap,这个项目的目的是实现bootbox的效果，而不采用bootstrap的框架。
这里采用的是semantic-ui的框架。
## 弹窗类型
1. 消息弹窗
```
semanticbox.info(msg, callback);
```

举例

```
semanticbox.info("消息弹框!", function() {
    console.log("我是回调")
});
```

## 依赖
[semantic-ui](http://semantic-ui.com/) 2.1+
