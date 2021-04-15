

#### 方法


    1.安装background插件
    2.打开设置，在搜索框中输入background，选择扩展中的plugin background，选择在setting.json中编辑
    3.

```

  //background 的相关配置
    "update.enableWindowsBackgroundUpdates": true,
    "background.customImages": [
        "xx/vs_background.png"//图片地址
    ],
    "background.style": {
        "content":"''",
        "pointer-events":"none",
        "position":"absolute",//图片位置
        "width":"100%",
        "height":"100%",
        "z-index":"99999",
        "background.repeat":"no-repeat",
        "background-size":"25%,25%",//图片大小
        "opacity":0.2 //透明度
    },
    "background.useFront": true,
    "background.useDefault": false,//是否使用默认图片

```


    4.mac 老版本如何copy图片的路径
        打开一个文本，直接拖拽图片到文本中，就可以得到图片的路径了