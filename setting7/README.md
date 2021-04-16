

###  配置启动器

```
npm run dev (serve)
```

初始化（启用）-左侧菜单第四个图标

点击创建 launch.json 文件

点击搜索 Node.js 点击选择

会自动生成.vscode/launch.json文件。


```

{
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [{
        "type": "node",
        "request": "launch",
        "name": "Launch Program",
        "skipFiles": ["<node_internals>/**"],
        "program": "${workspaceFolder}\\app.js"
    }]
}
```



编辑启动配置文件
launch.json

```

{
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [{
        "name": "Launch via NPM",
        "request": "launch",
        "runtimeArgs": [
            "run",
            "serve"
        ],
        "runtimeExecutable": "npm",
        "skipFiles": [
            "<node_internals>/**"
        ],
        "type": "node"
    }]
}
```

添加configurations 下的 runtimeArgs/runtimeExecutable

其中 runtimeArgs serve 可修改为 dev命令 


mac 下 fn+F5  -> 启动调试

快捷键
F5：启动调试

Ctrl + F5：直接运行

Shift + F5：终止调试

Ctrl + Shift + F5：重启调试