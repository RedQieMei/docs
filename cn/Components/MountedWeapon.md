# TankTurret

## 描述
从[Weapon](./Weapon.md)类派生

## 用法

## 注释

## 变量
| 名称 | 类型 | 描述 |
| ----------- | ----------- | ----------- |
| overrideCamera | Camera | 优先使用的摄像机（超越控制） |
| aimCamera | Camera | 瞄准用摄像机（这样才能更改fov） |
| aimChangeSpeed |float  | 瞄准速度（fov变化速度） |
| vehicleRigidbodyRecoilForce | float | 载具刚体后坐力，但是这是真的能导致载具移动的，跟weapon脚本里的后坐力不是一个意思 |