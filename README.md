# softandhard
该项目是个软硬结合的项目，系统分为三部分代码，MircoPython、Android、JavaWeb
MircoPython代码，主要控制单片机，进行命令控制，以及对其开发板上的传感器进行数据接收和命令控制
开发板:STM32F407ZEGT6+ESP8266
Android代码：主要客户端采用TCP/IP协议实现对开发板的简单控制以及数据接收
JavaWeb：主要客户端采用TCP/IP协议实现对开发板的简单控制以及数据接收，同时作为android端与硬件端数据传送的桥梁
System 项目可以直接使用android代码或者Web代码相连
WebControllerSystem部分代码则使web端作为android端与硬件端数据交互的桥梁
