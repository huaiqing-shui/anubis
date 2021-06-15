# anubis
G-Nut/Anubis 基于VS2019配置Windows可执行文件以及VS项目，2.3版本
是一款在原始观测值层面，提供多频多系统GNSS观测值质量检测与评估的开源C++程序，是GNSS领域为数不多的开放源代码的数据预处理和分析软件包之一。不过官方不免费提供Windows版本可执行文件，需要自己编译。

该软件始于捷克的国家大地测量局、地形与地图制图研究所（Geodetic observatory Pecny (GOP)，Research Institute of Geodesy, Topography and Cartography in Czech Republic）于2011年启动的G-Nut项目。目前最新版为2020-07-18 发布的2.3版本（https://www.pecny.cz/gop/index.php/gnss/sw/anubis）。

Anubis 软件是一款开源免费的命令行应用程序，支持 Windows、Linux 和 macOS 等常见的操作系统。支持在线实时[^RT]/事后[^RX]观测值质量检核。支持GPS、GLONASS、GALILEO、BEIDOU、QZSS、IRNSS等全部导航卫星系统。支持 RINEX 2、3 文件格式。Anubis通过读取用户从命令行，或是XML配置文件输入的参数，就可以对各个卫星系统各个频率的伪距、相位、信噪比观测量进行质量检核与分析操作，生成质量评估xtr文件。在上面的网站中还另外提供Perl绘图脚本plot_Anubis的源码下载，支持从xtr文件中提取多类信息绘制成图。
