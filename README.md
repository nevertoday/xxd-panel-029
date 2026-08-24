<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 029 项目横幅" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 029

### 把照片画成横向低饱和色域上的松弛蜡粉笔手绘

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#四种输出共享同一种横向色域逻辑)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#边界与信任)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 横向色域 · 浅色蜡粉笔 · 粗纤维手工纸 · Risograph 颗粒 · 松弛手写

XXD Panel 029 是一个面向 Codex 与兼容 Agent 的图像生成 Skill。它保留照片中真实的身份、比例、走势、姿态与关系，再用浅色哑光蜡粉笔将主体概括在米白粗纤维手工纸上。

画面只有一块从当前照片综合色彩与情绪中提炼的横向低饱和纸张色域。主体可按源图重心自然偏置、裁切或跨越色域边界；松弛、断裂、带摩擦的粉蜡笔触，双层纸面、轻微做旧、Risograph 颗粒与柔软手写共同形成安静而现代的纸上编辑视觉。

## 为什么需要 029

普通“蜡笔手绘”很容易退化成儿童卡通、廉价手账、固定米粉色模板，或把一堆贴纸与装饰当成手工温度。

029 的顺序完全相反：

```text
锁定身份／比例／走势／关系 → 从当前照片提炼横向低饱和纸张色域 → 让色域高度回应主体重心 → 用浅色哑光蜡粉笔概括主体 → 按源图偏置、裁切或跨界 → 平衡上下留白 → 加入克制纸纤维与 Risograph 痕迹
```

如果换成一张无关照片，主体走势、横向色域比例、边界跨越、综合色彩、粉蜡笔节奏和手写关系仍然成立，这张图就不属于 029。

## 029 的视觉契约

- **源图身份：** 至少三个专属线索保住主体比例、轮廓走势、姿态、方向、动作、功能与关系。
- **一个横向色域：** 色相、冷暖和明度从当前照片提炼；色域高度、垂直位置与上下米白留白形成有意比例。
- **源图决定跨界：** 主体尺度、偏置、裁切以及是否跨越色域上缘或下缘都回应原图重心和动作，不机械居中。
- **浅色哑光蜡粉笔：** 笔触随性、不规整、略断裂、带粗糙摩擦和纸纤维露出，但关键轮廓仍可读。
- **双层纸面：** 横向色域像第二层低饱和纸张落在粗纤维米白底纸上，只有克制边缘差，不做复杂剪贴。
- **真实印刷痕迹：** 轻微做旧、Risograph 颗粒与极小套印偏差增加手工温度，不变成脏污滤镜。
- **松弛手写：** 一句短句沿色域边缘、主体走势或留白融入，可轻微穿插、错位或跨界。

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2090452158827422135) · 2026-08-20<br>
> GPT2 x 蜡笔 x 松弛感 x 美学提示词 x VOL.029

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090452158827422135"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 029 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090452158827422135"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 029 样张 2"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090452158827422135">查看原推文与完整提示词 →</a></p>

这些样张用于展示 029 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 四种可组合输出模式

可用 `1`、`1+3`、`1、2、4` 或 `全部` 选择一个或多个模式；`全部` 每张源图输出 7 个独立 PNG。模式确定后，Skill 会在生图前继续询问整张最终成品的画幅：`3:4` 原提示词画幅、明确跟随原图、常用比例，或自定义比例／准确像素。不会再静默套用源图尺寸。

| 模式 | 画幅逻辑 | 成品 |
| --- | --- | --- |
| `top-bottom` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在上，029 设计在下，约 50/50 |
| `left-right` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在左，029 设计在右，约 50/50 |
| `design-only` | 用户确认的整张成品画幅 | 029 设计铺满画布，不显示原照片 |
| `wallpaper-pack` | 逐设备确认 | 手机、iPad、电脑、儿童手表四张独立 PNG |

双联默认把原图作为高保真垫图／编辑参考，用一套完整提示词直接生成一张整体成品，让摄影、设计、色彩、光线、文字与含义自然呼应。只有完整画布针对性重试仍失败、用户要求原片逐像素不变、当前通道无法实现目标画幅，或需要无创像素校准时，才启用确定性拼合兜底。

壁纸可选连贯或独立。连贯套装先批准一张 iPad 定调图，另外三张分别参考原图＋同一定调图重新构图；独立套装的四张都只参考原图。两者都不会裁切其他设备成品或串联衍生图。

## 文字像手绘动作一样进入画面

正式生图前，先选择自动文案、自定义文案或无文字。有文字时还要指定目标语言或地区。

自动文案从照片可见或有依据的情绪、动作、状态、关系或隐喻中提炼一句简短短句。它要与当前主体高度绑定，不用空泛诗句冒充高级。

默认只有一句主文案；只有确有信息价值时才增加零至两个微型元素，不会为了显得高级而编造编号、年份、坐标或档案标签。文字使用目标文字系统中自然、柔软、潦草但可读的手写方式，沿色域、主体走势或留白融入；文案仍需通过换图测试。

用户提供最终成稿时逐字保留。用户提供的是方向或可编辑草稿时，才会在保留受众、目的、必备词、语气和潜台词的前提下专业深化。

语言遵循目标受众，而不是用户下指令时使用的语言：

```text
目标市场或受众 > 指定成品语言 > 用户方向语言；都不明确时生图前询问
```

日本版使用自然日语，韩国受众使用自然韩语与正确空格，英国版使用英式英语，阿拉伯语版默认使用自然的现代标准阿拉伯语和真正的从右到左排版。手写会尊重各文字系统的比例、连接、方向与可读性，不模仿拉丁连笔。

## 完整画布优先与位图边界

图像模型负责整张成品的审美重构，双联也默认一次直出完整画布。`scripts/compose_panel.py` 只保留为条件明确的兜底、无创尺寸校准和只读审计工具，不再预先规划每次任务，也不评价审美是否成功。

全部交付为 PNG 位图。每次调用都在 `~/Desktop/xxd/` 下创建新任务；已配置图像通道只返回脱敏状态，不公开供应商、端点、凭据、请求头、提示词、响应或账户信息。SVG、HTML、Canvas、图表和程序绘图不能替代最终作品。

## 生图模型优先级

GPT Image 2 是默认首选，并继续执行本项目现有的高保真垫图、生成前确认整张画幅、双联一次生成完整画布、脚本仅作条件式兜底等逻辑。

当当前工具或已配置兼容通道确实可用，并能满足原图保真、整张成品比例、目标语言文字和连贯壁纸多图参考等要求时，也支持 Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）或其他兼容位图模型。备用模型只替换生成通道，不得改变模式、画幅、文案、语言、壁纸关系和完整画布优先策略。

如果没有合适的生图通道，Skill 会请用户启用生图工具或提供 API Key。用户主动提供的凭据可以用于当前任务，但不得在回复或日志中回显、展示或泄露；未经用户明确要求，不会长期保存凭据或修改供应商、账户、计费及全局路由配置。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-029.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-029" ~/.codex/skills/xxd-panel-029
```

Claude Code 用户可以把同一目录链接到 `~/.claude/skills/xxd-panel-029`。安装后重新启动 Agent 会话。

```text
$xxd-panel-029
把这张照片做成左右双联，文案由你根据照片内涵创作，使用自然韩语。
```

只上传照片也可以调用。Skill 会先用分行编号菜单询问一个或多个模式，再询问文字设置；选择壁纸时还会确认连贯或独立以及设备尺寸。

完整规范：

- [Skill 工作流](SKILL.md)
- [中文完整提示词](references/xxd-panel-029-prompt.zh-CN.md)
- [英文完整提示词](references/xxd-panel-029-prompt.en.md)
- [原始风格提示词](references/029-source.md)

## 边界与信任

- 每张照片只在自己的任务中使用，不借用其他输入、旧成品或样张里的主体、颜色、文案和构图。
- 每次调用都创建新的任务子文件夹；相同原图和参数也要重新生成，旧成品不能冒充当前任务。
- 最终交付为 PNG 位图，不是 SVG、HTML、Canvas 或程序绘图替代品。
- 已配置位图桥接只返回脱敏状态，不显示供应商、端点、请求头、凭据、提示词或服务器响应正文。
- 每个所选普通模式各返回一张；若选择 `wallpaper-pack`，再返回四张独立壁纸。选择 `全部` 时每张原图共返回 7 个 PNG，分处四个同级模式文件夹，绝不生成拼贴总览。

本地拼版需要 Python 3 和 Pillow。安全位图桥接使用 Python 3.11+ 的 `tomllib`。图像生成仍需要主机 Agent 的内置位图能力或已经配置好的兼容位图路径。

## 项目结构

```text
xxd-panel-029/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/（未来本地样张占位）
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-029-prompt.zh-CN.md
    ├── xxd-panel-029-prompt.en.md
    └── 029-source.md
```

## 关于 XXD

XXD 是小小东的品牌名称缩写。项目由 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) 创建并维护。

## 服务与会员

### 深度咨询 · 299 元/小时

Skills 使用的一对一深度咨询按 299 元/小时收费。请通过下方微信二维码联系小小东预约。

### 小小东 Skills 用户交流群 · 入群 99 元

一次支付 99 元加入用户交流群，用于交流工作流、作品与互助；不包含按小时的一对一深度咨询。扫码后请备注“Skills 用户交流群”。

### 知识星球＋成员提示词库 · 699 元/年

[知识星球](https://wx.zsxq.com/group/15554814142882)与[小小东成员提示词库](https://vip.xiaoxiaodong.ai/)是同一份会员权益：**一次年费同时开通两边，无需重复付费。**

1. 在[知识星球](https://wx.zsxq.com/group/15554814142882)开通后，微信联系小小东领取成员提示词库兑换码。
2. 在[成员提示词库](https://vip.xiaoxiaodong.ai/)自助开通后，微信联系小小东邀请进入知识星球。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="小小东付费服务微信二维码" width="320"></a>
</p>

<div align="center">

**让一块横向颜色托住主体，也托住那句说不太完整的话。**

</div>

---

<div align="center">
  <h2>☕ 为开源项目赞助算力</h2>
  <p>如果这个项目为你节省了时间，可以通过微信或支付宝赞助后续测试与生成算力。</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="小小东微信算力赞助二维码" width="180"></a><br>
        <strong>微信算力赞助</strong>
      </td>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="小小东支付宝算力赞助二维码" width="180"></a><br>
        <strong>支付宝算力赞助</strong>
      </td>
    </tr>
  </table>
  <p><sub>赞助完全自愿，不会改变这个开源项目的使用权限。</sub></p>
</div>
