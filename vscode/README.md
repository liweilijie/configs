# vscode

vscode作为自己常用的一个IDE,
尤其是在写rust的时候常用它，因为微软本身大力支持rust的阵营，而且vscode也是微软的一个大力产品，所以一定会针对rust做很多细节上的优化的。

#### 常用的一些设置

Shift+Cmd+P 

> 设置proxy代理：设置里面->应用程序->代理服务器 `http://127.0.0.1:8001` 另外`Proxy Support`要选择为"on" 才行。

#### rust安装插件：

- rust-analyzer
- rust syntax
- crates
- better toml
- rust test lens
- tabnine
- Atom One Dark 主题
- Material Icon Theme 

字体14 
Font Family: 'Fira Code', Menlo, Monaco, 'Courier New', monospace

[下载fira code](https://github.com/tonsky/FiraCode/wiki/Installing)

```bash
export http_proxy="http://127.0.0.1:8001"; export HTTP_PROXY="http://127.0.0.1:8001"; export https_proxy="http://127.0.0.1:8001"; export HTTPS_PROXY="http://127.0.0.1:8001"
brew tap homebrew/cask-fonts
brew install --cask font-fira-code
```

快捷键
```text
shift+cmd+p 命令面板
shift+option+f 格式化
ctrl+] 转到实现
ctrl+cmd+] 转到声明
ctrl+\,s 引用
ctrl+cmd+\,s 所有引用
cmd+/ 单行注释
cmd+b 显示/隐藏左侧目录栏
ctrl+~ 终端
cmd+p 查找文件
shift+cmd+e 文件资源管理器
```
