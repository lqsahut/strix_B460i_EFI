# i5 10600 + Rog B460i 核显 Hackintosh EFI
- OpenCore引导macOS Catalina 10.15.6 ++ Win10

### 0、完美程度
- 0、核显加速，显存1536mb（没钱，没上独显）
- 1、睡眠正常（睡眠一晚上依旧可唤醒，今天发现以后1个小bug，睡眠一晚上显示器音频不可识别，之前没出现过）
- 2、cpu睿频正常，单核4.8，全核4.4
- 3、传感器正常工作，cpu温度，ssd温度，风扇转速均可获取（通过istat menus查看）
- 4、USB映射正常（usb2.0 type-c音频口不可识别，其他音频口正常，不过有3.5耳机和显示器扬声器，无所谓；
  usb3.2gen2x2未测试，没有这么高的设备，不过是系统识别出单独走线，符合官方描述，应该可达到20gbps）
- 5、有线网正常工作
- 6、ax200 Wi-Fi可驱动（稳定性弱于USB wifi）
- 7、蓝牙可用
- 8、4k@60显示器输出正常，内建识别，亮度及音量可通过monitorControl控制

### 1、具体不详细介绍，说一些细节
- 0、显示器输出为dp转mini dp，好像加了一个mini dp补丁，具体没在意
- 1、记得修改platforminfo里面的串号，以免不能登陆app store
- 2、若可以修复上述小bug记得跟我分享一下，star也不能少哦

# i5 10600 + Rog B460i + AMD-6650XT Hackintosh EFI 
- OpenCore引导macOS Ventura 13.6.3 + Win10
- EFI-new文件夹

