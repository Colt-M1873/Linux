## Software

PuTTY

Xshell

Xftp



## Concepts

CVM Cloud Virtual Machine

CUDA Compute Unified Device Architecture

## Operations

Xshell shift+alt+enter=全屏

按两下tab出现所有可用命令

按tab补全

rz或者sz卡死后，按住ctrl+5次x键可退出

ctrl+s暂停终端  ctrl+q恢复

 Ctrl + c 中止当前正在执行的程序。

 Ctrl + d 相当于exit命令，退出当前会话。

 Ctrl + z 将当前运行的程序放到后台运行。与运行时加 & 类似。



在命令行环境中无GUI，加入以下代码可避免出错，并且在可生成图片后用plt.savefig发送到有GUI的系统上打卡

```python
import matplotlib as mpl
mpl.use('Agg')
......
plt.show()
plt.savefig('/home/pycode/img1.png')
```





### vim

':w'保存    ':q'退出

':u'撤销      Ctrl+r还原，反撤销

ctrl+v进入多选模式，j和k选择要操作的行数，shift+>>批量缩进  <<批量取消缩进

光标移动到要复制的地方，ctrl+v进入多选模式，方向键移动，y复制，p粘贴，d删除





## Commands and meanings

rm remove

cd	change directory 

pwd	print work directory

ls	list files

ln	link files

touch

mv move

cat	concatenate

mkdir	make directory

tar	tape archive











now i know
im in vim editor
press ESC to insert command 
command 'i' means insert
command ':wq' means save and quit
command ':w' means write into the storage
command ':q'means quit and ':q!'menas quit without saving any changes 
now i'll try ':saveas'
~