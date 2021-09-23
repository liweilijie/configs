# vscode

**vscode**作为自己常用的一个**IDE**,
尤其是在写`rust`的时候常用它，因为微软本身大力支持`rust`的阵营，而且**vscode**也是微软的一个大力产品，所以一定会针对`rust`做很多细节上的优化的。

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
- GitLens
- Bracket Pair Colorizer 2 # 匹配括号的
- Rainbow Brackets # 同上的功能
- code time
- Project Manager 
  > 工作中，我们经常会来回切换多个项目，每次都要找到对应项目的目录再打开，比较麻烦。
  > Project Manager插件可以解决这样的烦恼，它提供了专门的视图来展示你的项目，我们可以把常用的项目保存在这里，需要时一键切换，十分方便。
- highlight-icemode https://blog.csdn.net/palmer_kai/article/details/79548164
  > 选中相同的代码时，让高亮显示更加明显【荐】VSCode自带的高亮显示，实在是不够显眼。用插件支持一下吧。所用了这个插件之后，
  > VS Code自带的高亮就可以关掉了：在用户设置里添加"editor.selectionHighlight": false即可。



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
ctrl+cmd+] 转到定义
ctrl+opt+] 转到声明
ctrl+\,s 引用
ctrl+cmd+\,s 所有引用
cmd+/ 单行注释
cmd+b 显示/隐藏左侧目录栏
ctrl+~ 终端
cmd+p 查找文件
shift+cmd+e 文件资源管理器
cmd+\ 创建多个编辑器 # 抄代码得器，非常重要
ctl+1、2 聚焦到第1或者第2个编辑器，同上重要
cmd+j 显示/隐藏控制台
cmd+shift+n 重新开一个软件的窗口 很常用
cmd+n 新建文件
cmd+w 关闭当前文件
cmd+` 在同一个软件的多个工作区之间切换，很频繁
# 搜索相关的
cmd+shift+f 全局搜索代码，很常用
cmd+p 在当前的项目工程里，全局搜索文件名
cmd+f 在当前文件中搜索代码，渔村在搜索框里
```

#### 左右显示多个编辑器窗口

https://juejin.cn/post/6844903826063884296

```text
cmd+\ 打开多个编辑器窗口
cmd+1 切换到左边的窗口
cmd+2 切换到右边的窗口
```

#### 高阶设置

```text
# 启用连字符，比较好看。
"editor.fontLigatures": true
# 终端支持选中即复制的功能
"terminal.integrated.copyOnSelection": true
# 自动保存
文本编辑器->文件-》Auto Save-> onFocusChange
# 保存即格式化
# editor.formatOnSave

```

#### 搜索

- Aa: 大小写敏感
- Ab: 全字匹配
- .*: 正则匹配
