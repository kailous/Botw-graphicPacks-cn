# Botw GraphicPacks CN 

----
# 塞尔达传说：旷野之息 图形插件 中文版

----

编码 `UTF-8` | 汉化 `RainForest` 

----

这个项目的目的主要是帮助不懂设置图形插件的小伙伴，汉化之后可以自主根据需要去调试。而不是根据别人的建议去设置。

但是这个项目有一个最大的问题目前无解，就是使用中文的图形插件后，`log` 中记录的也是中文，在官方论坛进行 Bug 反馈的时候，开发人员无法重现 Bug 。进而也就无法解决你遇到的问题。
遇到需要向官方反馈的时候，请下载原版的图形插件。

----
### Tips
- 建议使用 `Githob` 管理此插件，方便随时保持文件是最新的。更新的时候仅下载更改了的文件，而不是每次下载全部。之后补充下载和更新的脚本。
- 因为时间精力有限，官方的更新可能跟进的不会很及时，如果有你需要的插件不在此项目中，或者版本较低，请在 `Github` 或者 `Notion` 中进行反馈。
- 新的 `MacOS` 好像是自带 `git` 工具，`终端.app` 输入 ``` git -v ``` 可以查看版本。如果没有你可以[到这里](https://git-scm.com/download/mac)安装 

### git下载
```
GITHUB=git@github.com:kailous/Botw-graphicPacks-cn.git
CEMU="${HOME}/Library/Application Support/Cemu/graphicPacks/Botw-graphicPacks-cn"
git clone ${GITHUB} ${CEMU}
```
### git更新
```
cd "${HOME}/Library/Application Support/Cemu/graphicPacks/Botw-graphicPacks-cn"
git fetch --all
git pull
```
