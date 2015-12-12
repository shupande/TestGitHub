#README

这个是在Sublime text 3 里面的一个git测试。
我尝试在这里添加一个文件并上传到github的仓库中。

但是在我提交Git:push命令的时候出现了一个提示如下：

fatal: could not read Username for 'https://github.com': Device not configured

显示设备没有配置.

Google了半天发现可能是git的方式不对。在sublime下要使用ssh的模式才可以push成功。所以通过命令Git:add remote打开设置，设置origin然后再下一步中填入ssh方式的地址就可以了。

弄了一天我决定写一篇博客记录一下整个安装的过程，怕以后忘记。