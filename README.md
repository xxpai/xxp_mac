# xyp_mac 设置


### 切换到用户目录, git克隆repo, 并且将文件夹重新命名为xyp
```
cd ~
git clone git@xypai.github.com:xypai/xyp_mac.git
mv xyp_mac xyp
````

添加如下内容到~/.bash_profile
```
[ -f ~/xyp/rc/myrc ] && . ~/xyp/rc/myrc
```
