---
title: OmniNode 物理世界
description: OmniNode 物理声明、解算器、写回、调试和烘焙的完整入口。
---

# OmniNode 物理世界

物理世界是一套“场景声明 + 节点编排”的系统：先在对象、网格或骨骼属性中声明碰撞和物理参数，再由 OmniNode 收集声明、运行解算器、提交结果，最后预览、写回或烘焙。

## 推荐阅读顺序

1. [[概念与最小流程]]：理解对象范围、帧开始、解算和帧提交。
2. [[碰撞属性与预览]]：配置对象、网格、骨骼碰撞和过滤组。
3. 选择解算器：[[MC2网格与骨骼布料]]、[[SpringBone VRM]] 或 [[Jolt刚体]]。
4. [[写回调试与烘焙]]：观察结果、写回 Blender 并生成动画。

## 添加菜单分类

| 分类 | 作用 |
| --- | --- |
| 物理世界 | 选择对象范围、帧生命周期、结果流、写回与烘焙 |
| 解算器 | MC2、SpringBone VRM、Jolt 刚体等具体域 |
| 物理世界调试 | 快照、文本和可视化调试 |

## 截图计划

- [ ] `omninode-physics-add-menu.png`
- [ ] `omninode-physics-properties-overview.png`
- [ ] `omninode-physics-minimal-graph.png`

