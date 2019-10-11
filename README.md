# Linux_interviewing_skills
Linux面试基本100道题
<br>
1. cron 后台常驻程序 (daemon) 用于： <br>
A. 负责文件在网络中的共享 <br>
B. 管理打印子系统<br>
C. 跟踪管理系统信息和错误 <br>
D. 管理系统日常任务的调度<br>
答案：D<br>
<br>
2. 在大多数Linux发行版本中，以下哪个属于块设备 (block devices) ？ <br>
A. 串行口<br>
B. 硬盘 <br>
C. 虚拟终端<br>
D. 打印机<br>
答案：B<br>
<br>
3. 下面哪个Linux命令可以一次显示一页内容？ <br>
A. pause <br>
B. cat <br>
C. more <br>
D. grep <br>
答案：C<br>
<br>
4. 怎样了解您在当前目录下还有多大空间？ <br>
A. Use df <br>
B. Use du / <br>
C. Use du . <br>
D. Use df . <br>
答案：C<br>
<br>
5. 怎样更改一个文件的权限设置？ <br>
A. attrib <br>
B. chmod <br>
C. change <br>
D. file <br>
答案：B<br>
<br>
6. 假如您需要找出 /etc/my.conf 文件属于哪个包 (package) ，您可以执行： <br>
A. rpm -q /etc/my.conf <br>
B. rpm -requires /etc/my.conf <br>
C. rpm -qf /etc/my.conf <br>
D. rpm -q | grep /etc/my.conf <br>
答案：C<br>
<br>
7. 假如当前系统是在 level 3 运行，怎样不重启系统就可转换到 level 5 运行？ <br>
A. Set level = 5 <br>
B. telinit 5 <br>
C. run 5 <br>
D. ALT-F7-5 <br>
答案：B<br>
<br>
8. 那个命令用于改变 IDE 硬盘的设置？ <br>
A. hdparam <br>
B. ideconfig <br>
C. hdparm <br>
D. hddparm<br>
答案：C<br>
<br>
9. 下面哪个命令可以列出定义在以后特定时间运行一次的所有任务？<br>
A. atq<br>
B. cron<br>
C. batch<br>
D. at<br>
答案：A<br>
<br>
10.下面命令的作用是：set PS1="[\u\w\t]\$" ; export PS1<br>
A. 改变错误信息提示<br>
B. 改变命令提示符<br>
C. 改变一些终端参数<br>
D. 改变辅助命令提示符<br>
答案：B<br>
<br>
11.作为一个管理员，你希望在每一个新用户的目录下放一个文件 .bashrc ，那么你应该在哪个目录下放这个文件，以便于新用户创建主目录时自动将这个文件复制到自己的目录下。<br>
A. /etc/skel/<br>
B. /etc/default/<br>
C. /etc/defaults/<br>
D. /etc/profile.d/<br>
答案：A<br>
<br>
12.在bash中，export命令的作用是：<br>
A. 在子shell中运行命令<br>
B. 使在子shell中可以使用命令历史记录<br>
C. 为其它应用程序设置环境变量<br>
D. 提供NFS分区给网络中的其它系统使用<br>
答案：C<br>
<br>
13.在使用了shadow口令的系统中，/etc/passwd和/etc/shadow两个文件的权限正确的是：<br>
A. -rw-r----- , -r--------<br>
B. -rw-r--r-- , -r--r--r--<br>
C. -rw-r--r-- , -r--------<br>
D. -rw-r--rw- , -r-----r--<br>
答案：C<br>
<br>
14．下面哪个参数可以删除一个用户并同时删除用户的主目录？<br>
A. rmuser -r<br>
B. deluser -r<br>
C. userdel -r<br>
D. usermgr -r<br>
答案：C<br>
<br>
15．有一个备份程序mybackup，需要在周一至周五下午1点和晚上8点各运行一次，下面哪条crontab的项可以完成这项工作？<br>
A. 0 13,20 * * 1,5 mybackup<br>
B. 0 13,20 * * 1,2,3,4,5 mybackup<br>
C. * 13,20 * * 1,2,3,4,5 mybackup<br>
D. 0 13,20 1,5 * *  mybackup<br>
答案：B<br>
<br>
16．如何从当前系统中卸载一个已装载的文件系统<br>
A. umount<br>
B. dismount<br>
C. mount -u<br>
D. 从 /etc/fstab 中删除这个文件系统项<br>
答案：A<br>
<br>
17．如果你的umask设置为022，缺省的你创建的文件的权限为：<br>
A. ----w--w-<br>
B. -w--w----<br>
C. r-xr-x---<br>
D. rw-r--r--<br>
答案：D<br>
<br>
18．在一条命令中如何查找一个二进制命令 Xconfigurator 的路径？<br>
A. apropos Xconfigurator <br>
B. find Xconfigurator<br>
C. where Xconfigurator<br>
D. which Xconfigurator<br>
答案：D<br>
<br>
19．哪一条命令用来装载所有在 /etc/fstab 中定义的文件系统？<br>
A. amount<br>
B. mount -a<br>
C. fmount<br>
D. mount -f<br>
答案：B<br>
<br>
20．运行一个脚本，用户不需要什么样的权限？<br>
A. read<br>
B. write<br>
C. execute<br>
D. browse on the directory<br>
答案：B<br>
<br>
21．在Linux中，如何标识接在IDE0上的slave硬盘的第2个扩展分区？<br>
A. /dev/hdb2<br>
B. /dev/hd1b2<br>
C. /dev/hdb6<br>
D. /dev/hd1b6<br>
答案：C<br>
<br>
22．在应用程序起动时，如何设置进程的优先级？<br>
A. priority<br>
B. nice<br>
C. renice<br>
D. setpri<br>
答案：B<br>
<br>
23．在 bash 中, 在一条命令后加入"1>&2" 意味着：<br>
A. 标准错误输出重定向到标准输入<br>
B. 标准输入重定向到标准错误输出<br>
C. 标准输出重定向到标准错误输出<br>
D. 标准输出重定向到标准输入<br>
答案：C<br>
<br>
24．下面哪条命令可以把f1.txt复制为f2.txt?<br>
A. cp f1.txt | f2.txt<br>
B. cat f1.txt | f2.txt<br>
C. cat f1.txt > f2.txt<br>
D. copy f1.txt | f2.txt<br>
答案：C<br>
<br>
25．显示一个文件最后几行的命令是：<br>
A. tac<br>
B. tail<br>
C. rear<br>
D. last<br>
答案：B<br>
 <br>
26.如何快速切换到用户John的主目录下？<br>
A. cd @John<br>
B. cd #John<br>
C. cd &John<br>
D. cd ~John<br>
答案：D<br>
<br>
27.把一个流中所有字符转换成大写字符，可以使用下面哪个命令？<br>
A. tr a-z A-Z<br>
B. tac a-z A-Z <br>
C.sed /a-z/A-Z<br>
D. sed --toupper<br>
答案：A<br>
<br>
28.使用什么命令可以查看Linux的启动信息？<br>
A. mesg -d<br>
B. dmesg<br>
C. cat /etc/mesg<br>
D. cat /var/mesg<br>
答案：B<br>
 <br>
29.运行级定义在：<br>
A. in the kernel<br>
B. in /etc/inittab<br>
C. in /etc/runlevels<br>
D. using the rl command<br>
答案：B<br>
 <br>
30.如何装载(mount)上在 /etc/fstab 文件中定义的所有文件系统？<br>
A. mount -a<br>
B. mount /mnt/* <br>
C. mount <br>
D. mount /etc/fstab<br>
答案：A<br>
 <br>
31.使用ln命令将生成了一个指向文件old的符号链接new，如果你将文件old删除，是否还能够访问文件中的数据？<br>
A. 不可能再访问<br>
B. 仍然可以访问<br>
C. 能否访问取决于文件的所有者<br>
D. 能否访问取决于文件的权限<br>
答案：A<br>
 <br>
32.xt2fs文件系统中，缺省的为root用户保留多大的空间？<br>
A. 3%<br>
B. 5%<br>
C. 10%<br>
D. 15%<br>
答案：C<br>
<br>
33.哪个命令用来显示系统中各个分区中inode的使用情况？<br>
A. df -i<br>
B. df -H<br>
C. free -b<br>
D. du -a -c /<br>
答案：A<br>
<br>
34.多数Linux发行版本中，图形方式的运行级定义为？<br>
A. 1<br>
B. 2<br>
C. 3<br>
D. 5<br>
答案：D<br>
 <br>
35.在系统文档中找到关于print这个单词的所有说明？<br>
A. man print<br>
B. which print<br>
C. locate print<br>
D. apropos print<br>
答案：D<br>
 <br>
36.man 5 passwd 含义是？<br>
A. 显示 passwd 命令的使用方法<br>
B. 显示 passwd 文件的结构<br>
C. 显示 passwd 命令的说明的前五行<br>
D. 显示关于passwd的前五处说明文档。<br>
答案：A<br>
 <br>
37.如何在文件中查找显示所有以" * "打头的行？ <br>
A. find \* file <br>
B. wc -l * < file <br>
C. grep -n * file <br>
D. grep ‘^\*’ file <br>
答案：D<br>
 <br>
38.在ps命令中什么参数是用来显示所有用户的进程的？<br>
A. a<br>
B. b<br>
C. u<br>
D. x<br>
答案：A<br>
 <br>
39.显示二进制文件的命令是？<br>
A. od<br>
B. vil<br>
C. view<br>
D. binview<br>
答案：A<br>
 <br>
40.如何显示Linux系统中注册的用户数（包含系统用户）？<br>
A. account -l<br>
B. nl /etc/passwd |head<br>
C. wc --users /etc/passwd<br>
D. wc --lines /etc/passwd<br>
答案：D<br>
 <br>
41.在一行结束位置加上什么符号，表示未结束，下一行继续？<br>
A. /<br>
B. \<br>
C. ;<br>
D. |<br>
答案：B<br>
 <br>
42.命令 kill 9 的含义是：<br>
A. kills the process whose PID is 9.<br>
B. kills all processes belonging to UID 9.<br>
C. sends SIGKILL to the process whose PID is 9.<br>
D. sends SIGTERM to the process whose PID IS 9.<br>
答案：D<br>
 <br>
43.如何删除一个非空子目录/tmp？<br>
A. del /tmp/*<br>
B. rm -rf /tmp<br>
C. rm -Ra /tmp/*<br>
D. rm -rf /tmp/* <br>
答案：B<br>
 <br>
44.使用什么命令可以在今天午夜运行命令 cmd1 ？<br>
A. at midnight cmd1<br>
B. cron -at "00:00" cmd1<br>
C. batch -t "00:00" < cmd1<br>
D. echo "cmd1" | at midnight<br>
答案：D<br>
 <br>
45.你的系统使用增量备份策略，当需要恢复系统时，你需要按什么顺序恢复备份数据？<br>
A. 最后一次全备份，然后从最早到最近的增量备份<br>
B. 最后一次全备份，然后从最近到最早的增量备份<br>
C. 最早到最近的增量备份，然后最后一次全备份<br>
D. 最近到最早的增量备份，然后最后一次全备份<br>
答案：B<br>
 <br>
46.对所有用户的变量设置，应当放在哪个文件下？<br>
A. /etc/bashrc<br>
B. /etc/profile<br>
C. ~/.bash_profile<br>
D. /etc/skel/.bashrc<br>
答案：B<br>
 
47.Linux系统中，一般把命令 ls 定义为 ls --color 的别名，以便以不同颜色来标识不同类型的文件。但是，如何能够使用原先的ls命令？<br>
A. \ls<br>
B. ;ls<br>
C. ls $$<br>
D. ls --noalias<br>
答案：A<br>
 <br>
48.在Linux系统中的脚本文件一般以什么开头？<br>
A. $/bin/sh<br>
B. #!/bin/sh<br>
C. use /bin/sh<br>
D. set shell=/bin/sh<br>
答案：B<br>
 <br>
49.下面哪种写法表示如果cmd1成功执行，则执行cmd2命令？<br>
A. cmd1&&cmd2<br>
B. cmd1|cmd2<br>
C. cmd1;cmd2<br>
D. cmd1||cmd2<br>
答案：A<br>
 <br>
50.在哪个文件中定义网卡的I/O地址？<br>
A. cat /proc/modules<br>
B. cat /proc/devices<br>
C. cat /proc/ioports<br>
D. cat /io/dma<br>
答案：C<br>
 <br>
51.Linux中，提供TCP/IP包过滤功能的软件叫什么？<br>
A. rarp<br>
B. route<br>
C. iptables<br>
D. filter<br>
答案：C<br>
 <br>
52.如何暂停一个打印队列？<br>
A. lpr<br>
B. lpq<br>
C. lpc<br>
D. lpd<br>
答案：C<br>
 <br>
53.在vi中退出不保存的命令是？<br>
A. :q<br>
B. :w<br>
C. :wq<br>
D. :q!<br>
答案：D<br>
 <br>
54.在 XFree86 3.x 中, 缺省的字体服务器为：<br>
A. xfs<br>
B. xfserv<br>
C. fonts<br>
D. xfstt<br>
答案：A<br>
 <br>
55.使用什么命令检测基本网络连接？<br>
A. ping<br>
B. route<br>
C. netstat<br>
D. ifconfig<br>
答案：A<br>
 <br>
56.下面哪个协议使用了二个以上的端口？<br>
A. telnet<br>
B. FTP<br>
C. rsh<br>
D. HTTP<br>
答案：B<br>
 <br>
57.在PPP协议中，哪个认证协议不以明文传递密码？<br>
A. PAM<br>
B. PAP<br>
C. PGP<br>
D. CHAP<br>
答案：D<br>
 <br>
58.下面哪个文件系统应该分配最大的空间？<br>
A. /usr<br>
B. /lib<br>
C. /root<br>
D. /bin<br>
答案：A<br>
 <br>
59.如何在Debian系统中安装rpm包？<br>
A. alien pkgname.rpm<br>
B. dpkg --rpm pkgname.rpm<br>
C. dpkg --alien pkgname.rpm<br>
D. alien pkganme.rpm ; dpkg -i pkganme.deb<br>
答案：D<br>
<br>
60.在安装软件时下面哪一步需要root权限？<br>
A. make<br>
B. make deps<br>
C. make config<br>
D. make install<br>
答案：D<br>
 <br>
61.什么命令用来只更新已经安装过的rpm软件包？<br>
A. rpm -U * .rpm <br>
B. rpm -F * .rpm <br>
C. rpm -e * .rpm <br>
D. rpm -q * .rpm <br>
答案：B<br>
<br>
62.在 windows 与 Linux 双起动的系统中，如果要让LILO 管理引导，则 LILO 应该放在：<br>
A. MBR<br>
B. /<br>
C. root分区的首扇区<br>
D. /LILO<br>
答案：D<br>
 <br>
63.ldconfig的配置文件是<br>
A. /lib/ld.so<br>
B. /etc/ld.so.conf<br>
C. /etc/ld.so.cache<br>
D. /etc/modules.conf<br>
答案：B<br>
 
64.下面哪个命令可以压缩部分文件：<br>
A. tar -dzvf filename.tgz * <br>
B. tar -tzvf filename.tgz * <br>
C. tar -czvf filename.tgz * <br>
D. tar -xzvf filename.tgz * <br>
答案：C<br>
 <br>
65.网络服务的daemon是：<br>
A. lpd<br>
B. netd<br>
C. httpd<br>
D. inetd<br>
答案：D<br>
 <br>
66.Linux与windows 的网上领居互联，需要提供什么daemon?<br>
A. bind<br>
B. smbd<br>
C. nmbd<br>
D. shard<br>
答案：B<br>
 <br>
67.对于Apache服务器，提供的子进程的缺省的用户是：<br>
A. root<br>
B. apached<br>
C. httpd<br>
D. nobody<br>
答案：D<br>
 <br>
68.sendmail中缺省的未发出信件的存放位置是：<br>
A. /var/mail/<br>
B. /var/spool/mail/<br>
C. /var/spool/mqueue/<br>
D. /var/mail/deliver/<br>
答案：C<br>
 <br>
69.apache的主配置文件是：<br>
A. httpd.conf<br>
B. httpd.cfg<br>
C. access.cfg<br>
D. apache.conf<br>
答案：A<br>
 <br>
70.关于可装载的模块，装载时的参数，如I/O地址等的存放位置是：<br>
A. /etc/conf.modules<br>
B. /etc/lilo.conf<br>
C. /boot/System.map<br>
D. /etc/sysconfig<br>
答案：A<br>
 <br>
71.在 Linux 中，如何关闭邮件提示？<br>
A. biff n <br>
B. mesg n <br>
C. notify off <br>
D. set notify=off<br>
答案：A<br>
 <br>
72.在 bash shell 环境下，当一命令正在执行时，按下 control-Z 会： <br>
A. 中止前台任务 <br>
B. 给当前文件加上 EOF.<br> 
C. 将前台任务转入后台 <br>
D. 注销当前用户<br>
答案：C<br>
 <br>
73.定义bash环境的用户文件是：<br>
A. bash & .bashrc<br>
B. bashrc & .bash_conf<br>
C. bashrc & bash_profile<br>
D. .bashrc & .bash_profile<br>
答案：D<br>
 <br>
74.下面哪条命令用来显示一个程序所使用的库文件？<br>
A. ldd<br>
B. ld so<br>
C. modprobe<br>
D. ldconfig<br>
答案：B<br>
 <br>
75.如何查看一个RPM软件的配置文件的存放位置？<br>
A. rpm -qc rpm1<br>
B. rpm -Vc rpm1<br>
C. rpm --config rpm1<br>
D. rpm -qa --config rpm1<br>
答案：A<br>
 <br>
76.如何查看一个RPM软件的修改记录？<br>
A. rpm -Vc postfix<br>
B. rpm -qpil postfix<br>
C. rpm --changelog postfix<br>
D. rpm -q --changelog postfix<br>
答案：D<br>
 <br>
77.通过Makefile来安装已编译过的代码的命令是：<br>
A. make <br>
B. install<br>
C. make depend<br>
D. make install<br>
答案：D<br>
 <br>
78.什么命令解压缩tar文件？<br>
A. tar -czvf filename.tgz<br>
B. tar -xzvf filename.tgz<br>
C. tar -tzvf filename.tgz<br>
D. tar -dzvf filename.tgz<br>
答案：B<br>
 <br>
79.在 XF86Config 配置文件中，哪个段用来设置字体文件？<br>
A. The Fonts section.<br>
B. The Files section.<br>
C. The xfsCodes section.<br>
D. The Graphics section.<br>
答案：B<br>
 <br>
80.8 bit color 指的是：<br>
A. 64K colors<br>
B. 16K colors<br>
C. 256 colors<br>
D. 16M colors<br>
答案：C<br>
 <br>
81.下面哪个文件用来设置 X window 的显示分辨率？<br>
A. xinit<br>
B. xinitrc<br>
C. XF86Setup<br>
D. XF86Config<br>
答案：D<br>
 <br>
82.哪个变量用来指定一个远程X应用程序将输出放到哪个X server上？<br>
A. DISPLAY<br>
B. TERM<br>
C. ECHO<br>
D. OUTPUT<br>
答案：A<br>
 <br>
83.在xdm的配置目录中，哪个文件用来设置在用户通过xdm登录后自动起动的应用程序？<br>
A. The Xsession file<br>
B. The Xsetup_0 file<br>
C. The Xstart_up file<br>
D. The GiveConsole file<br>
答案：B<br>
 <br>
84.命令 netstat -a 停了很长时间没有响应，这可能是哪里的问题？<br>
A. NFS.<br>
B. DNS.<br>
C. NIS.<br>
D. routing.<br>
答案：B<br>
 <br>
85.ping使用的协议是：<br>
A. TCP<br>
B. UDP<br>
C. SMB<br>
D. ICMP<br>
答案：D<br>
 <br>
86.下面哪个命令不是用来查看网络故障的？<br>
A. ping <br>
B. init<br>
C. telnet <br>
D. netstat<br>
答案：B<br>
 <br>
87.拨号上网使用的协议通常是：<br>
A. PPP<br>
B. UUCP<br>
C. SLIP<br>
D. Ethernet<br>
答案：A<br>
 
88. TCP/IP中，哪个协议是用来进行IP自动分配的？<br>
A. ARP<br>
B. NFS<br>
C. DHCP<br>
D. DNS<br>
答案：C<br>
 <br>
89.下面哪个文件定义了网络服务的端口？<br>
A. /etc/netport<br>
B. /etc/services<br>
C. /etc/server<br>
D. /etc/netconf<br>
答案：B<br>
 <br>
90.下面哪个功能用来生成一个文件的校验码？<br>
A. md5<br>
B. tar<br>
C. crypt<br>
D. md5sum<br>
答案：A<br>
 <br>
91.缺省的，用户邮件放在：<br>
A. ~/mail/<br>
B. /var/mail/<br>
C. /var/mail/spool/<br>
D. /var/spool/mail/<br>
答案：D<br>
 <br>
92.下面哪个文件包含了供 NFS daemon 使用的目录列表？<br>
A. /etc/nfs<br>
B. /etc/nfs.conf<br>
C. /etc/exports<br>
D. /etc/netdir<br>
答案：C<br>
 <br>
93.如何停止一台机器的telnet服务？<br>
A. Put NONE in /etc/telnet.allow<br>
B. Put a line 'ALL:ALL' in /etc/hosts.deny<br>
C. Comment the telnet entry in /etc/inittab<br>
D. Comment the telnet entry in /etc/xinetd.conf<br>
答案：D<br>
 <br>
94.在哪个文件中保存了sendmail的别名？<br>
A. /etc/aliases<br>
B. /etc/mailaliases<br>
C. /etc/sendmail.aliases<br>
D. /etc/sendmail/aliases<br>
答案：A<br>
<br>
95.smbd and nmbddaemons 的配置文件是：<br>
A. /etc/exports<br>
B. /etc/smb.conf<br>
C. /etc/samba/config<br>
D. /usr/local/samba.cfg<br>
答案：B<br>
 <br>
96.下面哪个命令用来卸载一个内核模块？<br>
A. rmmod<br>
B. unmod<br>
C. delmod<br>
D. modprobe<br>
答案：A<br>
 <br>
97.什么情况下必须运行lilo<br>
A. once a day from cron<br>
B. once a week from cron<br>
C. after installing a new kernel<br>
D. after installing a new module<br>
答案：C<br>
<br>
98.什么命令显示所有装载的模块？<br>
A. lsmod<br>
B. dirmod<br>
C. modules<br>
D. modlist<br>
答案：A<br>
<br>
99.下面哪个命令刷新打印机队列？<br>
A. lpflush<br>
B. lprm -<br>
C. lpclear<br>
D. lprm all<br>
答案：B<br>
<br>
100.下面哪个命令可以查看网卡的中断？<br>
A. cat /proc/ioports<br>
B. cat /proc/interrupts<br>
C. cat /proc/memoryinfo<br>
D. which interrupts<br>
答案：B<br>
<br>
