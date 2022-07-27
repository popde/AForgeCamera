# AForgeCamera
aardio调用AForge.video.DirectShow免费实现摄像头采集和上下左右镜像功能

这次我们使用开源免费的AForge.video.DirectShow实现摄像头采集和上下左右镜像功能,
AForge也是异步使用picturebox来实现,
所以,我们在aardio里也给c#窗体添加个picturebox , 然后利用异步回调更新图片.
