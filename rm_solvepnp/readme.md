# PNP 函数说明

## 如何调用函数

- 声明一个类型 Rm_Solvepnp
- 例如 Rm_Solvepnp pnp("\_camera_path", "\_pnp_config_path")
- 调用其中的 run_Solvepnp()函数
- 参数主要分为

```C++
  _ballet_speed 当前子弹速度
  _armor_type 装甲板类型 | _width _height 实际宽和高单位为(mm）
  _src_img 原图像
  _rect 旋转矩形 | 外接矩形
```
