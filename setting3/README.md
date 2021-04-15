

###   设置代码文字颜色

打开设置面板

在输入框输入json,找到并进入settings.json这个文件中


editor 设置配置模块下

```

    "editor.fontSize": 14,
    "editor.tokenColorCustomizations": {
        "comments": "#6D6D6D", // 注释
        "keywords": "#DCA34B", // 关键字
        "variables": "#e9e9e0f1", // 变量名
        "strings": "#547143", // 字符串
        "functions": "#e9b76c", // 函数名
        "numbers": "#5583AF" // 数字
      },
```

此处的配置 偏向于 WebStorm 的风格


同时文字大小  通过editor.fontSize 来配置