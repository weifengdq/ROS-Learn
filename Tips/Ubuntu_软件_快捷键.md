
## 系统设置
使能工作空间： system settings -> appearances -> behavior -> enable workspaces.  

##　安装的软件：  
- 搜狗拼音输入法, 参考[Ubuntu 16.04 LTS安装sogou输入法详解](https://www.cnblogs.com/lrj567/p/6307329.html)   
- 网易云音乐　　
- smplayer, 可以倍速播放([])的视频播放器．安装参考[官网](http://www.smplayer.info/en/downloads)：　

```
sudo add-apt-repository ppa:rvm/smplayer 
sudo apt-get update 
sudo apt-get install smplayer smplayer-themes smplayer-skins 
```
- gitkraken  
- vs code  

- [kicad](http://kicad-pcb.org/download/ubuntu/)
```
sudo add-apt-repository --yes ppa:js-reynaud/kicad-4
sudo apt update
sudo apt install kicad
```

- 为知笔记, 参考[Ubuntu16.04安装为知笔记(WizNote)](https://www.jianshu.com/p/0b719bea9fa8)


- stm32cubemx, 安装参考 [64位Ubuntu 16.04安装STM32CubeMX-4.24.0](https://blog.csdn.net/zoomdy/article/details/79217847)  
```
sudo apt install libc6-i386
sudo apt install default-jre
sudo ./SetupSTM32CubeMX-4.24.0.linux 
```
按照提示一步步安装即可, 然后在默认的安装路径下打开: 
/usr/local/STMicroelectronics/STM32Cube/STM32CubeMX/STM32CubeMX  
或者终端 cd/usr/local/STMicroelectronics/STM32Cube/STM32CubeMX
./STM32CubeMX
安装一些MCU支持包等.  

- TrueStudio, 默认安装到了
/opt/Atollic_TrueSTUDIO_for_STM32_x86_64_9.0.1/
ST-Link/J-Link udev rules to /etc/udev/rules.d/



## 快捷键
终端粘贴: Ctrl+Shift+V
终端开新窗口： Ctrl+Shift+N
终端开新标签： Ctrl+Shift+T  

## 注意
cd /
cd ~