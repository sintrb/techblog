#VirtualBox 使用主机上的物理硬盘作为虚拟机的硬盘

###前言
有的时候需要将一整个物理硬盘都当作虚拟的硬盘，其实这样做的用途很广的。比如你安装了双系统，Windows在第一分区上，Linux在第4分区，那么你可以在启动Windows之后创建一个虚拟机，并把整块硬盘作为虚拟机的硬盘。虚拟机启动之后进入到你的Linux系统，这样就可以同时运行你同一块硬盘的两个分区上的系统了。或者你也可以进入Linux之后创建虚拟机来启动你的Windows，这样一来你的两个系统就互通。

当然，有点不足之处就是，你在Linux下不能挂载你的Windows系统分区，因为如果你挂载的话那么虚拟机就没法用这个分区了，也就没法启动那个分区的系统了。

###创建VMDK文件
VMDK文件其实是一硬盘描述文件（如果你有兴趣可以用记事本打开），VBox的虚拟机可以直接使用该文件作为。
VBox的帮助文档这么描述VMDK的：
> While this variant is the simplest to set up, you must be aware that this will give a guest operating system direct and full access to an entire physical disk. If your host operating system is also booted from this disk, please take special care to not access the partition from the guest at all. On the positive side, the physical disk can be repartitioned in arbitrary ways without having to recreate the image file that gives access to the raw disk.
VBox的帮助文件里面有提到如何创建一个VMDK文件的：
>

首先需要创建一个创建

##topic0
##topic1
###segment0
###segment1
####section0
####section1
#####paragraph0
#####paragraph1
>quote0<br />quote1

* list0
* list1
* list2

<pre>
<code>#include <stdio.h>
int main(int argc, char **argv)
{
  printf("hello world~\n");
  return 0;
}</code>
</pre>

[This blog's url](https://github.com/sintrb/techblog/blob/master/BlogTemplate.md),and U can *click* it.

Of course, you can use code in a line. Such as <code>printf(frmstr, args...)</code> function.
