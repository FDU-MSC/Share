
如何配置一个好环境 - pseudo best practice

# Win10

Zeal: 文档离线，类似MacOS上的Dash，灰常好用  
终端实践: cmder + babun，人生从未如此美好  
vagrant: 如果实在想要linux的环境，可以用vagrant装虚拟机，然后用上述终端ssh连接，异常满足！  

# 数据科学

anaconda: [tuna](https://mirror.tuna.tsinghua.edu.cn/help/anaconda/)

```bash
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
conda config --set show_channel_urls yes
```

pip: [tuna](https://mirror.tuna.tsinghua.edu.cn/help/pypi/)

```bash
mkdir ~/.pip
mkdir ~/.config/pip
touch ~/.pip/pip.conf
echo "[global]\nindex-url = https://pypi.tuna.tsinghua.edu.cn/simple\n" >> ~/.pip/pip.conf
cp ~/.pip/pip.conf ~/.config/pip/pip.conf
```

换源之后会发现人生如此美好

pytorch: `conda install pytorch torchvision -c pytorch`
