# onscripter-jh-gpm2804
[WIP] My ONScripter-jh Waveshare GPM2804 port

## Original ONScripter-Jh readme
```
ONScripter是一个开源的NScripter脚本解释工具，主要由Ogapee开发维护
原版的Readme请查看Readme.old。

这是一个修改版的ONScripter源码，在GPLv2协议下发布，使用时请遵守。

修改目标：
	提供比原版ONScripter更好的性能，适当增加一些功能
	添加中文支持
	尽可能的兼容原版ONS脚本
	
进度

	SDL2分支提供各种改进并可在SDL2环境编译
	目前Windows、Android、iOS、Linux、Windows Phone平台均编译通过实测可用，其余平台未测试
```

## How to Build  
* make clean  
* make -j8   

## Prebuild for onscripter-jh-sdl2   
* sudo apt install libsdl2-dev liblua5.1-0-dev libsdl2-image-dev libsdl2-ttf-dev libsdl2-mixer-dev libbz2-dev libfontconfig1-dev libogg-dev libvorbis-dev  

## Bugs and TODO
* Sound not good
* key mapping not good
* embed to retropie menu  
see https://sirius10.net/RaspberryPi/ONScripter.html  
/opt/retropie/configs/ports   
