---
title: Jolt 刚体
description: Jolt 刚体世界、约束、命令、查询和调试节点。
---

# Jolt 刚体

Jolt 解算器依赖 HoTools 安装包中的 native 后端。文档应明确支持平台和加载失败时的错误信息。

## 注册

- 刚体世界-Jolt 设置属性/设置注册。
- 刚体生成约束属性/约束注册。

通常先由对象属性声明刚体和约束，再用注册节点把声明送入当前物理帧。补写重复注册、对象失效和运行时重建。

## 模拟与结果

- 刚体模拟步。
- 刚体结果-读取状态。
- 刚体约束结果-读取状态。

记录位置、旋转、速度、睡眠、约束冲量或其他输出的坐标与单位。

## 命令

- 设置速度、施加力、施加冲量。
- 设置重力倍率、材质响应、运动质量和激活状态。

每项说明作用时机、世界/局部空间、一次性或持续性，以及静态/运动学对象是否接受。

## 查询与调试

- RayCast：起点、方向、距离、过滤和命中输出。
- Jolt 刚体可视化调试：形状、包围盒、接触、约束和睡眠状态。

## 截图计划

- [ ] `omninode-jolt-register-graph.png`
- [ ] `omninode-jolt-constraint-graph.png`
- [ ] `omninode-jolt-commands.png`
- [ ] `omninode-jolt-raycast.png`
- [ ] `omninode-jolt-debug.png`
- [ ] `omninode-jolt-result.png`

