# openwrt-luci-app大神的openwrtde luci-app插件，仅仅适合Luci18。
收集了诸位大神的常用OpenWrt软件包源码合集，建议使用Lean源码（luci18）,Lienol源码（luci17heluci18）。

`Lean源码用luci18分支，Lienol源码默认用的luci 17用luci18`


## 使用方式（三选一，这里以18.06为例）：
`还是建议按需取用，不然碰到依赖问题不太好解决`
1. 先cd进package目录，然后执行
```bash
 git clone -b luci18 https://github.com/gproject-lede/openwrt-app.git
```
2. 或者添加下面代码到feeds.conf.default文件，
```bash
 src-git lede https://github.com/project-lede/openwrt-app;luci18
 或者
 src-git lede https://github.com/project-lede/openwrt-app;luci18
```
插件克隆在package目录下的god目录。

3、克隆package里的单个文件(建议此法)
```bash
svn export --force https://github.com/project-lede/openwrt-app/branches/luci18/luci-app-godproxy package/diy/luci-app-godproxy
或者
svn export --force https://github.com/project-lede/openwrt-app/trunk/luci-app-godproxy package/diy/luci-app-godproxy
```
## 感谢诸位大神的开源和贡献。
```bash
 Lean大神，Lienol大神、sirpdboy大神、kenzok8大神、frainzy1477大神、CTCGFW团队、garypang13大神、vernesong大神、rufengsuixing大神、jerrykuku大神、tty228大神、fw876大神、xiaorouji大神、xiaoqingfengATGH大神、lisaac大神、destan19大神、KFERMercer大神等等诸位大神。
```
