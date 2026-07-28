---
title: RBF 传递
description: 使用低模 Cage 和 KNN/RBF 方式传递形变。
---

# RBF 传递

入口为 `N > HoTools > Rbf`。

## 生成低模 Cage

从目标或源模型生成用于空间插值的低模 Cage。补写简化方式、分辨率、包裹关系和手动调整要求。

## KNN 传递

根据邻近点和 RBF/KNN 参数把源形变传给目标。记录源/目标/Cage 选择、邻居数、半径、正则化、输出形态键和耗时。

## 删除 RBF 结果键

按命名或内部标记清理由本流程生成的形态键。说明是否会误删用户同名键。

## 与普通形态键传递的选择

拓扑和点序一致时优先考虑 [[../04-形态键/形态键传递|形态键传递]] 的点序方式；拓扑不同且形变需要空间插值时再考虑 RBF。

## 截图计划

- [ ] `rbf-panel-overview.png`
- [ ] `rbf-generate-cage.png`
- [ ] `rbf-transfer-settings.png`
- [ ] `rbf-transfer-result.png`

