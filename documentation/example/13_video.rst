拍摄视频到TF卡存储
===================

例程::

    from mpython import *
    import smartcamera_new as smartcamera

    smart_camera = smartcamera.SmartCamera(tx=Pin.P16, rx=Pin.P15)
    smart_camera.video_capture(choice=1, path='/sd/capture.avi', interval=100000, quality=50, width=320, height=240, duration=10)



mPython图形化示例
----------------
.. figure:: /_static/image/example/video.png
    :align: center
    :width: 1080