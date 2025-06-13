# Quasar的Config文件配置(必须)
> 配置文件仅显示需追加或更改内容,其他默认值均省略
```javascript
  boot:[
      // 追加配置显示样式的boot文件(用于暗色模式)
      'appearance',
  ]

  framework:{
    // 配置暗色模型的默认值; 自动: "auto", 浅色: false, 深色:true; 
    config: { dark: "auto" },

    // 配置默认语言为中文简体(i18n)
    lang: "zh-CN",

    // 配置插件Notify
    plugins: ["Notify"],
  }

```
