# VMware-autorun-script </br> VMware 自动启动虚拟机脚本

VMware Workstation autorun script on Windows platform </br>
在 Windows 平台上用于开机自动启动 VMware Workstation 虚拟机的脚本

## Before 前情提要
VMware Workstation Pro origin support autorun virtual machine since VMware Workstation Pro 17. <br>
VMware Workstation Pro 17 原生支持开机自动启动。

This repo only record the method to autorun before version 17. </br>
此仓库仅用于记录在 VMware Workstation Pro 17 前的开机自动启动虚拟机的方法。


## Files 包含的文件
scripts </br>
|-- run_server.bat </br>
|-- VM_autorun.vbs

## Usage 使用方法
Put 'VM_autorun.vbs' to %APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup .</br>
将 VM_autorun.vbs 文件放置到 %APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup 文件夹。

Put 'run_server.bat' to somewhere (maybe where VMware installed).  </br>
将 run_server.bat 文件放置到某处（比如 VMware 安装目录）。

Edit path in 'run_server.bat' and 'VM_autorun.vbs' .</br>
修改 run_server.bat 和 VM_autorun.vbs 文件中的路径。

Test it. </br>
测试脚本是否如期运行。

Finish! </br>
完成!
