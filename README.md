原来买的4个打算做动捕用，结果发现安装完CL-Eye-Driver-5.3.0.0341驱动后，无法用外部程序驱动摄像头，后来知乎里发现有人解决了这个问题，原因是win10/11下缺乏摄像头directShow驱动的问题。有一个网友开源了github上的PS3EyeDirectShow的驱动。所以，要两个驱动都要安装，才可以在win10\11下，外部程序调用摄像头。

github上有高手解决了此问题，并分享了源码，地址如下：

https://archive.org/details/CLEyeDriver5.3.0.0341Emuline

https://github.com/jkevin/PS3EyeDirectShow

https://github.com/psmoveservice/PSMoveService/wiki/PSEye-Software-Setup-(Windows)
