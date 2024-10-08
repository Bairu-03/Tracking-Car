# STM32F103工程模板及常用外设驱动
### 2024.5.14
- 实现TIM2四路PWM输出（PA0 - PA3）

### 2024.5.15
- 完成五路红外寻迹模块驱动
- 优化电机驱动文件
- 优化PWM驱动，实现输入百分比控制PWM

### 2024.5.16
- 关闭JTAG，保留SWD，释放PA15、PB3、PB4作为普通IO口（在InfTrack.c中）

### 2024.7.18
- 修复OLED显示浮点数时可能出现数字错位的bug
- 完善OLED水平滚动显示功能

### 2024.9.7
- 优化串口驱动
- 优化OLED驱动

### 2024.9.8
- 将OLED驱动和模拟I2C驱动分离
- 完善OLED滚动显示功能驱动
- 增加清空OLED指定行功能
- 增加调节OLED对比度功能
- 增加设置OLED显示模式功能（正显/反显）
- 增加OLED测试函数（强制全屏亮）

### 2024.10.7
- 此次提交将原来的寻迹小车项目修改为STM32模板项目
- 调整工程目录结构
- 将OLED驱动中的指令常量宏定义修改为枚举类型
