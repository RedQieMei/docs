---
category: 
- 组件
- Custom  GameMode
---
# TriggerLookAt
## 描述
从[TriggerReceiver](./TriggerReceiver.md)类派生

使AI看向指定的位置，也可以停止AI看向的位置
## 用法

挂载在任意空物体上即可

## 注释

玩家会忽略此组件

## 变量
| 名称 | 类型 | 描述 |
| ----------- | ----------- | ----------- |
| Type | enum | 看向目标&停止看向目标 |  
| lookTarget | Transform | 要看向的目标位置 |  
| actor | ActorReference | 目标人员 |  
