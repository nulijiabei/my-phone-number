---------------
Sim

[![GoDoc](https://godoc.org/github.com/nulijiabei/sim?status.svg)](https://godoc.org/github.com/nulijiabei/sim)

暂时设计支持自动写入本机号,但是框架支持任意电话薄,任意内容

查看支持的类型(AT+CPBS=?)输出,+CPBS: ("SM",”FD”,”ON”,"EN")

选择电话簿类型,(AT+CPBS=“ON”)进入本机号码簿

读取电话簿内容,(AT+CPBR=1)读取第一个号码

写号码到电话簿,(AT+CPBW=1,”18600000000”,128,”Danoo”)

