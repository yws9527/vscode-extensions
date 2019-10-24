# vscode-extensions
快速同步旧已经机器安装过的扩展

## Windows（Powershell）版本

机器A：

在VSCode Powershell终端中：
```
code --list-extensions > extensions.list
```

机器B：

将extension.list复制到机器B

在VSCode Powershell终端中：

```
cat extensions.list | % { code --install-extension $_}
```
## 操作参考地址：
```
  https://365airsoft.com/zh-CN/questions/1218029/ruhedaochuvs-codekuozhanmingliebiao
```
