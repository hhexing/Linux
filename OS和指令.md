# OS（Operator System）

> **操作系统是一款搞管理的软件**
>
> 软件?    最大的软件
>
> 管理什么？  软硬件
>
> 为什么要管理？   操作系统对下把软硬件管理好是为了对上向用户提供一个良好的资源环境
>
> 如何管理？ 管理者根据被管理的信息进行决策
>
> 怎样管理？ 先描述再组织

![1547557282727](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1547557282727.png)

# Linux下的指令

##### 1.ls

> 对于目录：打印出目录下的所有子文件与文件
>
> 对于文件：打印出文件信息
>
> 可以不加参数，打印出当前目录下的所有子文件与文件

![1547557807417](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1547557807417.png)

##### 2.pwd

> 打印出当前用户的目录

![1547558107817](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1547558107817.png)

##### 3.cd

> 改变工作目录

- 相对路径：从根目录开始的目录
- 绝对路径：从当前目录开始的目录

```
cd .   当前目录
cd ..  上级目录
cd ~   主工作目录
cd -   最近访问目录
```

##### 4.touch

> 可以更改文件或者目录的目录的日期时间
>
> 创建一个新文件

**一个文件有3个时间**

- Access time   访问时间
- Modify time  修改时间
- Change time 状态改变时间

##### 5. mkdir

> 创建一个目录

![1547558923968](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1547558923968.png)

可以递归创建目录

##### 6.rmdir 、dir

> 删除文件或者目录

```
-f 强制删除
-r 删除目录下的所有文件
```

##### 7.man

> 查看使用方法

##### 8.cp

> 复制文件
>
> 复制目录 -r

![1547559377770](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1547559377770.png)

##### 9.mv

> 移动文件或者将文件改名

##### 10.cat、tac

> 查看文件内容

```
-b  对非空行输出行号
-n	对输出的所有行编号
-s	不输出多余空行
```





