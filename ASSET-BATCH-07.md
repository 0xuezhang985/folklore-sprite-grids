# 绣灵志 · Batch 07

**13 张原图 / 117 个帧位 / 每张 1254×1254 PNG / 3×3 名义网格（418px）。**

> **当前交付是原始生图素材，不是已完成配准的成品动画。**
> 已执行旧表与新表 50% 叠合、帧对及循环首尾检查，仍有主体漂移、尺寸差异和切格交界像素。
> 沿用用户此前“上传原图并注明规格偏差”的选择；没有脚本改背景、缩放、裁切、重新居中或拆帧。

## 下载清单

| 文件 | 内容 | 原图 |
|---|---|---|
| [wick-walk-01.png](wick-walk-01.png) | 烛芯童：侧面与正面步行 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/wick-walk-01.png) |
| [wick-walk-02.png](wick-walk-02.png) | 烛芯童：背面步行与互动 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/wick-walk-02.png) |
| [boss-nian-02.png](boss-nian-02.png) | 年兽：待机、潜行与激怒 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/boss-nian-02.png) |
| [boss-mirror-02.png](boss-mirror-02.png) | 镜童：左向奔跑与下潜 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/boss-mirror-02.png) |
| [boss-scissor-02.png](boss-scissor-02.png) | 剪刀将军：重步、受击与二阶段 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/boss-scissor-02.png) |
| [boss-unpicker-03.png](boss-unpicker-03.png) | 拆线人一形态：滑行与战前对话 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/boss-unpicker-03.png) |
| [boss-unpicker-04.png](boss-unpicker-04.png) | 拆线人真身：漂移与战后跪谈 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/boss-unpicker-04.png) |
| [boss-kite-02.png](boss-kite-02.png) | 万信风筝：振翅、断线与战后对话 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/boss-kite-02.png) |
| [boss-ferryman-02.png](boss-ferryman-02.png) | 渡者：撑船、受击与坐谈 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/boss-ferryman-02.png) |
| [caravan-anim-01.png](caravan-anim-01.png) | 行商獾与茶婆婆 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/caravan-anim-01.png) |
| [caravan-anim-02.png](caravan-anim-02.png) | 补锅鼹与独眼信鸽 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/caravan-anim-02.png) |
| [caravan-anim-03.png](caravan-anim-03.png) | 照镜猫与老绣娘 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/caravan-anim-03.png) |
| [caravan-anim-04.png](caravan-anim-04.png) | 灶君与商队闲暇动作 | [下载](https://raw.githubusercontent.com/0xuezhang985/folklore-sprite-grids/main/caravan-anim-04.png) |

## 检查结果与限制

- 13 张均成功解码为 1254×1254 PNG；逐文件 SHA-256 及 Git blob 校验值见 [机器可读报告](asset-batch-07.json)。
- 图像文件逐字节等于选定的内置 image_gen 输出；AI 定向修订的旧稿与完整提示词仅保留本地。
- 背景肉眼近黑，但外边缘 8px 带检测到 RGB 通道值 1–4；**没有通过严格 #000000 纯黑检查**。
- **12/13 张**在 x/y=418、836 的至少一条切线上检测到 max RGB >16 的像素。包括火焰、羽毛、线尾、水花及邻格局部；不能保证固定切格后不截断素材。
- 17 个角色/朝向的只读浏览器叠图检查已完成。待机、说话对及跨行循环均可见不同程度重影，**相同中心、脚底线和原角色尺寸的要求未通过**。
- 本地预览成功加载 22 个原图 URL、17 个检查卡片并运行 8 个动画 tick，无页面错误；这只证明预览可运行，**不证明动画无抖动或已接入游戏**。
- 像素颗粒约 6–7px 的一致性未定量认证；部分说话/步行动作变化幅度或交替腿部表达不足。
- 镜童保持朝左；图中未见文字、边框和水印。多数人物沿用参考图的 3/4 朝向，不作为严格正侧面认证。

## 帧序与逐表偏差

下面为设计帧序（按从左到右、从上到下），不等同于动作或配准全部合格。

### wick-walk-01.png

1. 侧面左脚触地；2. 侧面经过位；3. 侧面右脚触地；4. 侧面经过位；5. 正面左脚触地；6. 正面经过位；7. 正面右脚触地；8. 正面经过位；9. 正面眨眼。

- 跨行的步行循环存在头部和脚底位置漂移；未通过无抖动配准。
- 本表四条精确切线没有阈值以上像素，但不代表已满足统一留白与动画基准。

### wick-walk-02.png

1. 背面左脚触地；2. 背面经过位；3. 背面右脚触地；4. 背面经过位；5. 正面对话闭口；6. 正面对话张口；7. 正面吸气；8. 欢呼跳起；9. 向右指路。

- 初稿多画一人，已重新生成并确认九格。
- 背面步行中部分经过位与触地位区分不足；动作幅度与规定的一像素变化未通过验证。
- 跨行位置偏移，火焰进入切格交界。

### boss-nian-02.png

1. 呼气待机；2. 吸气待机；3. 潜行左脚接触；4. 潜行经过位；5. 潜行右脚接触；6. 潜行经过位；7. 受击；8. 激怒待机一；9. 激怒待机二。

- 主体与旧表叠合不完全，跨行潜行存在位置变化；未验证四足交替与首尾无缝。
- 鬃毛、雪花和地面碎屑越过部分切格交界。

### boss-mirror-02.png

1. 待机呼气；2. 待机吸气；3. 左向跑接触一；4. 左向跑经过位一；5. 左向跑接触二；6. 左向跑经过位二；7. 受击；8. 半身入镜；9. 完全下潜末段。

- 已修订第九格，移除水面上的整面盾牌；刀尖在最终图中辨识度不足。
- 所有角色朝左；存在待机横向漂移和跨行奔跑的脚底线变化。
- 刀尖、涟漪或碎片触及部分纵向切线。

### boss-scissor-02.png

1. 一阶段待机一；2. 一阶段待机二；3. 重步接触一；4. 重步经过位一；5. 重步接触二；6. 重步经过位二；7. 受击；8. 二阶段步行一；9. 二阶段步行二。

- 保留一阶段剑盾与二阶段双刀；二阶段两帧的交替脚步不够明显。
- 循环跨行脚底线漂移；二阶段动作未认证为可无缝播放。

### boss-unpicker-03.png

1. 待机一；2. 待机二；3. 线摆向左；4. 线摆收拢一；5. 线摆向右；6. 线摆收拢二；7. 受击；8. 站姿对话闭口；9. 站姿对话张口。

- 待机和循环叠图存在主体位置重影；对话嘴部开合辨识度偏弱。
- 袖线和下摆邻近或越过切格交界。

### boss-unpicker-04.png

1. 松线待机；2. 收线待机；3. 线尾向左；4. 收拢一；5. 线尾向右；6. 收拢二；7. 受击；8. 战后跪姿闭口；9. 战后跪姿说话。

- 第五格已改为线尾向右，第九格抬手已降低；战后两格保留更小跪姿。
- 第五格修订同时改变部分躯干朝向和位置，不能视为只改变线尾的精准编辑。
- 线体、面环和循环中心仍漂移，部分线尾跨格；嘴线变化辨识度不足。

### boss-kite-02.png

1. 双翅平展；2. 双翅上扬；3. 双翅平展；4. 双翅下压；5. 断线振翅上扬；6. 断线振翅下压；7. 受击纸裂；8. 落地折翅闭口；9. 落地折翅说话。

- 振翅、断线、受击与落地说话均有独立帧位。
- 翼端触及纵向切格线；振翅中心未固定，战后说话抬翅幅度大于轻微变化要求。

### boss-ferryman-02.png

1. 低位待机；2. 浮动待机；3. 前方落篙；4. 向后撑篙；5. 提篙回收；6. 向前伸篙；7. 受击摇船；8. 战后坐谈闭口；9. 战后坐谈张口。

- 撑篙四步和战后坐直对话已生成。
- 船体跨行位置及局部横向位置不一致，灯笼待机摆动方向不够明确；不能直接作为原位循环。
- 水花和受击碎屑进入横向切格交界。

### caravan-anim-01.png

1. 行商呼气；2. 行商吸气；3. 行商闭口说话；4. 行商张口说话；5. 茶婆呼气；6. 茶婆吸气；7. 茶婆闭口说话；8. 茶婆张口说话；9. 茶婆倾头倒茶。

- 茶婆保留茶壶头造型，末格从自身壶嘴倒茶。
- 待机对存在横向主体漂移；跨行说话变化不止嘴部与手势。
- 蒸汽或摆件触及切格线。

### caravan-anim-02.png

1. 补锅鼹呼气；2. 补锅鼹吸气；3. 补锅鼹闭口说话；4. 补锅鼹张口说话；5. 信鸽待机一；6. 信鸽待机二；7. 信鸽闭喙说话；8. 信鸽张喙说话；9. 补锅鼹跪姿敲锅。

- 保留锅帽、工具带、独眼、邮袋与末格修锅动作。
- 旧表对照和说话对存在位置差异；嘴部之外的肢体变化偏大。
- 锤头、羽毛和相邻帧局部进入切格交界。

### caravan-anim-03.png

1. 照镜猫待机一；2. 照镜猫待机二；3. 照镜猫闭口说话；4. 照镜猫张口说话；5. 绣娘呼气；6. 绣娘吸气；7. 绣娘闭口说话；8. 绣娘张口说话；9. 绣娘穿针。

- 末格为全身穿针动作；未替换成半身图。
- 尾巴、镜面及身体位置在待机对中同时变化；老绣娘相对旧表的位置和尺寸未严格匹配。
- 发髻针饰进入横向切格线。

### caravan-anim-04.png

1. 灶君呼气；2. 灶君吸气；3. 灶君闭口抚须；4. 灶君张口举炉；5. 行商大笑；6. 信鸽啄地；7. 照镜猫举镜；8. 茶婆闭眼饮茶；9. 灶君扇火。

- 已把错误的“老绣娘饮茶”替换为茶壶头茶婆婆饮茶。
- 灶君待机和说话帧仍存在位置重影，角色对旧表的尺寸与基线未严格一致。
- 底排部分装饰进入横向切格交界。

## 本次公开范围

仅公开这 13 张选定 PNG、本文档及机器可读报告。未公开来源 Gist 全文、完整提示词、本地路径、参考图副本或被替换的草稿。

生成方式：内置 image_gen；五次定向 AI 修订（包括烛芯童布局与位置、镜童下潜、拆线人线尾/手势、茶婆角色纠正）。未采用脚本绘制或后处理。

**接入建议：先按角色重新建立锚点和尺度，再处理背景与边缘；不要直接宣称这批素材已经达到无抖动循环验收。**
