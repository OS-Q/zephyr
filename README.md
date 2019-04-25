﻿# [直流信号](https://github.com/OS-Q/W1)
[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)
####  qitas@qitas.cn
#### 归属状态数据：[M1](https://github.com/OS-Q/M1)
#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)
Edge-Q -> 体系 Q[1,4] -> 节点 M[1,12] -> 平台 W[1,52] -> 设备 D[1,365]
### [平台描述](https://github.com/OS-Q/W1/wiki) 

直流信号平台，包括电信号和磁信号的获得，也是很多基础数据的转换入口，大部分的物理数据都可以通过相应的电信号或磁信号被获得，进而被表征还原。

直流信号数据生产平台，通过各种规格的ADC设备及相应的磁力设备，直流信号设备通过标准数据协议和串口向外输出数据。

### [平台资源](https://github.com/OS-Q/W1/wiki) 

- [资源](src/)
- [文档](docs/)

### [平台结构](https://github.com/OS-Q/W1) 

* M1：[状态数据](https://github.com/OS-Q/M1)
	* W1：[电压输入](https://github.com/OS-Q/W1)
		* D1：[ADC低成本](https://github.com/OS-Q/D1)
		* D2：[ADC性价比](https://github.com/OS-Q/D2)
		* D3：[ADC低功耗](https://github.com/OS-Q/D3)
		* D4：[ADC高密度](https://github.com/OS-Q/D4)
		* D5：[ADC高精度](https://github.com/OS-Q/D5)
		* D6：[电流转换](https://github.com/OS-Q/D6)
		* D7：[电容转换](https://github.com/OS-Q/D7)
	* W2：[按键输入](https://github.com/OS-Q/W2)
	* W3：[阈值监控](https://github.com/OS-Q/W3)
	* W4：[生存监控](https://github.com/OS-Q/W4)




### [OS-Q : Operation System for edge devices](http://www.OS-Q.com/Edge/W1)
####  2019-4-25  
