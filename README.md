# 收集的各种PKGBUILD

## [网易云音乐](https://github.com/9527tech/PKGBUILDs/tree/master/netease-cloud-music) [来源](https://gitee.com/laomocode/netease-cloud-music/)
## [qcef](https://github.com/9527tech/PKGBUILDs/tree/master/qcef) [来源](https://github.com/springzfx/archlinux/tree/master/qcef)
### 解决网易云音乐无法中文输入的问题: 先装qcef再装netease-cloud-music

```shell
# 克隆项目
git clone https://github.com/9527tech/PKGBUILDs

# 进入项目中的qcef文件夹
cd qcef 
makepkg -sci

# 进入项目中的netease-cloud-music文件夹
cd netease-cloud-music
makepkg -sci
```
