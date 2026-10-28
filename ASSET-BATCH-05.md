# 《绣灵志》素材 · Batch 05

第三至七章，以及跨章节人物、技能、物品、特效、头像和两个结局。生成日期：2026-10-29。

**33 张 PNG 原图：26 张九宫格（21 张精灵/角色/道具表 + 5 张地面表），7 张主视觉。**
需求标题写 32 张，但逐项文件名共 33 个，本批按全部 33 个文件交付，没有漏掉第二张拆线者姿态表。

生成方式：内置 image_gen，参考原始 sprite-grid-01 及既有玩家/头像素材；部分内容通过同一工具定向修订。交付 PNG 与选定的生成器输出逐字节一致。
按用户选择保留生成原图，**不使用脚本裁切、缩放、重排、抠图或校正背景**。完整提示词、参考板与修订前稿仅保留本地，不随本次公开上传。

## 尺寸与使用前须知

- 26 张九宫格均为 **1254×1254**；名义切格为 **418×418**。
- 6 张主视觉为 **1672×941**；镜湖主视觉为 **1672×940**，与 1672×941 示例差 1 行像素。没有强制转换为 1920×1080。
- **21 张黑底精灵表均未达到逐像素 #000000；19 张的切格边界检测到明亮像素。** 素材完整生成，但不能当作已严格对齐、可直接无损批切的生产图集。
- 首领动作体型/锚点、玩家动作基线、机关开关状态对齐，以及每美术像素约 6–7 实像素的统一栅格，均未认证；仍需游戏接入前 QA。
- 地面图已生成并提供边缘诊断，但 **不宣称已验证无缝平铺**；未进行游戏内动画或重复铺图测试。

详细尺寸、SHA-256、切线采样、地面边缘诊断与逐图备注见 [机器可读报告](asset-batch-05.json)。

## 文件清单

### 第三章 · 风筝崖

| 原图 | 内容 | 实际尺寸 |
|---|---|---|
| [kite-creatures-01.png](kite-creatures-01.png) | 风筝、石狮、信封蛾等九格生物 | 1254×1254 |
| [boss-kite-01.png](boss-kite-01.png) | 万信风筝首领九种姿态 | 1254×1254 |
| [tiles-04.png](tiles-04.png) | 风筝崖九格地面 | 1254×1254 |
| [kite-props-01.png](kite-props-01.png) | 风筝崖九格场景道具 | 1254×1254 |
| [keyart-chapter3.png](keyart-chapter3.png) | 风筝崖章节主视觉 | 1672×941 |

### 第四章 · 镜湖

| 原图 | 内容 | 实际尺寸 |
|---|---|---|
| [mirror-creatures-01.png](mirror-creatures-01.png) | 镜鱼、纸扎人、镜鹿等九格生物 | 1254×1254 |
| [boss-mirror-01.png](boss-mirror-01.png) | 镜中橡果童九种姿态，修订朝左 | 1254×1254 |
| [tiles-05.png](tiles-05.png) | 镜湖九格地面 | 1254×1254 |
| [mirror-props-01.png](mirror-props-01.png) | 镜湖九格道具与机关 | 1254×1254 |
| [keyart-chapter4.png](keyart-chapter4.png) | 镜湖章节主视觉，含满月 | 1672×940 |

### 第五章 · 绣坊旧城

| 原图 | 内容 | 实际尺寸 |
|---|---|---|
| [town-creatures-01.png](town-creatures-01.png) | 顶针兵、线团犬、剪刀螳螂等九格生物 | 1254×1254 |
| [boss-scissor-01.png](boss-scissor-01.png) | 剪刀将军九种姿态 | 1254×1254 |
| [tiles-06.png](tiles-06.png) | 绣坊旧城九格地面 | 1254×1254 |
| [town-props-01.png](town-props-01.png) | 绣坊旧城九格道具 | 1254×1254 |
| [keyart-chapter5.png](keyart-chapter5.png) | 绣坊旧城章节主视觉 | 1672×941 |

### 第六章 · 冬灶林

| 原图 | 内容 | 实际尺寸 |
|---|---|---|
| [winter-creatures-01.png](winter-creatures-01.png) | 冻柿、爆竹鼠、草鞋等九格生物 | 1254×1254 |
| [boss-nian-01.png](boss-nian-01.png) | 年兽九种姿态 | 1254×1254 |
| [tiles-07.png](tiles-07.png) | 冬灶林九格地面 | 1254×1254 |
| [winter-props-01.png](winter-props-01.png) | 冬灶林九格道具与炉灶状态 | 1254×1254 |
| [keyart-chapter6.png](keyart-chapter6.png) | 冬灶林章节主视觉，冰封年兽与小灶 | 1672×941 |

### 第七章 · 绣卷背面

| 原图 | 内容 | 实际尺寸 |
|---|---|---|
| [reverse-creatures-01.png](reverse-creatures-01.png) | 散线幽灵、线结团、回针蛇等九格生物 | 1254×1254 |
| [boss-unpicker-01.png](boss-unpicker-01.png) | 拆线者首领第一组九种姿态 | 1254×1254 |
| [boss-unpicker-02.png](boss-unpicker-02.png) | 拆线者首领第二组九种姿态 | 1254×1254 |
| [tiles-08.png](tiles-08.png) | 绣卷背面九格地面 | 1254×1254 |
| [reverse-props-01.png](reverse-props-01.png) | 巨针、线轴、倒置铜铃等九格道具 | 1254×1254 |
| [keyart-chapter7.png](keyart-chapter7.png) | 绣卷背面章节主视觉 | 1672×941 |

### 跨章节 · 人物、技能、物品与结局

| 原图 | 内容 | 实际尺寸 |
|---|---|---|
| [npc-bodies-01.png](npc-bodies-01.png) | 九格 NPC 全身像与状态 | 1254×1254 |
| [player-abilities-01.png](player-abilities-01.png) | 橡果童滑翔、钩针、御寒、铃舌等九格姿态 | 1254×1254 |
| [items-04.png](items-04.png) | 九格跨章节物品 | 1254×1254 |
| [effects-02.png](effects-02.png) | 九格跨章节效果 | 1254×1254 |
| [portraits-03.png](portraits-03.png) | 九格对话头像，统一灶神和纸扎人设计 | 1254×1254 |
| [keyart-ending-sew.png](keyart-ending-sew.png) | 缝合结局主视觉 | 1672×941 |
| [keyart-ending-cut.png](keyart-ending-cut.png) | 剪断结局主视觉 | 1672×941 |

## 已完成的定向修订

- 镜中橡果童第 3、6、8 格调整为朝左；玩家第 8 格改成单独铃舌，第 9 格去除外扩浅蓝光晕。
- 绣卷背面第 5 格改成口朝上的倒置铜铃，保留第 9 格正常悬挂的大钟。
- 灶神头像统一为叶饰草帽；纸扎人头像统一为镜湖生物表中的传统纸人服饰。
- 风筝崖与绣卷背面主视觉调整顶部构图；镜湖补满月；冬灶林炉屋改成小灶。
- 缝合结局移除重复烛芯童。修订后原稿另存本地 drafts，未上传。

## 仍需注意的视觉偏差

- [items-04.png](items-04.png)：第3格手镜略偏椭圆而非严格圆形。
- [keyart-chapter4.png](keyart-chapter4.png)：满月已补上，但位于顶部三分之一右侧；顶部并非完全空净，叠加标题时应避开月亮。
- [keyart-ending-sew.png](keyart-ending-sew.png)：重复烛芯童已移除；左侧风筝缩小后仍有部分进入顶部三分之一，标题建议放在上方中央。
- [keyart-ending-cut.png](keyart-ending-cut.png)：部分漂浮生物进入顶部三分之一区域，中央星空仍较空。

## 切格边界检测

下表计数为原图在 x=418、x=836、y=418、y=836 四条线上，最大 RGB 通道值 >16 的像素数。该检测只能提示风险，不能区分散点与主体；不能据此直接删除所有越界像素。

| 图集 | x=418 | x=836 | y=418 | y=836 |
|---|---:|---:|---:|---:|
| [npc-bodies-01.png](npc-bodies-01.png) | 0 | 0 | 0 | 160 |
| [player-abilities-01.png](player-abilities-01.png) | 18 | 7 | 0 | 19 |
| [boss-kite-01.png](boss-kite-01.png) | 11 | 0 | 15 | 0 |
| [kite-creatures-01.png](kite-creatures-01.png) | 0 | 175 | 0 | 296 |
| [kite-props-01.png](kite-props-01.png) | 0 | 20 | 0 | 22 |
| [boss-mirror-01.png](boss-mirror-01.png) | 15 | 11 | 0 | 0 |
| [mirror-creatures-01.png](mirror-creatures-01.png) | 0 | 0 | 0 | 181 |
| [mirror-props-01.png](mirror-props-01.png) | 0 | 0 | 0 | 27 |
| [boss-scissor-01.png](boss-scissor-01.png) | 62 | 18 | 21 | 0 |
| [town-creatures-01.png](town-creatures-01.png) | 0 | 131 | 6 | 222 |
| [town-props-01.png](town-props-01.png) | 0 | 0 | 0 | 231 |
| [boss-nian-01.png](boss-nian-01.png) | 20 | 13 | 0 | 129 |
| [winter-creatures-01.png](winter-creatures-01.png) | 49 | 201 | 7 | 362 |
| [winter-props-01.png](winter-props-01.png) | 0 | 0 | 0 | 76 |
| [boss-unpicker-01.png](boss-unpicker-01.png) | 0 | 0 | 0 | 155 |
| [boss-unpicker-02.png](boss-unpicker-02.png) | 0 | 15 | 58 | 0 |
| [reverse-creatures-01.png](reverse-creatures-01.png) | 0 | 78 | 0 | 37 |
| [reverse-props-01.png](reverse-props-01.png) | 0 | 0 | 0 | 271 |
| [portraits-03.png](portraits-03.png) | 30 | 0 | 0 | 27 |

items-04.png 与 effects-02.png 在上述阈值下四条切线计数均为 0；这不等于它们已通过全部规格。

机关状态诊断：mirror-props-01 前两格同坐标轮廓 IoU 为 0.4688，winter-props-01 为 0.6385。该数值包含材质与效果变化，不单独证明主体锚点是否相同；未把两种状态强行对齐。

## 校验范围

- 已核对：33 个文件名全覆盖、PNG 可解码、实际尺寸、生成输出逐字节一致、SHA-256、背景与切线采样。
- 未核对：游戏内显示/动画、精确碰撞尺寸、严格平铺、像素级姿态锚点一致性。
- 仓库保持公开；只新增本批 33 张图片与本报告、JSON 清单，不覆盖先前批次文件。
