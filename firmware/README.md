# firmware

固件代码放这里。

建议按外设分目录，一个外设一个文件夹：

```
firmware/
├─ led-blink/       # 点灯
├─ uart-printf/     # 串口打印
└─ i2c-sensor/      # 温湿度传感器
```

每个目录里放：`main.c` + 一句说明写了什么、怎么烧进去、怎么验证跑通了。
