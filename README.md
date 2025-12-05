# QQ音乐会员下载歌曲破解  
依据原作者说法，本项目只能在QQ音乐VIP在期时使用。  

## 环境要求
```requirements
python==3.10.6
frida==16.5.2
```
其它版本有可能运行不起来  
推荐使用conda管理python环境  

## 使用（conda）
```bash
# 创建并激活python环境
conda create -n qqmusic_vip python=3.10.6 -y
conda activate qqmusic_vip
# 安装frida
pip install frida==16.5.2
```
然后运行`python qqmusic_vip.py`即可。文件会输出在当前目录下的output下。

注意：如果你修改了QQ音乐的下载路径，需要修改`qqmusic_vip.py`中的`home`变量。