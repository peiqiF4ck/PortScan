# PortScan
端口扫描工具后续将集成到webframeworktools工具里面这里先单独开一个项目吧</br>
软件截图:
![端口扫描动态测试截图](https://raw.githubusercontent.com/peiqiF4ck/PortScan/refs/heads/main/%E8%BD%AF%E4%BB%B6%E9%A6%96%E9%A1%B5%E6%88%AA%E5%9B%BE.png)
端口扫描</br>
用法: Scan.exe -ip <IP|ip.txt> -port <Port|port.txt> [-thread <Threads>] [-timeout <Timeout>] [-banner <yes|no>] [-type <ping|tcp>] [-export <Port>]</br>
Author:peiqiF4ck  https://peiqif4ck.github.io/</br>
ip地址可以是txt文件一行一个也可以是ip地址</br>
port端口号可以是txt文件一行也可以是端口号</br>
export(排除的端口号)只能是端口号不支持txt</br>
ip支持格式:192.168.1.1,192.168.1.1-255,192.168.1.1-192.168.1.255,192.168.1.1,192.168.1.2,192.168.1.1/24/8/16</br>
端口号支持,和-格式80,81或者81-82.默认端口超时时间为9000。如果输入20以下的数字那么就是9000。否则就是你输入的超时时间。如果想加请指定参数-timeout 10000</br>
默认使用tcp扫描并且识别banner信息,如果想使用ping探活之后在扫描请加-type指定为ping</br>
默认线程20更改线程数-thread 100,不识别banner只端口扫描指定参数-banner no </br>
部分参数用法</br>
Scan.exe -ip 192.168.1.1 -port 80 -thread 100 -timeout 9000 -banner no -type ping -export 80</br>
Scan.exe -ip 192.168.1.1 -port 80 -thread 100 </br>
Scan.exe -ip 192.168.1.1 -port 80  -timeout 9000</br>
Scan.exe -ip 192.168.1.1 -port 80  -type ping</br>
Scan.exe -ip 192.168.1.1</br>
Scan.exe -ip ip.txt -port port.txt</br>
端口扫描
![端口扫描动态测试截图](https://raw.githubusercontent.com/peiqiF4ck/PortScan/refs/heads/main/%E8%BD%AF%E4%BB%B6%E5%8A%A8%E6%80%81%E6%89%AB%E6%8F%8F%E6%88%AA%E5%9B%BE.gif)

视频教程</br>
https://www.youtube.com/watch?v=W3aJ4n5u0jg</br>
