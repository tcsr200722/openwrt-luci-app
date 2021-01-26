# openwrt-luci-app大神的openwrtde luci-app插件
收集了诸位大神的常用OpenWrt软件包源码合集，建议使用Lean源码,Lienol源码。

18.06版luci请使用luci18分支

19.07版luci请使用luci19分支

`Lean源码用19分支，Lienol源码默认用的luci 17用18`


## 使用方式（三选一，这里以18.06为例）：
`还是建议按需取用，不然碰到依赖问题不太好解决`
1. 先cd进package目录，然后执行
```bash
 git clone -b luci18 https://github.com/godros/openwrt-luciapps.git
```
2. 或者添加下面代码到feeds.conf.default文件，
```bash
 src-git god https://github.com/godros/god-openwrt-packages;luci18
 或者
 src-git god https://github.com/godros/god-openwrt-packages;luci19
```
插件克隆在package目录下的god目录。

3、克隆package里的单个文件，添加代码()
```bash
svn co https://github.com/godros/openwrt-luciapps/branches/luci18/luci-app-godproxy ./package/luci-app-godproxy
```
## 感谢诸位大神的开源和贡献。
```bash
 Lean大神，Lienol大神、sirpdboy大神、kenzok8大神、frainzy1477大神、CTCGFW团队、garypang13大神、vernesong大神、rufengsuixing大神、jerrykuku大神、tty228大神、fw876大神、xiaorouji大神、xiaoqingfengATGH大神、lisaac大神、destan19大神、KFERMercer大神等等诸位大神。
```
