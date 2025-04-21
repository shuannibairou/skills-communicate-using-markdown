# linux系统的命令
* ls>>列出目录内容
* cd>>切换目录
* pwd>>显示当前工作目录
* mkdir>>创建目录 -p:递归创建目录
* rm>>删除文件或目录
* mv>>mv \[源文件或目录] \[目标文件或目录]，移动文件或目录
* cp>>cp \[源文件或目录] \[目标文件或目录],复制文件或目录
* cat>>cat \[文件名]，将文件的内容输出到终端
* touch>>创建空文件或修改文件时间戳
* less>>分页查看文件内容
* head>>查看文件头部内容

	> head -n 5 example.txt 显示 example.txt 文件的前 5 行内容。

* tail>>查看文件尾部内容

	> tail -n 5 example.txt 显示 example.txt 文件的最后 5 行内容；tail -f log_file.log 可以实时查看 log_file.log 文件的新增内容。

* uname>>显示系统信息
* df>>显示磁盘空间使用情况
* du>>查看目录或文件的磁盘使用情况
* ps>>显示当前进程信息
* who>>显示当前登录用户信息
* top>>实时显示系统进程信息
* free>>显示内存使用情况