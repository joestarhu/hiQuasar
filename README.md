# Quasar的Config文件配置
## 暗色模型的配置
```javascript
    ...
    boot: [
      'i18n',
      'axios',
      // 追加配置显示样式的boot文件
      'appearance',
    ],


    framework: {
        // 配置暗色模型的默认值为auto
        config: { dark: "auto" },

      ...
    }
```

## i18n的配置
```javascript
    ...

    framework: {
        // 配置默认语言为中文简体
        lang: "zh-CN",

      ...
    }
```


## Nofify插件配置
```javascript
    framework: {
      ...

      // 配置插件Notify
      plugins: ["Notify"]
    },
```