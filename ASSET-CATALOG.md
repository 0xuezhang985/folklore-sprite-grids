# 铃不响的林子 · 素材目录

本批新增 **12 张生成原图：8 张九宫格（72 个格位）与 4 张单图**。使用内置 image_gen 生成，用户明确选择不做脚本后处理，所有 PNG 保持生成时的原始像素与文件内容。

## 下载与预览

| 分组 | 文件 | 内容 | 实际尺寸 |
| --- | --- | --- | --- |
| P0 · A | [tiles-01.png](tiles-01.png) | 9 种地面纹理 | 1254×1254 |
| P0 · B | [trees-01.png](trees-01.png) | 树木与森林边缘 | 1254×1254 |
| P0 · C | [pickups-01.png](pickups-01.png) | 拾取物与血量图标 | 1254×1254 |
| P0 · D | [props-01.png](props-01.png) | 村庄与剧情道具 | 1254×1254 |
| P1 · E | [effects-01.png](effects-01.png) | 投射物与特效，每格单帧 | 1254×1254 |
| P1 · F | [player-facings-01.png](player-facings-01.png) | 橡果童正面、背面与动作 | 1254×1254 |
| P1 · G | [portraits-01.png](portraits-01.png) | 九位角色对话半身像 | 1254×1254 |
| P2 · H | [sprite-grid-04.png](sprite-grid-04.png) | 九种新生物 | 1254×1254 |
| 主视觉 | [keyart-title.png](keyart-title.png) | 夜林、沉默的钟、橡果童背影 | 1672×941 |
| 主视觉 | [keyart-ending.png](keyart-ending.png) | 黎明、响钟、精怪聚集 | 1672×941 |
| UI | [ui-dialogue-border.png](ui-dialogue-border.png) | 木雕与刺绣对话框边框，中心及外围透明 | 2172×724 |
| UI | [ui-boss-nameplate.png](ui-boss-nameplate.png) | 树桩巨口名牌底图，外围透明，未烘焙文字 | 2172×724 |

## 已知规格偏差：接入前必须阅读

- 八张九宫格的实际画布均为 **1254×1254**，名义格子为 **418×418**；但生成器没有严格按格线排齐所有内容。A、B、E、G、H 的部分格线处检测到非黑像素，直接固定切格存在相邻素材混入或截边风险；未重新排格。F 的最小检测留边仅为 2px。
- 九宫格背景视觉上为黑色，但包含 **#010101 等近黑像素**，不满足逐像素纯 #000000；未做背景归零。
- 两张主视觉实际为 **1672×941**，不是要求的 1920×1080；未放大或补边。
- 两张 UI 使用真实 RGBA 透明通道；对话框中心透明。名牌中心保留深色木板，供游戏叠字。
- 地面贴图的无缝拼接、树冠块的可重复拼接、橡果童动画连续性、UI 九切片拉伸效果与统一 6–7px 艺术像素尺度，**尚未在实际游戏中验证**，不能视为已通过。
- 所有图都保留原始输出；未执行去背、重采样、重排格、逐格切图或美术修正。

每格内容顺序见 [asset-manifest.json](asset-manifest.json)，采用从左到右、从上到下的顺序。完整生成提示词见 [asset-prompts.json](asset-prompts.json)，机器检查数据见 [asset-validation.json](asset-validation.json)。

此前上传的三组精怪与 assets/ 下三套透明底素材保持不变。

