# Assembly Language
## 基本概念
汇编语言: 
* 汇编语言（assembly language）是直接面向处理器（Processor）的程序设计语言
* 汇编语言是一种用于电子计算机、微处理器、微控制器或其他可编程器件的低级语言，亦称为符号语言。
* 在汇编语言中，用助记符（Mnemonics）代替机器指令的操作码，用地址符号（Symbol）或标号（Label）代替指令或操作数的地址。
* 在不同的设备中，汇编语言对应着不同的机器语言指令集，通过汇编过程转换成机器指令。普遍地说，特定的汇编语言和特定的机器语言指令集是一一对应的,不同平台之间不可直接移植

## 开始学习
### 1. 配置环境
DOSBox 0.74-2
debug.exe
link.exe
masm.exe

1. DOSBox 0.74-2 安装好
2. 将其余三个exe 放在自定义文件夹 D:\softwaredata\small\Asm
3. 打开DOSBox 输入命令 mount c:  D:\softwaredata\small\Asm, 回车,输入c: 进入dos 下的C盘
4. 为了避免在每次启动DOXBox的时候都输入这个映射命令, 可以在primary settings from config file C:\Users\Frank\AppData\Local\DOSBox\dosbox-0.74-2.conf 文件中最后自动输入下输入上述命令,则启动输入,更方便

注: mount c: d:\Asm 意思是将PC的D盘目录映射为dos下的C盘。这样你在dos里打C:回车，进入的就是你pc上的D盘，dir的话，显示的会是D盘下的文件，然后就可以在这里操作了

